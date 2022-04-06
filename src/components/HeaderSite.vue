<template>
  <div id="header">
    <div class="header">
      <img src="../assets/dc-logo.png" alt="DC-Logo" />
      <nav>
        <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
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
