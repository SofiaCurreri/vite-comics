<script>
import comics from "./_comicsData.js";
import AppCard from "./AppCard.vue";

export default {
  data() {
    return {
      comics,
    };
  },

  components: { AppCard },
};
</script>

<template>
  <div class="container d-flex flex-column align-items-center py-5">
    <label class="d-flex align-items-center justify-content-center">
      <h2>CURRENT SERIES</h2>
    </label>
    <div class="row row-cols-6 mt-5">
      <div class="col mb-5" v-for="comic in comics">
        <AppCard :comic="comic" />
      </div>
    </div>
    <button>
      <a href="#"><h4 class="fs-5 mt-1">LOAD MORE</h4></a>
    </button>
  </div>
</template>

<style lang="scss" scoped>
.container {
  position: relative;
}

button {
  width: 15%;
  border: transparent;
  background-color: rgb(2, 130, 249);
  color: white;
  padding: 4px 20px;
  a {
    text-decoration: none;
    color: currentColor;
  }
}

label {
  color: white;
  background-color: rgb(2, 130, 249);
  height: 4rem;
  width: 20rem;

  position: absolute;
  left: 0;
  top: -2rem;
}
</style>
