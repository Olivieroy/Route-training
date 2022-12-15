<script setup>
    import Button from '../components/Button.vue';
</script>

<template>
    <div class="abouthelp">
        <img src="../../public/img/Discussion.png" alt="" class="img">
        <div class="text">
            <h2>Need help ?</h2>
            <p>You are stuck on something? Do you need help? Or do you just have a question? Feel free to contact me on the github discussion folder.</p>
            <Button text="Go to the discussion folder" link="https://github.com/Olivieroy/Kit-Starter-VueJS/discussions/1" target="_blank" color="secondary" />
        </div>
        
    </div>
</template>

<style lang="scss">

@use '../sass/global' as *;

    .abouthelp{
        display: flex;
        align-items: center;
        justify-content: flex-start;
        gap: rem(12);

        .img{
            max-width: 25%;
        }

        .text{
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            // justify-content: flex-start;
            gap: rem(12);

            max-width: 75%;

            h2{
                font-size: rem(40);
                font-weight: 700;
            }
        }
    }

</style>