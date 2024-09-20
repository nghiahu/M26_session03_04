<template>
  <div>
    <div v-bind:class="{active:isActive}" v-bind:style="{backgroundColor:backgroundColor,color}">Block</div>
  </div>
</template>

<script setup>
    const isActive = true;
    const backgroundColor = "blue";
</script>

<style scoped>
.active{
    width: 100px;
    display: flex;
    place-content: center;
    color: white;
}
</style>