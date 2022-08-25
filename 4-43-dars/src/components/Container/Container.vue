<template>
<Container>
    <slot>
<card></card>
    </slot>
</Container>
</template>
<script>
    import styles from './container.module.css'
    export default {
        name: "Container",
    data()
    {
        return {
            styles
        }
    }
    }
</script>