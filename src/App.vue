<template>
  <main-header />

  <image-cover src="https://i.redd.it/e2aiwmfjv0g51.png"> </image-cover>
  <h3
    class="-mt-8 relative text-white font-bold justify-center flex text-lg tracking-wide font-semibold text-neutral-200"
  >
    Pokemon GO
  </h3>
  <div class="bg-[#0B0418]">
    <p class="text-neutral-400 text-sm font-bold flex justify-center py-3">
      Conteúdo do jogo grátis com o Prime
    </p>
  </div>

  <div
    class="overflow-auto w-full pb-5 px-3 bg-[#0B0418] flex xl:justify-center"
  >
    <div class="flex w-32 gap-1 xl:justify-center">
      <img
        class="rounded-lg"
        src="https://cdn.oneesports.gg/cdn-data/2022/09/LeagueofLegends_Worlds2022_Logo_Poster.jpg"
        alt=""
      />
      <img
        class="rounded-lg"
        src="https://assets.pokemon.com/assets//cms2-pt-br/img/watch-pokemon-tv/_tiles/broadcaster/season23-cartoon-network-169.png"
        alt=""
      />
      <img
        class="rounded-lg"
        src="https://cdn.cloudflare.steamstatic.com/steam/apps/1172470/capsule_616x353.jpg?t=1664321959"
        alt=""
      />
      <img
        class="rounded-lg"
        src="https://cdn.akamai.steamstatic.com/steam/apps/730/capsule_616x353.jpg?t=1641233427"
        alt=""
      />
      <img
        class="rounded-lg"
        src="https://meups.com.br/wp-content/uploads/2020/01/Rainbow-Six-Siege-1.jpg"
        alt=""
      />
      <img
        class="rounded-lg"
        src="https://cdn1.epicgames.com/salesEvent/salesEvent/EGS_LeagueofLegends_RiotGames_S1_2560x1440-ee500721c06da3ec1e5535a88588c77f"
        alt=""
      />
    </div>
  </div>

  <div class="bg-[#0B0418] cursor-pointer">
    <ul class="flex text-xs justify-center items-center gap-6 pt-3 text-white">
      <li class="bg-neutral-600 py-2 px-3 rounded-2xl">Todos</li>
      <li class="hover:bg-neutral-800 py-2 px-3 rounded-2xl">
        Conteúdo no jogo
      </li>
      <li class="hover:bg-neutral-800 py-2 px-3 rounded-2xl">Jogos</li>
    </ul>
  </div>
</template>

<script lang="ts" setup>
import MainHeader from "./components/MainHeader.vue";
import ImageCover from "./components/ImageCover.vue";
</script>
