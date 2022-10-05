<template>
    <svg
      viewBox="0 0 24 24"
      :width="size || 24"
      :height="size || 24"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path fill="currentColor" :d="iconValue" />
    </svg>
  </template>
  
  <script lang="ts" setup>
  import { ref, onBeforeMount } from "vue";
  import { IconTypes } from "../declarations/IconTypes";
  interface Props {
    size?: number;
    fill?: boolean;
    icon: keyof typeof IconTypes;
  }
  const props = defineProps<Props>();
  const iconValue = ref("");
  onBeforeMount(async () => {
    const value = await import(
      `../icons/${props.icon}-${props.fill ? "fill" : "line"}.ts`
    );
    iconValue.value = value.default;
  });
  </script>