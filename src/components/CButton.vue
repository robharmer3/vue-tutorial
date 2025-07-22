<template>
  <button class="button">
    <slot></slot>
  </button>
</template>

<style scoped>
.button {
  background: red;
  color: white;
  border: none;
  cursor: pointer;
}
</style>
