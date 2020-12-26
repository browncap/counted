<template>
  <div class="constrain">

    <div class="sectionTitle">
      <p>The counted . . .</p>
    </div>

    <ul>
      <li v-for="person in counted" :key="person">
        {{ person }}
      </li>
    </ul>
  </div>

</template>

<script>
export default {
  name: "Counted",
  data: function () {
    return {
      counted: [
        "Brayla Stone",
        "Neulisa Luciano Ruiz",
        "Dustin Parker",
        "Monika Diamond",
        "Lexi",
        "Nina Pop",
        "Tony McDade",
        "Dominique “Rem'mie” Fells",
        "Serena Angelique Velázquez Ramos",
        "Layla Pelaez Sánchez",
        "Riah Milton",
        "Brian “Egypt“ Powers",
        "Summer Taylor",
        "Scott / Scottlynn Devore",
        "Shaki Peters",
        "Bree Black",
        "Marilyn Cazares",
        "Dior H Ova",
        "Helle Jae O’Regan",
        "Queasha D Hardy",
        "Aja Raquell Rhone-Spears",
        "Lea Rayshon Daye",
        "Aerrion Burnett",
        "Yampi Méndez Arocho",
        "Mia Green",
        "Felycya Harris",
        "Brooklyn Deshuna",
        "Angel Unique",
        "Skylar Heath",
        "Sara Blackwood",
        "Asia Jynae Foster",
        "Chae’Meshia Simms",
        "Selena Reyes-Hernandez",
        "Michelle Michellyn Ramos Vargas",
        "Kee Sam",
        "Yunieski Carey Herrera",
        "Johanna Metzger",
        "Jayne Thompson",
        "Penélope Díaz Ramírez",
        "Merci Mack",
        "Kimberly Fial"
      ]
    }
  }
}
</script>

<style scoped>

  ul {
    list-style-type: none;
    padding: 0px;
    margin: auto;
  }

  li  {
    font-family: "Lato", Arial, Helvetica, sans-serif;
    font-size: 17px;
    color: white;
    font-weight: 500;
    margin-top: 5px;
  }

  .headerParagraph p {
    color: white;
  }

  @media(min-width: 540px) {
    li  {
      font-size: 18px;
    }
  }

</style>
