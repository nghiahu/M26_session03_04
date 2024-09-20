<template>
    <div>
        <div v-bind:id="elementId" v-bind:class="elementClass">Văn bản bất kì</div>
    </div>
</template>

<script setup>
    const elementId="text"
    const elementClass=["text","color"]
</script>

<style scoped>
.text{
    font-size: 20px;
}
.color{
    color: red;
}
</style>>

