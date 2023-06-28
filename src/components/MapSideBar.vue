<script setup>
import InterestingPlaces from './InterestingPlaces.vue';
</script>

<template>
  <div class="side-bar">
    <div class="places">
      <InterestingPlaces />
    </div>
  </div>
</template>

<style scoped>
.side-bar {
  background-color: #f9f9f9;
  width: 380px;
  box-shadow: 0px 4px 31px 0px rgba(44, 44, 44, 0.1);
}

.places {
  padding: 0 24px;
  margin-top: 44px;
}
</style>
