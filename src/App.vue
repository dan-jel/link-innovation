<template>
  <div id="app">
    <Nav />
    <router-view />
    <Footer />
  </div>
</template>
<style>
@import "./styles/bootstrap.min.css";
</style>
<style>
@import "./styles/owl.carousel.min.css";
</style>
<style>
@import "./styles/owl.theme.default.min.css";
</style>
<style>
@import "./styles/style.css";
</style>
<style>
@import "./styles/open-iconic-bootstrap.min.css";
</style>
<style>
@import "./styles/icomoon.css";
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
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    Nav,
    Footer,
  },
};
</script>
