<template>
  <VueSlickCarousel v-bind="settings">
    <img
      src="https://cdn.oneesports.gg/cdn-data/2022/09/LeagueofLegends_Worlds2022_Logo_Poster.jpg"
    />
    <img
      src="https://cdn.akamai.steamstatic.com/steam/apps/730/capsule_616x353.jpg?t=1641233427"
    />
  </VueSlickCarousel>
</template>

<script lang="ts">
/* necessário colocar o "setup" após *  lang="ts"  * */
export default {
  data() {
    return {
      settings: {
        arrows: true,
        dots: true,
        accessibility: true,
      },
    };
  },
};
</script>
