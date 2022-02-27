<template>
  <!-- IF TRUE -->
  <b-row v-if="positionRow" class="rowImagesHome">
    <b-col class="columnImgHome columnImgHomeLeft">
      <img
        :src="require(`@/assets/img/home/${imagePath}`)"
        alt="Pets cafe image"
        class="imageHome"
      />
    </b-col>
    <b-col class="columnTextImage">
      <div class="containerTextImageRight">
        <h3 class="headerTextImage textRight">
          {{ headerText }}
        </h3>
        <p class="paragraphTextImage">
          {{ contextText }}
        </p>
      </div>
    </b-col>
  </b-row>

  <!-- ELSE -->
  <b-row v-else class="left rowImagesHome">
    <b-col class="columnTextImage">
      <div class="containerTextImageLeft">
        <h3 class="headerTextImage textLeft">
          {{ headerText }}
        </h3>
        <p class="paragraphTextImage">
          {{ contextText }}
        </p>
      </div>
    </b-col>
    <b-col class="columnImgHome columnImgHomeRight">
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
