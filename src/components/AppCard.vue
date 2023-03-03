<script>
export default {
  props: {
    comic: Object,
  },
};
</script>

<template>
  <div>
    <a href="#">
      <div class="thumb">
        <img :src="comic.thumb" alt="" />
      </div>

      <p class="text-center text-uppercase mt-3">
        {{ comic.series }}
      </p>
    </a>
  </div>
</template>

<style lang="scss" scoped>
.thumb {
  width: 180px;
  height: 180px;
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center top;
  }
}

a {
  text-decoration: none;
  color: white;
}
</style>
