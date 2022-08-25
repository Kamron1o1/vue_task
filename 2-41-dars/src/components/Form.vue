<template>
    <form action="">
        <input @input="accept" type="text" placeholder="name">
        <input @input="accept" type="text" placeholder="LastName">
        <input @input="accept" type="num" placeholder="Age">
    </form>
    <button>Ready</button>
</template>

<script>
    export default {
        name: "Form",
        methods: {
            accept (e){
                console.log(e.target.value)
            }
        }
    }

</script>

<style scoped>

</style>