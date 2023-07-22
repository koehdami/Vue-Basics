
<template>
    <h1>2 + 2 = {{ 2 + 2 }}</h1>
    <h1> refVar = {{ returnVar }}</h1>
    <h1 v-if="bool">Bool = true</h1>
    <h1 v-else>bool = false</h1>
</template>



<script setup>
import { computed, ref } from 'vue';

    let refVar = ref(1)
    let bool = ref(true)
    const returnVar = computed(() =>{
        return refVar;
    })
    
</script>




<style></style>