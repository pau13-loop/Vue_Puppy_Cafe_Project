<template>
  <div class="home">
    <b-container fluid>
      <!-- Header -->
      <b-row class="headerRow">
        <b-col class="headerColumn">
          <i class="fa-solid fa-paw iconHome"></i>
          <h3 class="headerTitle">Who we are</h3>
        </b-col>
        <b-col class="headerColumn">
          <p class="textHeader">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. It was popularised in the 1960s
            with the release of Letraset sheets containing Lorem Ipsum passages,
            and more recently with desktop publishing software like Aldus
            PageMaker including versions of Lorem Ipsum.
          </p>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {
    // @ is an alias to /src
    // HomeContent: () => import("@/components/home/HomeContent.vue"),
  },
};
</script>

<style>
/* HEADER */

.headerRow {
  height: 100vh;
  color: white;
  background-image: url("../assets/img/home/img-1.jpg");
}

.headerColumn {
  margin: auto;
}
.iconHome {
  font-size: 25px;
}

.headerTitle {
  font-size: 40px;
}

.textHeader {
  font-size: 15px;
}
</style>
