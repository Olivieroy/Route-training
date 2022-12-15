<script setup>
import AboutProject from '../parts/AboutProject.vue';
import AboutHelp from '../parts/AboutHelp.vue';
</script>

<template>
    <div class="about">
        <AboutProject/>
        
        <AboutHelp/>

    </div>

</template>

<style lang="scss">

@use '../sass/global' as *;

    .about{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: rem(12);
    }
</style>

