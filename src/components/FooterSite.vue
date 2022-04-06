<template>
  <div id="Footer">
    <div class="Footer">
      <!--TOP FOOTER-->

      <div id="TopFooter">
        <div class="smallcard">
          <img
            class="imgcard"
            src="../assets/buy-comics-digital-comics.png"
            alt="buy-comics-digital-comics"
          />
          <h4>DIGITAL COMICS</h4>
        </div>
        <div class="smallcard">
          <img
            class="imgcard"
            src="../assets/buy-comics-merchandise.png"
            alt="buy-comics-merchandise"
          />
          <h4>COMICS MERCHANDISE</h4>
        </div>
        <div class="smallcard">
          <img
            class="imgcard"
            src="../assets/buy-comics-shop-locator.png"
            alt="buy-comics-shop-locator"
          />
          <h4>COMICS SHOP LOCATOR</h4>
        </div>
        <div class="smallcard">
          <img
            class="imgcard"
            src="../assets/buy-comics-subscriptions.png"
            alt="buy-comics-subscriptions"
          />
          <h4>COMICS SUBSCRIPTIONS</h4>
        </div>
        <div class="smallcard">
          <img
            class="imgcard"
            src="../assets/buy-dc-power-visa.svg"
            alt="buy-dc-power-visa"
          />
          <h4>COMICS POWER VISA</h4>
        </div>
      </div>

      <!--MID FOOTER-->

      <div id="MidFooter">
        <div id="sitemap">
          <div class="flex">
            <div class="col">
              <div>
                <ul>
                  <li><h3>DC COMICS</h3></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Comics</a></li>
                  <li><a href="#">Movies</a></li>
                  <li><a href="#">TV</a></li>
                  <li><a href="#">Games</a></li>
                  <li><a href="#">Videos</a></li>
                  <li><a href="#">News</a></li>
                </ul>
                <ul class="m-tp">
                  <li><h3>SHOP</h3></li>
                  <li><a href="#">Shop DC</a></li>
                  <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
              </div>
              <div class="collist">
                <ul>
                  <li><h3>DC</h3></li>
                  <li><a href="#">Terms Of Use</a></li>
                  <li><a href="#">Privacy Policy</a></li>
                  <li><a href="#">Ad Choices</a></li>
                  <li><a href="#">Advertising</a></li>
                  <li><a href="#">Jobs</a></li>
                  <li><a href="#">Subscriptions</a></li>
                  <li><a href="#">Talent Workshops</a></li>
                  <li><a href="#">CPSC Certificates</a></li>
                  <li><a href="#">Ratings</a></li>
                  <li><a href="#">Shop Help</a></li>
                  <li><a href="#">Contact Us</a></li>
                </ul>
                <ul>
                  <li><h3>SITES</h3></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Comics</a></li>
                  <li><a href="#">Movies</a></li>
                  <li><a href="#">TV</a></li>
                  <li><a href="#">Games</a></li>
                  <li><a href="#">Videos</a></li>
                  <li><a href="#">News</a></li>
                </ul>
              </div>
            </div>
            <div id="dclogo">
              <img src="../assets/dc-logo-bg.png" alt="dc-logo-bg" />
            </div>
          </div>
        </div>
      </div>

      <!--BOTTOM FOOTER-->

      <div id="BottomFooter">
        <div id="bottombar">
          <div class="flex adjust">
            <a class="button" href="#">SIGN UP NOW!</a>
            <div class="socialbottom">
              <a class="follow" href="#">FOLLOW US!</a>
              <a href="#"
                ><img src="../assets/footer-facebook.png" alt="facebook"
              /></a>
              <a href="#"
                ><img src="../assets/footer-periscope.png" alt="periscope"
              /></a>
              <a href="#"
                ><img src="../assets/footer-pinterest.png" alt="pinterest"
              /></a>
              <a href="#"
                ><img src="../assets/footer-twitter.png" alt="twitter"
              /></a>
              <a href="#"
                ><img src="../assets/footer-youtube.png" alt="youtube"
              /></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterSite",
};
</script>

<style scoped lang="scss">
#TopFooter {
  z-index: 100;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgb(48, 131, 255);
  font-size: 0.8rem;
  color: white;
}
.smallcard {
  display: flex;
  align-items: center;
}
.imgcard {
  height: 40px;
  margin: 15%;
}
#MidFooter {
  font-weight: bold;
  background-image: url("../assets/footer-bg.jpg");
  display: flex;
  color: lightgray;
  #sitemap {
    margin: 0px auto;
    width: 1200px;
    .col {
      color: white;
      display: flex;
      margin-top: 5%;
      margin-bottom: 5%;
      .m-tp {
        margin-top: 15px;
      }
      .collist {
        margin-left: 15px;
        display: flex;
        ul {
          margin-right: 15px;
        }
      }
    }
  }
  #dclogo {
    img {
      width: 50%;
      height: 50%;
    }
  }
}
#BottomFooter {
  display: flex;
  background-color: #303030;
  height: 111px;
  #bottombar {
    width: 1200px;
    margin: 0 auto;
    .button {
      margin-top: 35px;
      border: 2px solid blue;
      padding: 15px;
      font-size: 1rem;
      color: white;
      background-color: transparent;
    }
    .socialbottom {
      margin-top: 35px;
      display: flex;
      text-align: center;
      .follow {
        color: blue;
        font-size: 1.3rem;
        margin-top: 10px;
      }
      a {
        margin-left: 20px;
      }
    }
  }
}
</style>
