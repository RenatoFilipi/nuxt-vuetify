<script setup lang="ts">
const test = () => {
  alert("test");
};
</script>

<template>
  <div class="container"><v-btn @click="test">button</v-btn></div>
</template>

<style lang="css">
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
