<template>
  <div id="descriptionAbout">
    <!-- Left align description -->
    <b-row class="descriptionRow">
      <b-col class="descriptionLeftColumn">
        <div>
          <h3 class="headerDescription">Experience</h3>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting.
          </p>
        </div>
      </b-col>
      <b-col><h1 class="numberColumn">01</h1></b-col>
    </b-row>

    <!-- Right align description -->
    <b-row class="descriptionRow">
      <b-col><h1 class="numberColumn">02</h1></b-col>
      <b-col class="descriptionRightColumn">
        <div>
          <h3 class="headerDescription">Innovation</h3>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting.
          </p>
        </div>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: "DescriptionAbout",
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
}
</style>
