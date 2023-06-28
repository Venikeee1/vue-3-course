<script setup></script>

<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>

<style>
.btn {
  padding: 16px 10px;
  background: #ffa279;
  border-radius: 12px;
  border: none;
  font-family: inherit;
  font-size: 16px;
  line-height: 1.1;
  color: #fff;
  cursor: pointer;
  font-weight: 500;
}
</style>
