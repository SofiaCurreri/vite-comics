<script>
import menuData from "./_menuData.js";

export default {
  data() {
    return {
      menuData,
    };
  },
};
</script>

<template>
  <div class="container d-flex align-items-center justify-content-between">
    <div v-for="item in menuData">
      <img :src="item.url" />
      <h4>{{ item.title }}</h4>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  height: 100%;
}

img {
  width: 7rem;
}
h4 {
  margin-left: 1rem;
  color: white;
}
</style>
