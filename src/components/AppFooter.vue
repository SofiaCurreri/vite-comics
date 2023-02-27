<script></script>

<template>
  <footer>
    <section id="footer-top">
      <div class="container">
        <div class="flex-x">
          <div class="flex-y">
            <div class="flex-y">
              <h2>DC COMICS</h2>
              <a href="#">Characters</a>
              <a href="#">Comics</a>
              <a href="#">Movies</a>
              <a href="#">Tv</a>
              <a href="#">Games</a>
              <a href="#">Videos</a>
              <a href="#">News</a>
            </div>

            <div class="flex-y">
              <h2>SHOP</h2>
              <a href="#">Shop DC</a>
              <a href="#">Shop DC</a>
              <a href="#">Collectibles</a>
            </div>
          </div>
          <div class="flex-y">
            <h2>DC</h2>
            <a href="#"> Terms of Use</a>
            <a href="#">Privacy</a>
            <a href="#"> Policy</a>
            <a href="#"> Ad Choicess</a>
            <a href="#">Advertising</a>
            <a href="#">Jobs</a>
            <a href="#">Subscriptions</a>
            <a href="#">Talent Workshops</a>
            <a href="#">CPSC Certificates</a>
            <a href="#"> Ratings</a>
            <a href="#"> Contact Us</a>
          </div>
          <div class="flex-y">
            <h2>SITES</h2>
            <a href="#">DC</a>
            <a href="#"> MAD Magazine</a>
            <a href="#">DC Kids</a>
            <a href="#"> DC Universe</a>
            <a href="#"> DC Power Visa</a>
          </div>
        </div>
        <div>
          <img src="../../public/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </section>
    <section id="footer-bottom">
      <div class="container">
        <button>
          <a href="#"><h2>SIGN-UP NOW!</h2></a>
        </button>

        <div id="right-bottom-footer">
          <div><h2>FOLLOW US</h2></div>
          <div>
            <img src="../assets/footer-facebook.png" alt="" />
            <img src="../assets/footer-twitter.png" alt="" />
            <img src="../assets/footer-youtube.png" alt="" />
            <img src="../assets/footer-pinterest.png" alt="" />
            <img src="../assets/footer-periscope.png" alt="" />
          </div>
        </div>
      </div>
    </section>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  width: 100vw;
  a {
    text-decoration: none;
    color: currentColor;
  }
}

#footer-top {
  height: 55vh;
  width: 100%;
  background-image: url("../../public/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  a {
    color: rgb(121, 121, 121);
    line-height: 1.5rem;
  }
  h2 {
    color: white;
  }
}

.container {
  height: 100%;
  margin: 0 300px;

  display: flex;
  justify-content: space-between;
  align-items: center;
}
#footer-top .container {
  position: relative;
  img {
    width: 55rem;
    position: absolute;
    right: 0;
    top: -80px;
  }
}

.flex-y {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.flex-x {
  display: flex;
  align-items: start;
  gap: 4rem;
}

#footer-bottom {
  height: 10vh;
  width: 100%;
  background-color: rgb(48, 48, 48);
  position: absolute;
  z-index: 1;
}

button {
  border: 2px solid rgb(2, 130, 249);
  background-color: rgb(48, 48, 48);
  color: white;
  padding: 3px 15px;
}

#right-bottom-footer {
  color: rgb(2, 130, 249);

  display: flex;
  align-items: center;
  gap: 2rem;
  img {
    margin-left: 1rem;
  }
}
</style>
