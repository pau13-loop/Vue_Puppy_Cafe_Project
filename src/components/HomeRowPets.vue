<template>
  <!-- IF TRUE -->
  <b-row v-if="isLeft" class="rowImagesHome">
    <b-col class="columnImgHome">
      <img
        :src="require(`@/assets/img/home/${imagePath}`)"
        alt="Pets cafe image"
        class="imageHome"
      />
    </b-col>
    <b-col class="columnTextImage">
      <div class="containerTextImageRight">
        <h3 class="headerTextImage">
          {{ headerText }}
        </h3>
        <p class="paragraphTextImage">
          {{ contextText }}
        </p>
      </div>
    </b-col>
  </b-row>

  <!-- ELSE -->
  <b-row v-else class="rowImagesHome">
    <b-col class="columnTextImage">
      <div class="containerTextImageLeft">
        <h3 class="headerTextImage">
          {{ headerText }}
        </h3>
        <p class="paragraphTextImage">
          {{ contextText }}
        </p>
      </div>
    </b-col>
    <b-col class="columnImgHome">
      <img
        :src="require(`@/assets/img/home/${imagePath}`)"
        alt="Pets cafe image"
        class="imageHome"
      />
    </b-col>
  </b-row>
</template>

<script>
export default {
  name: "HomeRowPets",
  props: {
    isLeft: { required: true, type: Boolean },
    imagePath: { required: true, type: String },
    headerText: { required: true, type: String },
    contextText: { required: true, type: String },
  },
};
</script>

<style>
/* IMAGES SECTION */

.rowImagesHome {
  column-gap: 35px;
  position: relative;
  /* animation: mymove 5s;
  animation-timing-function: ease-in; */
}

/* @keyframes mymove {
  from {
    left: -300px;
  }
  to {
    left: 0px;
  }
} */

.columnImgHome {
  max-height: 120vh;
  max-width: 100vh;
  margin-top: 50px;
  margin-bottom: 50px;
  text-align: center;
}

.imageHome {
  height: 100%;
  border-radius: 10px;
}

.columnTextImage {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.containerTextImageRight {
  padding-right: 20%;
}

.containerTextImageLeft {
  text-align: end;
  padding-left: 20%;
}

.headerTextImage {
  font-size: 70px;
  font-style: italic;
  font-weight: 400;
  line-height: 85px;
}

.paragraphTextImage {
  font-style: italic;
  font-weight: 200;
}
</style>
