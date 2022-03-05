<template>
  <div id="app">
    <div id="nav">
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
  display: flex;
  flex-direction: column;
  height: 100vh;
}

#content {
  flex: 1 0 auto;
}

#footer {
  flex-shrink: 0;
}
</style>
