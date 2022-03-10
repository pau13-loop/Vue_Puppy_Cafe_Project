<template>
  <div id="app">
    <div id="navBar">
      <NavBar />
    </div>

    <div id="content">
      <router-view />
    </div>

    <div id="footer">
      <Footer />
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {
    NavBar: () => import("@/components/layouts/NavBar.vue"),
    Footer: () => import("@/components/layouts/Footer.vue"),
  },
};
</script>

<style>
* {
  font-family: "Sora", sans-serif;
}

#app {
  min-height: 100vh;
  display: grid;
  grid-template-columns: auto;
  grid-template-rows: auto 1fr auto;
  grid-template-areas:
    "header"
    "main"
    "footer";
}

#navBar {
  grid-area: header;
  background-color: rgb(246, 225, 250);
  position: fixed;
  width: 100%;
  z-index: 1;
}

#content {
  grid-area: main;
}

#footer {
  grid-area: footer;
}
</style>
