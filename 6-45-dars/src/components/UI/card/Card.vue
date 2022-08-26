<template>
    <div :class="styles.card">
        <div :class="styles.card_name">Name:{{name}}</div>
        <div :class="styles.card_country">Country:{{country}}</div>
        <div :class="styles.card_id">Id:{{id}}</div>
    </div>
</template>

<script>
    import styles from "./Card.module.scss"
    export default {
        name: "Card",
        props: {
            name: {type: String, default:"ismini yoz" },
            country: {type: String, default:"qaysi mamlakatdan san" },
            id: {type: Number, default:"" },
    },

        data(){
            return{
                styles
            }
        }
    }
</script>
