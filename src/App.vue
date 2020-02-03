<template>
  <div id="app">
    <Navbar />
    <!-- <HelloWorld msg="Welcome to Your V/ue.js App of Kevin Ngo" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Navbar from "./components/Navbar";
import Vue from "vue";
import VueRouter from "vue-router";

Vue.use(VueRouter);

export default {
  name: "app",
  components: {
    // HelloWorld,
    Navbar
  }
};
</script>

<style>
#app {
  font-family: "Helvetica, Avenir, Arial, sans-serif";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 1.2em;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
