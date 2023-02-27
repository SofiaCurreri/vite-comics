<script>
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
import AppMenu from "./components/AppMenu.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeader,
    AppFooter,
    AppContent,
    AppMenu,
  },
};
</script>

<template>
  <AppHeader />

  <main>
    <section id="content">
      <AppContent />
    </section>

    <section id="menu">
      <AppMenu />
    </section>
  </main>

  <AppFooter />
</template>

<style lang="scss" scoped>
main {
  height: 80vh;
  margin-top: -20px;
}

#content {
  width: 100vw;
  height: 10vh;
  background-color: rgb(28, 28, 28);
}
</style>
