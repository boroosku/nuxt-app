<script setup lang="ts">
console.log("Hello world!")
</script>

<template>
  <div>
    <h2 class="montserrat">Hello world!</h2>
    <h2 class="open-sans">Hello world!</h2>
  </div>
</template>

<style scoped>
.open-sans {
  font-family: "Open Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: italic;
  font-variation-settings:
    "wdth" 100;
}

.montserrat {
  font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}
</style>
