<template>
  <div id="app">
    <div id="nav">
      <NavBar />
    </div>
    <router-view />
    <!-- <div id="footer">
      <Footer />
    </div> -->
  </div>
</template>

<script>
export default {
  name: "App",
  components: {
    NavBar: () => import("@/components/layouts/NavBar.vue"),
    // Footer: () => import("@/components/layouts/Footer.vue"),
  },
};
</script>

<style>
#nav {
  display: block;
  position: sticky;
  top: 0;
  z-index: 1;
}

/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 15px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
