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
</style>
