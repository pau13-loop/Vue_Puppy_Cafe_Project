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
      <b-row>
        <b-col class="columnImgHome columnImgHomeLeft">
          <img
            src="../assets/img/home/img-2.jpg"
            alt="Pets cafe image"
            class="imageHome"
          />
        </b-col>
        <b-col class="columnTextImage">
          <div class="containerTextImageRight">
            <h3 class="headerTextImage textRight">
              We care for them as much as they care for us too
            </h3>
            <p class="paragraphTextImage">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry.
            </p>
          </div>
        </b-col>
      </b-row>

      <b-row class="left">
        <b-col class="columnTextImage">
          <div class="containerTextImageLeft">
            <h3 class="headerTextImage textLeft">
              Integrity is the foundation of good business, and we value it
              above all.
            </h3>
            <p class="paragraphTextImage">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry.
            </p>
          </div>
        </b-col>
        <b-col class="columnImgHome columnImgHomeRight">
          <img
            src="../assets/img/home/img-3.jpg"
            alt="Pets cafe image"
            class="imageHome"
          />
        </b-col>
      </b-row>

      <b-row>
        <b-col class="columnImgHome columnImgHomeLeft">
          <img
            src="../assets/img/home/img-6.jpg"
            alt="Pets cafe image"
            class="imageHome"
          />
        </b-col>
        <b-col class="columnTextImage">
          <div class="containerTextImageRight">
            <h3 class="headerTextImage textRight">
              How we transformed The Puppy Cafe into a modern space of
              confidence
            </h3>
            <p class="paragraphTextImage">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry.
            </p>
          </div>
        </b-col>
      </b-row>

      <b-row class="left">
        <b-col class="columnTextImage">
          <div class="containerTextImageLeft">
            <h3 class="headerTextImage textLeft">
              Confidence and trust always will make the best friendships between
              animal kingdom and human kind
            </h3>
            <p class="paragraphTextImage">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry.Lorem Ipsum is simply dummy text of the printing and
              typesetting industry. Lorem Ipsum is simply dummy text of the
              printing and typesetting industry.
            </p>
          </div>
        </b-col>
        <b-col class="columnImgHome columnImgHomeRight">
          <img
            src="../assets/img/home/img-5.jpg"
            alt="Pets cafe image"
            class="imageHome"
          />
        </b-col>
      </b-row>

      <!-- 
      <b-row>
        <b-col class="columnImgHome columnImgHomeLeft">
          <img
            src="../assets/img/home/img-4.jpg"
            alt="Pets cafe image"
            class="imageHome"
          />
        </b-col>
        <b-col class="containerTextImage">
          <h3 class="headerTextImage">
            How we transformed The Puppy Cafe into a modern space of confidence
          </h3>
          <p class="paragraphTextImage">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry.Lorem Ipsum is simply dummy text of the printing and
            typesetting industry. Lorem Ipsum is simply dummy text of the
            printing and typesetting industry.
          </p>
        </b-col>
      </b-row>

      <b-row>
        <b-col class="containerTextImage">
          <h3 class="headerTextImage">
            Confidence and trust is the bae of any relationship and us know how
            to build it to deliver the best friendships between animal kingdom
            and human kind
          </h3>
          <p class="paragraphTextImage">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry.Lorem Ipsum is simply dummy text of the printing and
            typesetting industry. Lorem Ipsum is simply dummy text of the
            printing and typesetting industry.
          </p>
        </b-col>
        <b-col class="columnImgHome columnImgHomeRight">
          <img
            src="../assets/img/home/img-5.jpg"
            alt="Pets cafe image"
            class="imagesHome"
          />
        </b-col>
      </b-row> -->
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
  margin-top: 135px;
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
  font-size: 50px;
}

/* IMAGES SECTION */

/* .left {
  float: left;
} */

.columnImgHome {
  max-height: 1000px;
  max-width: 50%;
  margin-top: 50px;
  margin-bottom: 50px;
  text-align: center;
}

/* .columnImgHomeLeft {
  padding-left: 100px;
} */

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
  font-size: 80px;
  font-style: italic;
  font-weight: bold;
}

.paragraphTextImage {
  font-style: italic;
}
</style>
