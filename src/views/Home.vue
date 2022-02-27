<template>
  <div class="home">
    <b-container fluid>
      <!-- Header -->
      <b-row class="headerRow">
        <b-col class="headerColumn headerColumnTitle">
          <!-- <i class="fa-solid fa-paw iconHome"></i> -->
          <h3 class="headerTitle">Who we are</h3>
        </b-col>
        <b-col class="headerColumn">
          <p class="textHeader">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged.
          </p>
        </b-col>
      </b-row>

      <!-- SECTIONS and IMAGES -->

      <!-- IMG 1 -->
      <HomeRowPets
        v-bind:isLeft="true"
        imagePath="img-2.jpg"
        headerText="We care for them as much as they care for us too"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry."
      />

      <!-- IMG 2 -->
      <HomeRowPets
        v-bind:isLeft="false"
        imagePath="img-3.jpg"
        headerText="Integrity is the foundation of good business, and we value it
              above all"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry."
      />

      <!-- IMG 3 -->
      <HomeRowPets
        v-bind:isLeft="true"
        imagePath="img-6.jpg"
        headerText="How we transformed The Puppy Cafe into a modern space of
              confidence"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry."
      />

      <!-- IMG 4 -->
      <HomeRowPets
        v-bind:isLeft="false"
        imagePath="img-5.jpg"
        headerText="Confidence and trust always will make the best friendships"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry."
      />
    </b-container>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {
    HomeRowPets: () => import("@/components/HomeRowPets.vue"),
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
  margin-top: 50px;
}

.headerColumnTitle {
  max-width: 35%;
  padding-left: 50px;
}

.headerTitle {
  font-size: 40px;
}

.textHeader {
  width: 85%;
  font-size: 30px;
}
</style>
