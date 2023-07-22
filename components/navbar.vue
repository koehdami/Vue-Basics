
<template>
        <div class="nav-container">
            <ul class="nav-ul">
                <a href="">Home</a>
                <a href="">Info</a>
                <a href="">Contact</a>
            </ul>
        </div>
</template>



<script setup>



</script>




<style>
    .nav-container{
        display:flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .nav-ul{
        display:flex;
        justify-content: center;
        width: 100%;
        flex-direction: row;
        gap: 40px;
    }
    .nav-ul a{
        text-align: center;
        font-size: 25px;
    }
</style>