<template>
  <div>
    <form @submit.prevent="hanSubmit">
        <div>Form</div>
        <input type="text">
        <button>Submit</button>
    </form>
  </div>
</template>

<script setup>
    const hanSubmit=()=>{
        console.log("Form submission prevented!");
    }
</script>

<style>

</style>