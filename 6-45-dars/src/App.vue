<template>
<Users/>
    <Card/>
</template>

<script>
import '@/assets/style/index.scss'
import Users from "./components/section-users/Users";
import Card from "./components/UI/card/Card";

export default {
  name: 'App',
    components: {
      Users, Card
    },
}

</script>


