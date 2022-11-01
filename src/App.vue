<template>
  <main-header />

  <image-cover src="https://wallpapercave.com/wp/wp11326349.jpg"> </image-cover>
  <h3
    class="md:hidden text-white font-bold text-3xl -mt-10 relative flex justify-center text-lg tracking-wide font-semibold text-neutral-200"
  >
    FIFA 2023
  </h3>
  <div class="bg-[#0B0418]">
    <p class="text-neutral-400 text-sm font-bold flex justify-center py-3">
      Conteúdo do jogo grátis com o Prime
    </p>
  </div>

  <div
    class="overflow-auto w-full pb-3 px-3 bg-[#0B0418] flex md:justify-center xl:justify-center"
  >
    <div
      class="flex w-28 md:w-24 xl:w-44 md:justify-center gap-1 xl:justify-center cursor-grab"
    >
      <games-banner
        class="rounded"
        src="https://cdn.oneesports.gg/cdn-data/2022/09/LeagueofLegends_Worlds2022_Logo_Poster.jpg"
      />
      <games-banner
        class="rounded"
        src="https://assets.pokemon.com/assets//cms2-pt-br/img/watch-pokemon-tv/_tiles/broadcaster/season23-cartoon-network-169.png"
      />
      <games-banner
        class="rounded"
        src="https://cdn.cloudflare.steamstatic.com/steam/apps/1172470/capsule_616x353.jpg?t=1664321959"
      />
      <games-banner
        class="rounded"
        src="https://cdn.akamai.steamstatic.com/steam/apps/730/capsule_616x353.jpg?t=1641233427"
      />
      <games-banner
        class="rounded"
        src="https://meups.com.br/wp-content/uploads/2020/01/Rainbow-Six-Siege-1.jpg"
      />
      <games-banner
        class="rounded"
        src="https://cdn1.epicgames.com/salesEvent/salesEvent/EGS_LeagueofLegends_RiotGames_S1_2560x1440-ee500721c06da3ec1e5535a88588c77f"
      />
    </div>
  </div>

  <games-finder />

  <games-info />

  <image-carousel />
</template>

<script lang="ts" setup>
import MainHeader from "./components/MainHeader.vue";
import ImageCover from "./components/ImageCover.vue";
import GamesBanner from "./components/GamesBanner.vue";
import GamesFinder from "./components/GamesFinder.vue";
import GamesInfo from "./components/GamesInfo.vue";
import ImageCarousel from "./components/ImageCarousel.vue";
</script>
