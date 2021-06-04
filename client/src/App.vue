<template>
  <div id="app">
    <Navbar />
    <router-view />
    <Footer />
  </div>
</template>
<script>
  import Footer from "./components/Footer.vue";
  import Navbar from "./components/Navbar.vue";
  export default {
    name: "App",
    components: {
      Footer,
      Navbar,
    },
  };
</script>
<style>
  .action-box {
    color: inherit;
  }
  .action-box:hover {
    color: brown;
    cursor: pointer;
  }
</style>
