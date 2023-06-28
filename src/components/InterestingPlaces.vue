<script setup>
import IButton from './IButton.vue';
import PlaceOverview from './PlaceOverview.vue';

const places = [
  { title: 'Kyiv', description: 'Lovely place' },
  { title: 'Lviv', description: 'What a nice place' },
];
</script>

<template>
  <div class="title">Додані маркери</div>
  <PlaceOverview v-for="{ title, description } in places" :key="title" />
  <IButton>Додати маркер</IButton>
</template>

<style scoped>
.title {
  margin-bottom: 18px;
  font-size: 14px;
  color: var(--secondary-text-color);
}
</style>
