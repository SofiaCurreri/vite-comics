<script>
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
import AppMenu from "./components/AppMenu.vue";
import AppFooter from "./components/AppFooter.vue";
import AppJumbotron from "./components/AppJumbotron.vue";

export default {
  components: {
    AppHeader,
    AppFooter,
    AppContent,
    AppMenu,
    AppJumbotron,
  },
};
</script>

<template>
  <AppHeader />

  <main>
    <section id="content">
      <AppJumbotron />
      <div class="container">
        <AppContent />
      </div>
    </section>

    <section id="menu">
      <div class="container">
        <AppMenu />
      </div>
    </section>
  </main>

  <AppFooter />
</template>

<style lang="scss" scoped>
main {
  margin-top: -20px;
}

#content {
  width: 100vw;
  height: 90vh;
  background-color: rgb(28, 28, 28);
}

#menu {
  width: 100vw;
  height: 15vh;
  background-color: rgb(2, 130, 249);
}

.container {
  height: 100%;
  margin: 0 300px;
  h1 {
    color: white;
  }
}

#menu .container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
