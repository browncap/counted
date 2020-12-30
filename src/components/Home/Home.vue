<template>
  <div>
    <Introduction />
    <div class="separator"></div>
    <Demographics />
    <div class="separator"></div>
    <Risk />
    <div class="separator"></div>
    <Apathy />
    <div class="separator"></div>
    <Counted />
  </div>
</template>

<script>
import Introduction from './components/Introduction.vue'
import Demographics from './components/Demographics.vue'
import Risk from './components/Risk.vue'
import Apathy from './components/Apathy.vue'
import Counted from './components/Counted.vue'

export default {
  name: 'Home',
  components: {
    Introduction,
    Demographics,
    Risk,
    Apathy,
    Counted
  }
}
</script>

<style>
  .headerParagraph {
    width: 75%;
    margin: auto;
    padding: 0px;
  }

  .headerParagraph p {
    font-family: "Slabo", Arial, Helvetica, sans-serif;
    font-size: 22px;
    color: #FB9FFF;
    font-weight: 500;
    margin: 0px;
  }

  .secondaryParagraph {
    width: 70%;
    margin: auto;
    padding: 0px;
  }

  .secondaryParagraph p {
    font-family: "Lato", Arial, Helvetica, sans-serif;
    font-size: 17px;
    color: white;
  }

  .imgContainer{
    width: 100%;
    margin: auto;
    overflow: hidden;
  }

  .separator {
    width: 85%;
    height: 2px;
    background-color: #333;
    margin: 55px auto;
  }

  .sectionTitle {
    width: 80%;
    margin: auto;
    padding: 0px 0px 50px 0px;
  }

  .sectionTitle p {
    font-family: "Slabo", Arial, Helvetica, sans-serif;
    font-size: 25px;
    color: #8AE9FF;
    margin: 0px;
    text-align: left;
  }

  .constrain {
    margin:auto;
  }

  @media(min-width: 540px) {
    .headerParagraph {
      padding-top: 10px;
      width: 65%;
    }

    .secondaryParagraph {
      width: 60%;
      margin-bottom: 30px;
    }

    .headerParagraph p {
      font-size: 24px;
    }

    .secondaryParagraph p {
      font-size: 18px;
    }

    .constrain{
      width: 100%;
      max-width: 740px;
    }

    .separator {
      width: 90%;
      max-width: 540px;
      height: 2px;
      background-color: #333;
      margin: 85px auto;
    }

    .sectionTitle {
      padding-bottom: 40px;
    }
  }
</style>
