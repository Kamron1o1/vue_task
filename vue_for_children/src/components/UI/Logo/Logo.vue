<template>
    <div :class="styles.logo">
        <img src="@/assets/images/logo.svg" alt="logo">
    </div>
</template>

<script>
    import styles from "./Logo.module.scss"
    export default {
        name: "Logo",
        data(){
            return{
                styles
            }
        }
    }
</script>

<style scoped>

</style>