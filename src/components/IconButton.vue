<template>
  <button class="button">
    <slot></slot>
  </button>
</template>

<style scoped>
.button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  color: var(--secondary-text-color);
  background: none;
  border: none;
  width: 16px;
  height: 16px;
  cursor: pointer;
  transition: color 0.3s;
  padding: 0;
}

.button:hover {
  color: #f3743d;
}
</style>
