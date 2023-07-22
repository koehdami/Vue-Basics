
<template>
    <div v-for="item in itemList">
        <p>{{ item.title }}</p>
        <p>{{ item.description }}</p>
        <p>{{ item.content }}</p>
    </div>
</template>



<script setup>
import { ref } from 'vue';

const itemList = ref([
    {
        title: 'Item 1',
        description: 'Description for Item 1',
        content: 'Content for Item 1',
    },
    {
        title: 'Item 2',
        description: 'Description for Item 2',
        content: 'Content for Item 2',
    },
    {
        title: 'Item 3',
        description: 'Description for Item 3',
        content: 'Content for Item 3',
    },
    ]);
</script>




<style></style>