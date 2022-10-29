<template>
  <img class="object-cover w-full h-full" :src="src" :alt="alt" />
</template>

<script lang="ts" setup>
defineProps<{
  src: string;
  alt?: string;
}>();
</script>
