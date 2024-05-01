<template>
  <div id="app">
    <div class="navBar">
      <img src="./assets/logo.svg" />
      <navBar>
        <!-- <img alt="Vue logo" src="./assets/"> -->
      </navBar>
    </div>
    <div class="newbox">
      <newBox></newBox>
    </div>
    <div class="main">
      <img class="mainImg" src="./assets/image-web-3-desktop.jpg" />

      <mainPicture></mainPicture>
    </div>
    <div class="cardthree">
      <card> </card>
    </div>
  </div>
</template>

<script>
// import nav from "./components/nav.vue";
import navBar from "./components/nav.vue";
import newBox from "./components/newBox.vue";
import mainPicture from "./components/mainPicture.vue";
import card from "./components/card.vue";

export default {
  name: "App",
  components: {
    navBar,
    newBox,
    mainPicture,
    card,
  },
};
</script>

<style>
#app {
  display: grid;
  grid-template-columns: 75% 25%;
  grid-template-rows: 100px 400px 300px;
  /* margin-left: 100px;
  margin-top: 30px;
  margin-right: 100px; */
  padding: 60px;
}
.navBar {
  display: flex;
  justify-content: space-between;

  grid-column-start: 1;
  grid-column-end: 3;
}
.navBar img {
  width: 60px;
  height: 40px;
}

.newbox {
  display: flex;

  grid-column-start: 2;
  grid-row-start: 2;
  grid-row-end: 5;
}
.main {
  display: flex;
  flex-direction: column;
  justify-content: right;
  width: auto;
  grid-column-start: 1;
  grid-row-start: 2;
  grid-row-end: 5;
}
.mainImg {
  margin-right: 40px;
  grid-column-start: 1;
  grid-row-start: 2;
  grid-row-end: -2;
}
.cardthree {
  margin-top: 50px;
  margin-right: 10px;

  grid-column-start: 1;
  grid-column-end: 3;
  width: auto;
}
</style>
