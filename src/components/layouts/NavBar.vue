<template>
  <!-- <div>
    <b-navbar variant="secondary">
      <b-navbar-brand>
        <router-link to="/" style="color: #fcebf1"
          ><h2>Puppy Café</h2></router-link
        ></b-navbar-brand
      >
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item>
            <router-link to="/blog" style="color: white">Blog</router-link>
          </b-nav-item>
          <b-nav-item>
            <router-link to="/services" style="color: white"
              >Services</router-link
            >
          </b-nav-item>
          <b-nav-item>
            <router-link to="/about" style="color: white">About</router-link>
          </b-nav-item>
        </b-navbar-nav>

        <b-navbar-nav class="ml-auto">
          <b-nav-item-dropdown text="Lang" right toggle-class="text-light">
            <b-dropdown-item href="#" class="selectable-link"
              >EN</b-dropdown-item
            >
            <b-dropdown-item href="#" class="selectable-link"
              >ES</b-dropdown-item
            >
            <b-dropdown-item href="#" class="selectable-link"
              >RU</b-dropdown-item
            >
            <b-dropdown-item href="#" class="selectable-link"
              >FA</b-dropdown-item
            >
          </b-nav-item-dropdown>

          <b-nav-item-dropdown right toggle-class="text-light">
            <template #button-content>
              <em>User</em>
            </template>
            <b-dropdown-item href="#" class="selectable-link"
              >Profile</b-dropdown-item
            >
            <b-dropdown-item href="#" class="selectable-link"
              >Sign Out</b-dropdown-item
            >
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div> -->

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
  background-color: white;
}

.menu li {
  display: inline;
}

.secondaryLinksNavBar {
  display: flex;
  gap: 45px;
}

.linkNavBar {
  color: #e6a7bf;
}

/* .router-link-exact-active {
  color: pink !important;
}

nav li:hover,
nav li.router-link-active,
nav li.router-link-exact-active {
  cursor: pointer;
} */
</style>
