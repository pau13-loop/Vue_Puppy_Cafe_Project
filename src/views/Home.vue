<template>
  <div class="home">
    <b-container fluid>
      <!-- Header -->
      <b-row cols="1" cols-lg="2" class="headerRow">
        <b-col class="headerColumn headerColumnTitle">
          <h3 class="headerTitle">Who we are</h3>
        </b-col>
        <b-col lg="7" class="headerColumn">
          <p class="textHeader">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley.
          </p>
        </b-col>
      </b-row>

      <!-- SECTIONS and IMAGES -->

      <!-- IMG 1 -->
      <HomeRowPets
        v-bind:isLeft="true"
        imagePath="img-2.webp"
        headerText="We care for them as much as they care for us too"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry."
      />

      <!-- IMG 2 -->
      <HomeRowPets
        v-bind:isLeft="false"
        imagePath="img-3.webp"
        headerText="Integrity is the base of good business"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry."
      />

      <!-- IMG 3 -->
      <HomeRowPets
        v-bind:isLeft="true"
        imagePath="img-6.webp"
        headerText="How we transformed The Puppy Cafe into a modern space"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry."
      />

      <!-- IMG 4 -->
      <HomeRowPets
        v-bind:isLeft="false"
        imagePath="img-5.webp"
        headerText="Confidence and trust always will make the best friendships"
        contextText="Lorem Ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum is simply dummy text of the printing and typesetting industry."
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
  background-image: url("../assets/img/home/img-1.webp");
}

.headerColumn {
  margin-top: 150px;
}

.headerColumnTitle {
  max-width: 35%;
  padding-left: 50px;
}

.headerTitle {
  font-size: 20px;
  font-weight: 800;
}

.textHeader {
  width: 85%;
  font-size: 35px;
  font-weight: 100;
}

@media only screen and (max-width: 768px) {
  .headerRow {
    justify-content: center;
  }

  .textHeader {
    width: 100%;
    text-align: center;
  }

  .rowImagesHome {
    justify-content: center;
  }

  .containerTextImageRight {
    padding: 0 !important;
    text-align: center;
    margin-top: 50px;
  }

  .containerTextImageLeft {
    padding: 0 !important;
    text-align: center !important;
    margin-top: 50px;
  }
}
</style>
