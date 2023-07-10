<script setup>
import { computed } from 'vue';

const props = defineProps({
  variant: {
    type: String,
    default: 'primary',
    validator: (value) => {
      return ['primary', 'secondary'].includes(value);
    },
  },
  type: {
    type: String,
    default: 'button',
    validator: (value) => {
      return ['button', 'submit', 'reset'].includes(value);
    },
  },
});

// const bgModifier = computed(() =>
//   props.variant === 'primary' ? 'bg-gradient' : 'bg-plain'
// );

const btnStyles = computed(() => [
  'btn',
  {
    'bg-gradient': props.variant === 'primary',
    'bg-plain': props.variant === 'secondary',
  },
]);
</script>

<template>
  <button :class="btnStyles" :type="props.type" v-bind="$props">
    <slot></slot>
  </button>
</template>

<style>
.btn {
  padding: 16px 10px;
  /* background: #ffa279; */
  border-radius: 12px;
  border: none;
  font-family: inherit;
  font-size: 16px;
  line-height: 1.1;
  color: #fff;
  cursor: pointer;
  font-weight: 500;
}

.bg-gradient {
  background: linear-gradient(91deg, #ffa279 0%, #f3743d 100%);
}

.bg-plain {
  background: #ffa279;
}
</style>
