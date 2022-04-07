<template>
  <div id="app">
    <HeaderSite />
    <MainSite :comics="comics" />
    <FooterSite />
  </div>
</template>

<script>
import HeaderSite from "./components/HeaderSite.vue";
import MainSite from "./components/MainSite.vue";
import FooterSite from "./components/FooterSite.vue";
// data
import comics from "@/assets/data/dc-comics";

export default {
  name: "App",
  data() {
    return {
      comics,
    };
  },
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
  color: #2c3e50;
}
* {
  box-sizing: border-box;
  margin: 0px;
  padding: 0px;
}
* li {
  list-style-type: none;
}
* a {
  text-decoration: none;
  color: lightgrey;
  font-size: 0.7rem;
  color: lightslategray;
}
* a:hover {
  text-decoration: none;
  color: lightgray;
}
* a:focus {
  text-decoration: none;
  color: lightgray;
}
* a:active {
  text-decoration: none;
  color: lightgray;
}
.flex {
  display: flex;
}
.adjust {
  justify-content: space-between;
  align-content: center;
  align-items: center;
}
.container {
  width: 1200px;
  margin: 0 auto;
}
</style>
