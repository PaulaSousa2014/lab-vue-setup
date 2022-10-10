<template>
    <h1>New Component on Composition</h1>
    <h3>
        {{title}}
    </h3>
    <button @click="helloWorld">Iteration 3 Composition</button>
</template>
<script setup>
import { ref } from 'vue'
const title = ref('I am using JavaScript');
const helloWorld = () => {
    console.log('Hello World')
}

</script>
<style></style>