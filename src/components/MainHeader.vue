<template>
  <div
    class="h-14 md:h-16 bg-[#0B0418] text-white xl:text-xl flex items-center justify-center gap-3 md:justify-between md:px-7 xl:px-20"
  >
    <p class="font-bold tracking-wide">
      prime <span class="font-normal">gaming</span>
    </p>
    <div class="flex items-center">
      <div
        class="px-2 border border-neutral-500 rounded-sm hover:bg-neutral-700 cursor-pointer"
      >
        <p class="hidden md:contents text-sm">Fazer login</p>
      </div>
      <p
        class="text-sm bg-[#0284c7] py-1 px-2 ml-3 rounded-sm text-black hover:bg-[#22d3ee] cursor-pointer"
      >
        Experimente Amazon Prime
      </p>
      <div class="flex items-center ml-3 text-neutral-400">
        <div class="flex items-center hidden md:contents">
          <remix-icon icon="world" :size="16" />
          <p class="font-semibold ml-1">PT</p>
          <remix-icon icon="arrow-down-s" :size="16" />
        </div>
        <div class="flex ml-3">
          <remix-icon icon="user" :size="16" />
          <remix-icon icon="arrow-down-s" :size="16" />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import RemixIcon from "./RemixIcon.vue";
</script>
