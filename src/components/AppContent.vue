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
  <div class="container">
    <AppCard v-for="comic in comics" :comic="comic" />
    <button>
      <a href="#"><h2>LOAD MORE</h2></a>
    </button>
  </div>
</template>

<style lang="scss" scoped>
.container {
  height: 100%;
  margin-top: 4rem;

  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-wrap: wrap;
}

button {
  border: transparent;
  background-color: rgb(2, 130, 249);
  color: white;
  padding: 3px 15px;
  a {
    text-decoration: none;
    color: currentColor;
  }
}
</style>
