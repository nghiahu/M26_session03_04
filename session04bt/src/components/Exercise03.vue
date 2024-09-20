<template>
  <div>
    Acreage: {{ acreage }}
    <button @click="handleChangWidth">Change data</button>
  </div>
</template>

<script setup>
import { computed, ref } from "vue";

const width = ref(10);
const height = ref(10);

const acreage = computed(() => {
  return width.value * height.value;
});

const handleChangWidth = () => {
  width.value += 10; 
};
</script>

<style>

</style>
