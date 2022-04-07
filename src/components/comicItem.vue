<template>
  <div class="card">
    <img :src="pathImg" />
    <h2>{{ series }}</h2>
    <p>{{ price }}</p>
    <p>{{ type }}</p>
  </div>
</template>

<script>
export default {
  name: "comicItem",
  props: {
    product: Object,
    pathImg: String,
    series: String,
    price: String,
    type: String,
  },
};
</script>

<style lang="scss" scoped>
.card {
  text-align: center;
  background-color: transparent;
  color: rgb(255, 255, 255);
  width: calc(100% / 6);
  padding: 1rem;
  h2 {
    font-size: 1.1rem;
  }
  img {
    width: 100%;
  }
}
</style>
