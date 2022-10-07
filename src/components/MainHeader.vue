<template>
  <div class="flex bg-[#0B0418] text-white h-14 justify-around shadow-2xl z-10 relative">
    <ul class="flex gap-2 items-center">
      <li>
        <p class="font-bold">prime <span class="font-normal">gaming</span></p>
      </li>
      <li>
        <p class="bg-[#5FB7FF] px-2 py-1 rounded text-sm text-black">
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
