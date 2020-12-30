<template>
  <div class="constrain">

    <div class="sectionTitle">
      <p>The demographics . . .</p>
    </div>

    <div class="headerParagraph">
      <p>Of the 41 victims in 2020, 33 were people of color...</p>
    </div>

    <div class="imgContainer">
      <img :src="getImgUrl('demographicbreakdown.png')">
    </div>

    <div class="headerParagraph">
      <p>30 were trans women of color...</p>
    </div>

    <div class="imgContainer">
      <img :src="getImgUrl('transwomenofcolor.png')">
    </div>

    <div class="headerParagraph">
      <p>and 22 were Black trans women.</p>
    </div>

    <div class="imgContainer">
      <img :src="getImgUrl('blacktranswomen.png')">
    </div>

  </div>
</template>

<script>
export default {
  name: "Demographics",
  methods: {
    getImgUrl: function(path) {
      return require("@/assets/" + path);
    }
  }
}
</script>

<style scoped>

  .headerParagraph p {
    margin: 0px 0px 40px 0px;
  }

  .headerParagraph ~ .headerParagraph {
    padding-top: 40px;
    width: 70%;
  }

  .imgContainer {
    width: 68%;
  }

  @media(min-width: 540px) {
    .imgContainer{
      width:50%;
    }
  }

</style>
