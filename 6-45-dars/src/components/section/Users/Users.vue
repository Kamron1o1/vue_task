<template>
    <Container>
        <div :class="styles.users" >
        <form action="" :class="styles.users_form" @submit.prevent="addUser" ref="form">
           <h1 :class="styles.users_title"></h1>
            <div  :class="[styles.users_input,'input', user.nameError && error]">
                <label for="name" class="inout_label">Name</label>
                <input v-model="user.name" type="text" id="name" class="input_area" placeholder="Name please">
            </div>
            <div :class="[styles.users_input, 'input', user.countryErro && error ]" >
                <label for="country" class="inout_label">Country</label>
                <input v-model="user.country" type="text" id="country" class="input_area" placeholder="Country please">
            </div>
            <Button :class="styles.users_btn">Add User</Button>
        </form>
        <div :class="styles.users_container">
            <Card v-for="item in user"
                  :key="user.id"
                  :name="user.name"
                  :country="user.country"
                  :id="user.id"
            />
        </div>
        </div>
    </Container>
    
</template>

<script>
    import styles from "./Users.module.scss"
  import Button from "../../UI/Button/Button";
  import Container from "../../UI/Container/Container";
  import Card from "../../UI/Card/Card";
export default {
    name: "Users",
    components: {Button, Container, Card},
    data(){
        return{
                styles,
                users:[],
                user:{
                    name:"",
                    country:"",
                    nameError: false,
                    countryErro:false,
                }
        }
    },
    methods: {
        addUser() {
            this.checkName();
            this.checkCountry();
            if (this.checkName() && this.checkCountry()) {
                const user = {
                    name: this.user.name,
                    country: this.user.country,
                    id: Math.round(Math.random() * Date.now())
                };
                this.users.push(users);
                this.user.name = "";
                this.user.country = "";
            }

        },
        checkName() {
            if (this.user.name.trim()) {
                this.user.nameErro = false;
                return true
            } else {
                this.user.nameErro = true;
                return false
            }
        },
        checkCountry() {
            if (this.user.country.trim()) {
                this.user.countryErro = false;
                return true
            } else {
                this.user.countryErro = true;
                return false
            }
        }
    }
}
</script>
