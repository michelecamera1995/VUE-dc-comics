<template>
  <div id="app">
    <HeaderSite />
    <MainSite />
    <FooterSite />
  </div>
</template>

<script>
import HeaderSite from "./components/HeaderSite.vue";
import MainSite from "./components/MainSite.vue";
import FooterSite from "./components/FooterSite.vue";

export default {
  name: "App",
  components: {
    HeaderSite,
    MainSite,
    FooterSite,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
