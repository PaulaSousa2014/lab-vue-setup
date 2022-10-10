<template>
    <h1>New Component on Composition</h1>
    <h3>
        {{title}}
    </h3>
</template>
<script setup>
import { ref } from 'vue'
const title = ref('I am using JavaScript')

</script>
<style></style>