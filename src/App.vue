<script setup>
import { ref } from "vue";
import CButton from "./components/CButton.vue";

const count = ref(0);

const countUp = () => {
  count.value++;
};
</script>

<template>
  <div>
    <h1>Hello Rob's Counter!</h1>
    <CButton @click="countUp">Click Me!</CButton>
  </div>
  <div>
    {{ count }}
  </div>
</template>
