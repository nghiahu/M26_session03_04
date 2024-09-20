<template>
  <div>
    <a href="https://www.google.com">google</a>
    <a @click.stop.prevent="handleRouter" href="http://www.google.com">google</a>
  </div>
</template>

<script setup>
    const handleRouter=()=>{
        alert("Đường dẫn không hợp lệ")
    }
</script>

<style>

</style>