<template>
  <div
    class="flex items-center text-xs text-neutral-400 font-bold gap-3 bg-[#0B0418] pt-4 pl-8"
  >
    <p class="bg-[#3C3646] px-3 py-2 rounded-full">Todos</p>
    <p
      class="hover:bg-[#3C3646] hover:px-3 hover:py-2 hover:rounded-full hover:cursor-pointer"
    >
      Conteúdo no jogo
    </p>
    <p
      class="hover:bg-[#3C3646] hover:px-3 hover:py-2 hover:rounded-full hover:cursor-pointer"
    >
      Jogos
    </p>
  </div>

  <div class="bg-[#0B0418] pl-8 pt-3 pb-2 flex items-center">
    <input
      class="rounded-full border pl-14 border-white bg-[#0B0418] text-xs h-9 w-10/12 pl-3 absolute"
      type="text"
      placeholder="Pesquisar no Prime Gaming"
    />
    <remix-icon
      class="relative left-5 text-white"
      icon="lupa"
      :size="20"
    ></remix-icon>
  </div>
</template>

<script lang="ts" setup>
import RemixIcon from "./RemixIcon.vue";
</script>
