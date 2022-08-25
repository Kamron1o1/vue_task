<template>
<Navbar/>
  <Header/>
  <Main/>
</template>

<script>

import Header from "./components/Header";
import Main from "./components/Main";
import Navbar from "./components/Navbar";


export default {
  name: 'App',
  components: {
   Navbar,
    Header,
    Main

  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
  }

</style>
