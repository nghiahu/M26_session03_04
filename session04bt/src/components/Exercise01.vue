<template>
  <div>
    <div><button @click="hadleCount">Click {{count}} lần</button></div>
  </div>
</template>

<script setup>
import { ref } from "vue";

    const count = ref(0)
    const hadleCount=()=>{
        count.value++
    }
</script>

<style>

</style>