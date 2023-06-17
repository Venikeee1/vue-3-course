<script setup>
import ApplicationDescription from './components/ApplicationDescription.vue';
import StaticMapImage from './components/StaticMapImage.vue';
</script>

<template>
  <section class="content">
    <ApplicationDescription />
    <StaticMapImage />
  </section>
</template>

<style scoped>
.content {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
</style>
