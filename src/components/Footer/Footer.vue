<template>
  <footer id="footer">
    <a href="https://www.translivesmatter.xyz"><p>Donate</p></a>
    <span>|</span>
    <p>© Copyright 2021</p>
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
    padding: 0px 5px;
    color: white;
    font-size:20px;
  }

  #footer p {
    font-family: "Lato", Arial, Helvetica, sans-serif;
    padding: 0px 5px;
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
