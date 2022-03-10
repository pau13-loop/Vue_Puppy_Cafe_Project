<template>
  <nav class="navBarContainer">
    <ul class="menu">
      <li>
        <router-link to="/" class="linkNavBar"><h3>Puppy Café</h3></router-link>
      </li>
      <div class="secondaryLinksNavBar">
        <li><router-link to="/about" class="linkNavBar">About</router-link></li>
      </div>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style>
.menu {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 10px 45px;
  padding: 0;
}

.menu li {
  display: inline;
}

.secondaryLinksNavBar {
  display: flex;
  gap: 45px;
}

.linkNavBar {
  color: #d3618d;
}

.linkNavBar:hover {
  color: rgb(194, 173, 194);
}
</style>
