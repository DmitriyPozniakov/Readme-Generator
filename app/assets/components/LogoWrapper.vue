<template>
  <div class="wrapper" :class="{ rounded: borderRadius }">
    <img :src="image" alt="logo" />
  </div>
</template>

<script setup lang="ts">
import { defineProps } from "vue";

defineProps<{
  borderRadius?: boolean;
  image: string;
}>();
</script>

<style scoped>
.wrapper {
  background: var(--background-logo);
  display: flex;
  align-items: center;
  justify-content: center;
  width: 60px;
  height: 60px;
  padding: 10px;
  border-radius: 15px;
}

img {
    height: 40px;
    width: 40px;
}

.rounded {
  border-radius: 50%;
}
</style>