<script setup>
    import Button from '../components/Button.vue';
</script>

<template>
    <div class="aboutproject">
        <div class="text">
            <h1>What is this project?</h1>
            <p>
                This is a folder completely configured to start well with Vue 3 and SASS. 
            </p>
            <p>
                The SASS configuration is the same as on my Web-starter project.
            </p>
            <p>
                If you don't know my Web-starter project and/or you are not comfortable with SASS I invite you to see my project by clicking just below
            </p>
            <Button text="Voir le projet Web-starter" link="https://github.com/Olivieroy/web-starter" target="_blank" color="secondary"/>
        </div>
        <img src="../../public/img/VueSASS.png" alt="" class="img">
    </div>
</template>

<style lang="scss">

@use '../sass/global' as *;

    .aboutproject{
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: rem(12);

  .text{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    // justify-content: flex-start;
    gap: rem(12);

    max-width: 75%;

    h1{
        font-size: rem(40);
        font-weight: 700;
    }
  }

  .img{
    max-width: 25%;
  }

}
</style>