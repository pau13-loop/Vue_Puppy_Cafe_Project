<template>
  <!-- LEFT DESCRIPTION -->
  <b-row v-if="isLeft" class="descriptionRow">
    <b-col class="numberCol"
      ><h1 class="numberColumn">{{ numberSection }}</h1></b-col
    >
    <b-col class="descriptionRightColumn">
      <div>
        <h3 class="headerDescription">{{ headerSection }}</h3>
        <p class="contextSectionAbout">
          {{ contextSection }}
        </p>
      </div>
    </b-col>
  </b-row>

  <!-- RIGHT DESCRIPTION -->
  <b-row v-else class="descriptionRow">
    <b-col class="descriptionLeftColumn">
      <div>
        <h3 class="headerDescription">{{ headerSection }}</h3>
        <p class="contextSectionAbout">
          {{ contextSection }}
        </p>
      </div>
    </b-col>
    <b-col class="numberCol"
      ><h1 class="numberColumn">{{ numberSection }}</h1></b-col
    >
  </b-row>
</template>

<script>
export default {
  name: "AboutRowDescription",
  props: {
    isLeft: { required: true, type: Boolean },
    numberSection: { required: true, type: String },
    headerSection: { required: true, type: String },
    contextSection: { required: true, type: String },
  },
};
</script>

<style>
/* Description Block */

.descriptionRow {
  margin-top: 65px;
  margin-bottom: 65px;
}

.numberColumn {
  text-align: center;
  font-size: 120px;
  font-style: italic;
  font-weight: 400;
}

.descriptionLeftColumn {
  text-align: end;
  display: inline-block;
}

.descriptionRightColumn {
  text-align: start;
  display: inline-block;
}

.headerDescription {
  font-style: italic;
  font-weight: 700;
}

.contextSectionAbout {
  font-weight: 300;
}
</style>
