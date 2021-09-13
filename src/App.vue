<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Main msg="Welcome to Your Vue.js App" />
    <Ajax></Ajax>
  </div>
</template>

<script>
import Main from "./components/Main.vue";
import Ajax from "./components/Ajax.vue";
export default {
  components: {
    Main,
    Ajax,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
