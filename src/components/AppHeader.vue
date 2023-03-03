<script>
export default {
  data() {
    return {
      navbarLinks: [
        {
          title: "CHARACTERS",
          link: "#",
        },
        {
          title: "COMICS",
          link: "#",
        },
        {
          title: "MOVIES",
          link: "#",
        },
        {
          title: "TV",
          link: "#",
        },
        {
          title: "GAMES",
          link: "#",
        },
        {
          title: "COLLECTIBLES",
          link: "#",
        },
        {
          title: "VIDEOS",
          link: "#",
        },
        {
          title: "FANS",
          link: "#",
        },
        {
          title: "NEWS",
          link: "#",
        },
        {
          title: "SHOP",
          link: "#",
        },
      ],
    };
  },
};
</script>

<template>
  <header>
    <div class="container">
      <div>
        <img src="../assets/dc-logo.png" alt="logo dc" />
      </div>
      <nav>
        <ul>
          <li v-for="link in navbarLinks" :key="link.title">
            <a :href="link.link">{{ link.title }}</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  height: 10vh;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  ul {
    list-style: none;

    display: flex;
    align-items: end;
    gap: 3rem;
    a {
      text-decoration: none;
      color: rgb(28, 28, 28);
    }
  }
}
</style>
