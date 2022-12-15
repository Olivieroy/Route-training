<script setup>
import { RouterLink, RouterView } from "vue-router";
    import Button from '../components/Button.vue';
</script>

<template>
    <header class="header">
        <a href="https://github.com/Olivieroy/Kit-Starter-VueJS#readme" class="logo" target="_blank"><img src="/favicon.ico" alt="">Starter-Kit-VueJs</a>

       <nav class="nav">
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/components">Components</RouterLink>
            <router-link  to="/about">About</router-link>
            <router-link to="/test">Test</router-link>
       </nav>
        <a href="https://github.com/Olivieroy" target="_blank">Create by Olivieroy</a>
    </header>
</template>

<style lang="scss">

@use '../sass/global' as *;

.header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 100%;
    margin: auto;
    padding: rem(32) rem(16);
    background: color(btow, 0);
}

.nav{
    display: flex;
    gap: rem(20);
    width: rem(400);
}
</style>

<style scoped>
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
}

.logo{
    display: flex;
    align-items: center;
    text-decoration: none;
    color: #000;
}

.logo:hover::after{
    width: 0;
}

a{
    text-decoration: none;
    color: #000;
}

a::after{
    content: "";
    display: block;
    width: 0;
    height: 2px;
    background: #000;
    transition: width .3s;
}

a:hover::after{
    width: 100%;
}

nav{
    display: flex;
    gap: rem(16);
    align-items: center;
    width: auto;
}
</style>