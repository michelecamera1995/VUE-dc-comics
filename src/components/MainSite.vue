<template>
  <div id="Main">
    <div id="jumbo"></div>
    <div class="Main container">
      <div class="currentLabel"><h2>CURRENT SERIES</h2></div>
      <comicItem
        v-for="(item, index) in comics"
        :key="'prod-' + index"
        :series="item.series"
        :pathImg="item.thumb"
        :price="item.price"
        :type="item.type"
      />
    </div>
  </div>
</template>

<script>
import comicItem from "@/components/comicItem.vue";

export default {
  name: "MainSite",
  props: {
    comics: Array,
  },
  components: {
    comicItem,
  },
};
</script>

<style scoped lang="scss">
#Main {
  background-color: black;
  color: white;
}
.Main {
  display: flex;
  justify-content: center;
  flex-grow: 1;
  flex-wrap: wrap;
  padding-top: 5%;
  padding-bottom: 5%;
  position: relative;
}
.currentLabel {
  position: absolute;
  top: -3%;
  left: 5%;
  font-size: 1.3rem;
  z-index: 20;
  background-color: rgb(48, 131, 255);
  padding: 15px 15px;
}
#jumbo {
  background-image: url("@/assets/jumbotron.jpg");
  height: 350px;
  z-index: 5;
}
</style>
