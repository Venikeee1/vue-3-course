<script setup>
import IButton from './IButton.vue';
import PlaceOverview from './PlaceOverview.vue';
import { computed, ref } from 'vue';

const places = [
  { id: '1', title: 'Kyiv', description: 'Lovely place' },
  { id: '2', title: 'Lviv', description: 'What a nice place' },
];
const selectedPlaceId = ref(null);

const selectedPlace = computed(() => {
  return places.find((place) => place.id === selectedPlaceId.value);
});

const changeSelectedPlace = (id) => {
  selectedPlaceId.value = id;
};
</script>

<template>
  <div class="title">Додані маркери</div>
  <div v-if="selectedPlace">Вибране місце: {{ selectedPlace.title }}</div>
  <PlaceOverview
    v-for="{ title, description, id } in places"
    :key="id"
    :title="title"
    :description="description"
    @click="changeSelectedPlace(id)"
  />
  <IButton>Додати маркер</IButton>
</template>

<style scoped>
.title {
  margin-bottom: 18px;
  font-size: 14px;
  color: var(--secondary-text-color);
}
</style>
