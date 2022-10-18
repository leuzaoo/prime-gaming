<template>
  <div
    class="relative max-h-40 md:max-h-80 xl:max-h-[550px] xl:max-h-96 overflow-hidden"
  >
    <img class="object-cover w-full h-full" :src="src" :alt="alt" />
    <div
      class="absolute top-0 left-0 bottom-0 right-0 bg-gradient-to-b from-transparent to-black opacity-90"
    ></div>
  </div>
</template>

<script lang="ts" setup>
defineProps<{
  src: string;
  alt?: string;
}>();
</script>
