<template>
  <div id="vue-sample-component">{{ message }}</div>
</template>

<script setup>
const message = "Vue Sample Message";
</script>

<style scoped>
#vue-sample-component {
  background-color: green;
  color: white;
}
</style>
