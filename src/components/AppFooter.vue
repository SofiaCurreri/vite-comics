<script></script>

<template>
  <footer>
    <section id="footer-top">
      <div class="container">
        <div class="flex-x">
          <div class="flex-y">
            <div>
              <h2>DC COMICS</h2>
              <p>Characters</p>
              <p>Comics</p>
              <p>Movies</p>
              <p>Tv</p>
              <p>Games</p>
              <p>Videos</p>
              <p>News</p>
            </div>

            <div>
              <h2>SHOP</h2>
              <p>Shop DC</p>
              <p>Shop DC Collectibles</p>
            </div>
          </div>
          <div>
            <h2>DC</h2>
            <p>Terms of Use</p>
            <p>Privacy Policy</p>
            <p>Ad Choicess</p>
            <p>Advertising</p>
            <p>Jobs</p>
            <p>Subscriptions</p>
            <p>Talent Workshops</p>
            <p>CPSC Certificates</p>
            <p>Ratings</p>
            <p>Contact Us</p>
          </div>
          <div>
            <h2>SITES</h2>
            <p>DC</p>
            <p>MAD Magazine</p>
            <p>DC Kids</p>
            <p>DC Universe</p>
            <p>DC Power Visa</p>
          </div>
        </div>
        <div>
          <img src="../../public/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </section>
    <section id="footer-bottom"></section>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  width: 100vw;
}

#footer-top {
  height: 55vh;
  width: 100%;
  background-image: url("../../public/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  p {
    color: rgb(121, 121, 121);
    line-height: 0.7rem;
  }
  h2 {
    color: white;
  }
}

.container {
  height: 100%;
  margin: 0 300px;
  padding-top: 150px;

  display: flex;
  justify-content: space-between;
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
}
</style>
