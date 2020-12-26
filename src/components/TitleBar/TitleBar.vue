<template>
  <div class="constrain">
    <div class="imgPContainer">
      <p>Counted</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "TitleBar"
}
</script>

<style scoped>

  .constrain {
    margin:auto;
  }

  .imgPContainer{
    width: 90%;
    margin:auto;
  }

  .imgPContainer p {
    font-family: "Tangerine", Arial, Helvetica, sans-serif;
    font-weight: 900;
    color:white;
    font-size: 45px;
    margin-top: 0px;
    margin-bottom:25px;
    padding-top: 25px;
    text-align: left;
    padding-bottom:10px;
  }

  @media(orientation: landscape) and (min-width: 840px) {
    .articleContainer{
      width: 740px;
    }

    .constrain{
      width: 740px;
    }

    .imgContainer{
      width:600px;
    }
  }


</style>
