<script setup>
    import Button from "../components/Button.vue";
</script>

<template>
    <h2 class="title-components">Buttons</h2>
    <div class="components">
        <Button text="Button" color="primary" type="filled"  />
        <Button text="Button" color="primary" type="outlined"  />
        <Button text="Button" color="primary" type="link"  />
        <Button text="Button" color="secondary" type="filled"  />
        <Button text="Button" type="outlined" color="secondary"  />
        <Button text="Button" color="secondary" type="link"  /> 
    </div>
</template>

<style lang="scss">

@use '../sass/global' as *;

.components{
    display: flex;
    gap: rem(16);
    align-items: center;
    justify-content: center;
    margin-top: rem(16);
}

.title-components{
    font-size: rem(24);
    font-weight: 700;
    margin-bottom: rem(12);
    text-align: center;
}
</style>