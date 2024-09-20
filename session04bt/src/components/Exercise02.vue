<template>
  <div>
    <h3>Company: {{user.company}}</h3>
    <h3>Age: {{user.age}}</h3>
    <button @click="handleChangd">Change data</button>
  </div>
</template>

<script setup>
import { reactive } from "vue";
    
    const user = reactive({
        age:2,
        company:"Rekkei Academy"
    })
    const handleChangd=()=>{
        user.age = 1;
        user.company = "Rekkei Education"
    }
</script>

<style>

</style>