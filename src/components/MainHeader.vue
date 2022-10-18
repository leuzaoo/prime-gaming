<template>
  <div
    class="flex items-center bg-[#0B0418] text-white h-16 shadow-2xl z-10 relative"
  >
    <ul class="flex justify-between gap-2 px-2 w-full md:px-20 items-center">
      <li>
        <p class="font-bold xl:text-2xl xl:pl-56">
          prime <span class="font-normal">gaming</span>
        </p>
      </li>
      <div class="flex pr-60 gap-3 items-center">
        <p
          class="border-white border p-1 rounded-sm text-sm hover:bg-[#423B50] cursor-pointer"
        >
          Fazer login
        </p>
        <li>
          <p
            class="bg-[#5FB7FF] px-2 py-1 rounded-sm text-sm text-black cursor-pointer hover:bg-cyan-500"
          >
            Experimente Amazon Prime
          </p>
        </li>
        <li class="flex items-center gap-1 text-neutral-400">
          <remix-icon icon="world" :size="20" />
          <p class="font-bold">PT</p>
          <remix-icon icon="arrow-down-s" :size="20" />
        </li>
        <li class="flex items-center ml-3 text-neutral-400">
          <remix-icon icon="user" :size="16" />
          <remix-icon icon="arrow-down-s" :size="20" />
        </li>
      </div>
    </ul>
  </div>
</template>

<script lang="ts" setup>
import RemixIcon from "./RemixIcon.vue";
</script>
