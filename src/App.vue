<template>
  <div id="app">
    <Nav />
    <Jumbotron />
    <Info />
  </div>
</template>

<script>
import Nav from "./components/Nav.vue";
import Info from "./components/Info.vue";
import Jumbotron from "./components/Jumbotron.vue";

export default {
  name: "app",
  components: {
    Nav,
    Info,
    Jumbotron
  }
};
</script>

<style lang="css">
@import './assets/css/styles.css';
</style>
