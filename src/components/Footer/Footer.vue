<template>
  <footer id="footer">
    <a href="https://www.elle.com/culture/career-politics/a32839834/black-trans-lgbtq-organizations/"><p>Donate</p></a>
    <span>|</span>
    <p>© Copyright 2020</p>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
  #footer {
    height: 100px;
    color: white;
    text-align: center;
    margin-top: 20px;
    width: 100%;
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  #footer span {
    padding-left: 5px;
    padding-right: 5px;
    color: white;
    font-size:20px;
  }

  #footer p {
    font-family: "Lato", Arial, Helvetica, sans-serif;
    padding-left: 5px;
    padding-right: 5px;
    color: white;
  }

  #footer a {
    color: white;
    text-decoration: none;
  }

  #footer a:visited {
    text-decoration: none;
  }
</style>
