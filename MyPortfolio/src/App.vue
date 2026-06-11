<template>
  <navbar/>
  <router-view/>
  <footers/>

</template>

<script>
import navbar from './components/Navbar.vue'
export default {
  components: {
    navbar
  }


}

</script>

<style>
/* #app {
  margin: 0;
  padding: 0;
  text-align: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
   overflow: hidden;
   scroll-behavior: smooth;
} */
</style>