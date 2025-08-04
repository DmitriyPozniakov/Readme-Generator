<template>
  <div>
    <FloatingWidget />
     <LogoWrapper image="/images/document.svg"  />
     <LogoWrapper border-radius="true" image="/images/github.svg" />
    <p class="heavy">Readme</p>
    <p class="bold">Bold</p>
    <p class="semiBold">SemiBold</p>
    <p class="medium">Medium</p>
  </div>
</template>

<script setup>
import FloatingWidget from "~/assets/components/FloatingWidget.vue";
import LogoWrapper from "~/assets/components/LogoWrapper.vue";
</script>

<style scoped>
div {
  background: var(--background-color);
}

p {
  font-size: 4rem;
}
.heavy {
  font-family: "SF UI Display";
  font-weight: 800;
  color: transparent;
  text-transform: uppercase;
  -webkit-background-clip: text;
  background-clip: text;
  background-image: var(--gradient-primary);
  -webkit-text-fill-color: transparent;
}
.bold {
  font-family: "SF UI Display";
  font-weight: 700;
  color: var(--primary-color);
}
.semiBold {
  font-family: "SF UI Display";
  font-weight: 600;
  color: var(--secondary-color);
}
.medium {
  font-family: "SF UI Display";
  font-weight: 500;
  color: var(--grey-color);
}
</style>