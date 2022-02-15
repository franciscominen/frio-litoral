<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from "./views/Home.vue";
export default {
  name: "App",
  components: { Home },
};
</script>

<style lang='scss'>
@import "./scss/main.scss";
@import "./scss/variables.scss";
</style>
