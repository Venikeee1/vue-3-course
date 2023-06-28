<script setup>
// import ApplicationDescription from './components/ApplicationDescription.vue';
// import StaticMapImage from './components/StaticMapImage.vue';
import MapSideBar from './components/MapSideBar.vue';
</script>

<template>
  <!-- <section class="content">
    <ApplicationDescription />
    <StaticMapImage />
  </section> -->

  <MapSideBar />
</template>

<style scoped>
.content {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
</style>
