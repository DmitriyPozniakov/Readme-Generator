<template>
  <div class="error-page">
    <h1>Page not found <span>(404)</span></h1>
  </div>
</template>

<style scoped>
.error-page {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
h1 {
  font-family: "SF UI Display";
  font-weight: 800;
  color: var(--primary-color);
  font-size: clamp(5rem, 8vw, 10rem);
  text-align: center;
}

span {
  color: var(--secondary-color);
}
</style>