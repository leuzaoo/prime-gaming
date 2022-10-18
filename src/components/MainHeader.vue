<template>
  <div
    class="h-14 bg-[#0B0418] text-white flex items-center justify-center gap-3 md:justify-between md:px-7"
  >
    <p class="font-bold tracking-wide">
      prime <span class="font-normal">gaming</span>
    </p>
    <div class="flex items-center">
      <p
        class="text-sm bg-[#0284c7] py-1 px-2 rounded-sm text-black hover:bg-[#22d3ee] cursor-pointer"
      >
        Experimente a Amazon Prime
      </p>
      <div class="flex items-center ml-3 text-neutral-400">
        <div class="flex items-center gap-1 mr-3 hidden md:contents">
          <remix-icon icon="world" :size="16" />
          <p class="font-bold">PT</p>
          <remix-icon icon="arrow-down-s" :size="16" />
        </div>
        <remix-icon icon="user" :size="16" />
        <remix-icon icon="arrow-down-s" :size="16" />
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import RemixIcon from "./RemixIcon.vue";
</script>
