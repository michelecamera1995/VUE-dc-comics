<template>
  <div id="header">
    <div class="header">
      <img src="../assets/dc-logo.png" alt="DC-Logo" />
      <nav>
        <ul>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">Tv</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Collectibles</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">Fans</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Shop</a></li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderSite",
};
</script>

<style scoped lang="scss">
#header {
  background-color: white;
  width: 100%;
  font-size: 0.8rem;
  font-weight: bold;
  color: lightslategray;

}
.header {
  padding-top: 1%;
  padding-bottom: 1%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0px auto;
  width:1200px;
}
img {
  height: 60px;
}
nav {
  ul {
    display: flex;
    li {
      margin: 20px;
    }
  }
}
</style>
