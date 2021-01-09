<template>
  <div class="constrain">

    <div class="imgContainer">
      <img :src="getImgUrl('looking.png')">
    </div>

    <div class="headerParagraph">
      <p>At least 44 transgender and gender non-conforming people were killed in the United States in 2020. Most of the victims were young Black and Latinx transgender women.</p>
    </div>

    <div class="secondaryParagraph">
      <p>Since 2015, the annual number of trans and gender non-conforming homicides has more than doubled.</p>
    </div>

    <div class="imgContainer">
      <img :src="getImgUrl('annualtranshomicides.png')">
    </div>

  </div>
</template>

<script>
export default {
  name: "Introduction",
  methods: {
    getImgUrl: function(path) {
      return require("@/assets/images/" + path);
    }
  }
}
</script>

<style scoped>

  .headerParagraph p {
    margin: 22px 0px;
  }

  .secondaryParagraph p {
    margin: 17px 0px;
  }

  .imgContainer ~ .imgContainer {
    width: 70%;
  }

  @media(min-width: 540px) {

    .imgContainer{
      width: 70%;
    }

    .imgContainer ~ .imgContainer {
      width: 55%;
    }
  }

</style>
