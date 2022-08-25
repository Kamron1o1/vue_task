<template>
    <nav :class="styles.nav">
        <Container>
            <div :class="styles.nav_body">
                <a href="#" :class="styles.nav_logo">
                    <Logo/>
                </a>
                <ul :class="styles.nav_menu">
                    <li
                            :class="styles.nav_menu_item"
                            v-for="item in menu"
                            :key="item.id"
                    >
                        <a
                                :href="item.link"
                                :class="styles.nav_menu_link"
                        >
                          {{item.name}}
                        </a>
                    </li>

                </ul>


            </div>
        </Container>
    </nav>
</template>

<script>
    import Logo from "../../UI/Logo/Logo";
    import styles from "./Navbar.module.scss"
    import Container from "../../UI/Container/Container";

    export default {
        name: "Navbar",
        components: {
            Container,
            Logo
        },
        data() {
            return {
                styles,
                menu: [
                    {name: "Home", link: "#", id: 1},
                    {name: "About us", link: "#", id: 2},
                    {name: "Testimonials", link: "#", id: 3},
                    {name: "Career", link: "#", id: 4},
                    {name: "Contact", link: "#", id: 5},
                ]
            }
        }
    }
</script>

