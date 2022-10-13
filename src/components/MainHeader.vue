<template>
  <div
    class="flex items-center bg-[#0B0418] text-white h-14 shadow-2xl z-10 relative"
  >
    <ul class="flex justify-between gap-2 px-5 w-full md:px-20">
      <li>
        <p class="font-bold">prime <span class="font-normal">gaming</span></p>
      </li>
      <li>
        <p class="bg-[#5FB7FF] px-2 py-1 rounded text-sm text-black font-bold cursor-pointer hover:bg-orange-400">
          Experimente Amazon Prime
        </p>
      </li>
      <li class="flex items-center ml-3">
        <remix-icon icon="user" :size="16" />
        <remix-icon icon="arrow-down-s" :size="20" />
      </li>
    </ul>
  </div>
</template>

<script lang="ts" setup>
import RemixIcon from "./RemixIcon.vue";
</script>
