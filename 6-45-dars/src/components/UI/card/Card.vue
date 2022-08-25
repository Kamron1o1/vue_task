<template>
    <div :class="styles.card">
        <div :class="styles.card_name">
            <h4>kamron </h4>
        </div>
        <div :class="styles.card_country">
            uzb
        </div>
        <div :class="styles.card_id"><h1>101</h1></div>
    </div>

</template>

<script>
    import styles from "./Card.module.scss"
    export default {
        name: "Card",
        card:{
            styles
        }
    }
</script>

<style scoped>

</style>