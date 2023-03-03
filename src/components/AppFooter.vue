<script></script>

<template>
  <footer>
    <section id="footer-top">
      <div class="container">
        <div class="flex-x">
          <div class="flex-y">
            <div class="flex-y">
              <h2>DC COMICS</h2>
              <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
              </ul>
            </div>

            <div class="flex-y">
              <h2>SHOP</h2>
              <ul>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Collectibles</a></li>
              </ul>
            </div>
          </div>
          <div class="flex-y">
            <h2>DC</h2>
            <ul>
              <li><a href="#"> Terms of Use</a></li>
              <li><a href="#">Privacy</a></li>
              <li><a href="#"> Policy</a></li>
              <li><a href="#"> Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#"> Ratings</a></li>
              <li><a href="#"> Contact Us</a></li>
            </ul>
          </div>
          <div class="flex-y">
            <h2>SITES</h2>
            <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#"> MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#"> DC Universe</a></li>
              <li><a href="#"> DC Power Visa</a></li>
            </ul>
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
          <a href="#"><h3 class="px-4 py-2">SIGN-UP NOW!</h3></a>
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

  ul {
    list-style: none;
    padding-left: 0;
    margin-top: 0;
  }
}

.container {
  height: 100%;

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
    top: -5rem;
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
  width: 100vw;
  background-color: rgb(48, 48, 48);
  position: absolute;
  z-index: 1;
}

button {
  border: 2px solid rgb(2, 130, 249);
  background-color: rgb(48, 48, 48);
  color: white;
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
