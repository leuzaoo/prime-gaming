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
      <img
        class="rounded-xl"
        src="https://cdn.oneesports.gg/cdn-data/2022/09/LeagueofLegends_Worlds2022_Logo_Poster.jpg"
        alt=""
      />
      <img
        class="rounded-xl"
        src="https://assets.pokemon.com/assets//cms2-pt-br/img/watch-pokemon-tv/_tiles/broadcaster/season23-cartoon-network-169.png"
        alt=""
      />
      <img
        class="rounded-xl"
        src="https://cdn.cloudflare.steamstatic.com/steam/apps/1172470/capsule_616x353.jpg?t=1664321959"
        alt=""
      />
      <img
        class="rounded-xl"
        src="https://cdn.akamai.steamstatic.com/steam/apps/730/capsule_616x353.jpg?t=1641233427"
        alt=""
      />
      <img
        class="rounded-xl"
        src="https://meups.com.br/wp-content/uploads/2020/01/Rainbow-Six-Siege-1.jpg"
        alt=""
      />
      <img
        class="rounded-xl"
        src="https://cdn1.epicgames.com/salesEvent/salesEvent/EGS_LeagueofLegends_RiotGames_S1_2560x1440-ee500721c06da3ec1e5535a88588c77f"
        alt=""
      />
    </div>
  </div>

  <div
    class="md:flex items-center bg-[#0B0418] text-white text-xs font-semibold gap-1 pl-5 pt-5 md:pl-10 pt-3 cursor-pointer"
  >
    <div class="flex items-center md:flex md:text-base md:font-normal gap-2">
      <p class="text-neutral-300 bg-[#3C3646] px-3 py-2 rounded-2xl">Todos</p>
      <p class="text-neutral-300 hover:bg-[#464449] px-3 py-2 rounded-2xl">
        Conteúdo no jogo
      </p>
      <p class="text-neutral-300 hover:bg-[#464449] px-3 py-2 rounded-2xl">
        Jogos
      </p>
    </div>

    <div class="bg-[#0B0418] flex items-center py-3 gap-3">
      <remix-icon icon="lupa" class="text-white cursor-pointer" />
      <input
        type="text"
        class="text-xs md:text-base md:font-normal pl-5 md:pl-7 w-[320px] h-[35px] md:h-[45px] rounded-full text-left border border-white text-white bg-[#0B0418]"
        placeholder="Pesquisar no Prime Gaming"
      />
    </div>
  </div>
</template>

<script lang="ts" setup>
import MainHeader from "./components/MainHeader.vue";
import ImageCover from "./components/ImageCover.vue";
import RemixIcon from "./components/RemixIcon.vue";
</script>
