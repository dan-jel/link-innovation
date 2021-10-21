<template>
  <div id="app">
    <div id="nav">
      <Nav />
    </div>

    <router-view />
  </div>
</template>
<style>
@import "./styles/bootstrap.min.css";
</style>

<style>
@import "./styles/owl.theme.default.min.css";
</style>
<style>
@import "./styles/style.css";
</style>
<style lang="css">
* {
  margin: 0;
}

#app {
  font-family: "Work Sans", sans-serif;
  color: #2c3e50;
}
</style>

<script>
import Nav from "@/components/Nav.vue";

export default {
  name: "App",
  components: {
    Nav,
  },
};
</script>
