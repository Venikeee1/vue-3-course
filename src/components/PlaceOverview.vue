<script setup>
import IconButton from './IconButton.vue';
import IconDelete from '../assets/trash.svg';
import IconEdit from '../assets/edit.svg';
</script>

<template>
  <div class="place">
    <img
      class="image"
      width="76"
      height="76"
      src="https://ukr-prokat.com/wp-content/uploads/2020/07/lviv.jpg"
      alt=""
    />
    <div class="overview">
      <div class="title-wrapper">
        <h2 class="title">Place title</h2>
        <div class="title-actions">
          <IconButton>
            <IconEdit />
          </IconButton>
          <IconButton>
            <IconDelete />
          </IconButton>
        </div>
      </div>
      <p class="description">Place description</p>
    </div>
  </div>
</template>

<style scoped>
.place {
  display: flex;
  margin-bottom: 24px;
  padding-bottom: 18px;
  border-bottom: 1px solid rgba(44, 44, 44, 0.1);
}

.place:nth-last-child {
  margin-bottom: 0;
}

.image {
  display: block;
  width: 76px;
  height: 76px;
  object-fit: cover;
  margin-right: 16px;
  border-radius: 4px;
}

.title {
  font-size: 14px;
  font-weight: 500;
  line-height: 1.3;
  margin-top: 0;
  margin-bottom: 8px;
}

.description {
  font-size: 12px;
  color: var(--secondary-text-color);
}

.overview {
  width: 100%;
}

.title-wrapper {
  display: flex;
  justify-content: space-between;
}

.title-actions {
  display: flex;
  gap: 8px;
}
</style>
