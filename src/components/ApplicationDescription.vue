<script setup>
import IButton from './IButton.vue';
</script>

<template>
  <section class="container">
    <div class="overview">
      <img class="map-pin" src="/map-pin.svg" alt="map-pin" />
      <h1 class="title">IT traveler</h1>
      <p class="description">
        Простий і зручний веб додаток, який дозволить тобі відмічати твої
        улюблені місця, а також ті, в яких би ти дуже хотів побувати. Тож не
        зволікай і спробуй сам.
      </p>
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

.map-pin {
  margin-bottom: 24px;
}

.overview {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: auto;
  max-width: 510px;
  width: 100%;
  padding: 20px;
}

.title {
  text-align: center;
  font-size: 38px;
  font-weight: 700;
  color: #fff;
  margin-top: 0;
  margin-bottom: 28px;
}

.description {
  text-align: center;
  font-family: 18px;
  line-height: 1.3;
  color: #fff;
  margin-bottom: 44px;
}
</style>
