<template>
    <div>
        <button @click="handleClick2('Rikkei Academy')">Get param</button>
    </div>
</template>

<script setup>
    function handleClick2(mess){
        console.log(mess);
    }
</script>

<style>

</style>