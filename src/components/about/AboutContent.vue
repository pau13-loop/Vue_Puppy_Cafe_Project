<template>
  <div class="aboutcontent">
    <b-container fluid>
      <!-- Header -->

      <b-row>
        <b-col>
          <div class="headerContainer">
            <h1 class="headerAbout">
              Puppy Cafe is a private space to enjoy by cuddiling your fauvorite
              pets. Take a break and deep breath, welcome to Puppy Cafe.
            </h1>
          </div>
        </b-col>
      </b-row>

      <!-- Image -->

      <b-row>
        <b-col class="columnImg">
          <div class="imgOne">
            <img
              class="imgOne"
              alt="Image puppy cafe"
              src="../../assets/img/about/img-4.jpg"
            />
          </div>
        </b-col>
      </b-row>

      <!-- Slogan -->

      <b-row class="sloganRow">
        <b-col>
          <h1 class="slogan">
            <strong>Tranquility +</strong><br />
            harmony
          </h1>
        </b-col>
        <b-col>
          <div class="sloganParagraphContainer">
            <p class="sloganFirstParagraph">
              This is a space create to enjoy with your favourite people and
              your most loved ones. Don't worry about anything just take a break
              from the outside world and get this beloved disconnection.
            </p>

            <p class="sloganSecondParagraph">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into
              electronic typesetting, remaining essentially unchanged.
            </p>
          </div>
        </b-col>
      </b-row>

      <!-- Description 01 -->
      <b-row class="descriptionRow">
        <b-col class="descriptionLeftColumn">
          <div>
            <h3 class="headerDescription">Experience</h3>
            <p>
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into
              electronic typesetting.
            </p>
          </div>
        </b-col>
        <b-col><h1 class="numberColumn">01</h1></b-col>
      </b-row>

      <!-- Description 02 -->
      <b-row class="descriptionRow">
        <b-col><h1 class="numberColumn">02</h1></b-col>
        <b-col class="descriptionRightColumn">
          <div>
            <h3 class="headerDescription">Innovation</h3>
            <p>
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into
              electronic typesetting.
            </p>
          </div>
        </b-col>
      </b-row>

      <!-- Description 03 -->
      <b-row class="descriptionRow">
        <b-col class="descriptionLeftColumn">
          <div>
            <h3 class="headerDescription">Motivation</h3>
            <p>
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into
              electronic typesetting.
            </p>
          </div>
        </b-col>
        <b-col><h1 class="numberColumn">03</h1></b-col>
      </b-row>

      <!-- Description 04 -->
      <b-row class="descriptionRow">
        <b-col><h1 class="numberColumn">04</h1></b-col>
        <b-col class="descriptionRightColumn">
          <div>
            <h3 class="headerDescription">Passion</h3>
            <p>
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy text
              ever since the 1500s, when an unknown printer took a galley of
              type and scrambled it to make a type specimen book. It has
              survived not only five centuries, but also the leap into
              electronic typesetting.
            </p>
          </div>
        </b-col>
      </b-row>

      <!-- Image -->

      <b-row>
        <b-col class="columnImg">
          <div class="imgOne">
            <img
              class="imgOne"
              alt="Image puppy cafe"
              src="../../assets/img/about/img-5.jpg"
            />
          </div>
        </b-col>
      </b-row>

      <!-- Contact us -->
      <b-row class="contactUsRow">
        <b-col>
          <div class="first scaledParagraph">
            <p>If you are wondering who we are,</p>
          </div>
          <div class="second scaledParagraph">
            <p>and which activities we do,</p>
          </div>
          <div class="third scaledParagraph">
            <p>and maybe you fancy know a bit more</p>
          </div>
          <div class="forth scaledParagraph">
            <p><strong>about us</strong></p>
          </div>
        </b-col>
        <b-col class="contactUsColumn">
          <h1>Contact us <i class="fa-solid fa-arrow-right"></i></h1>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "AboutContent",
};
</script>

<style>
/* Header Block */
.headerContainer {
  float: right;
  width: 60%;
  margin: 80px;
}

.headerAbout {
  line-height: 75px;
  font-size: 60px;
}

/* Image Block */
.columnImg {
  padding: 0;
}

.imgOne {
  width: 100%;
  height: auto;
}

/* Slogan Block */
.sloganRow {
  margin-top: 70px;
  height: 260px;
}

.slogan {
  font-style: italic;
  font-size: 65px;
  padding-left: 50px;
}

.sloganParagraphContainer {
  width: 90%;
}

.sloganFirstParagraph {
  font-weight: bold;
}

.sloganSecondParagraph {
  margin-top: 45px;
}

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

/* Contact us */

.contactUsRow {
  margin-top: 150px;
  margin-bottom: 150px;
}

.scaledParagraph {
  margin: 30px;
  font-size: 25px;
}

.first {
  text-align: start;
}

.second {
  text-align: center;
}

.third {
  text-align: end;
}

.forth {
  text-align: center;
  margin-right: 160px;
}

.contactUsColumn {
  max-width: 40%;
  margin: auto;
  text-align: center;
}
</style>
