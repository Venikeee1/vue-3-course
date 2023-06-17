<script setup>
import IButton from './IButton.vue';
</script>

<template>
  <section class="container">
    <div class="description">
      <IButton />
    </div>
  </section>
</template>

<style scoped>
.container {
  display: flex;
  background: #f3743d;
  height: 100vh;
}

.description {
  margin: auto;
}
</style>
