<template>
    <Container !class="container">
        <slot>
            Hello beach
        </slot>
    </Container>
</template>

<script>
    import styles from "@/components/Container/container.module.scss"
    export default {
        name: "Container",
        components:{
            styles
        }
    }
</script>

<style scoped>

</style>