<template>
  <Navbar :logo="logo_src" :alt="alt_name"/>
  <router-view/>
  <Footer />
</template>

<script>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';

  export default {
    components: {
      Navbar,
      Footer
    },
    data() {
      return {
        logo_src: "/image/logo.png",
        app_name: "Make Your Burger"
      }
    }
  }
</script>

<style>
  
</style>
