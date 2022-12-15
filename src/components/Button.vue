<script setup>
defineProps({
    text: {
        type: String,
        required: true
    },
    color: {
        type: String,
        default: "primary"
    },
    type: {
        type: String,
        default: "filled"
    },
    link: {
        type: String,
        default: ""
    },
    target:{
        type: String,
        default: "_self"
    }
})
</script>

<template>
    <a  :class="`btn ${type} ${color} `" :href="` ${link}`" :target="` ${target}`">
        {{ text }}
    </a>
</template>

<style lang="scss">

@use '../sass/global' as *;

.btn{
    padding:  rem(16) rem(20);
    display: flex;
    align-items: center;
    justify-content: center;
    gap: rem(8);
    width: fit-content;
    transition: all .2s ease-in-out;
    cursor: pointer;
    text-decoration: none;

    &.filled{
        padding:rem(19) rem(23);

        &.primary{
            background-color: color(primary, base);
            color: color(btow, 0);
            border: none;
            border-radius: rem(4);
            // box-shadow: 0 rem(2) rem(4) rgba(0, 0, 0, 0.25);
            &:hover{
                background-color: color(primary, 900);
            }
        }

        &.secondary{
            background-color: color(secondary, base);
            color: color(btow, 0);
            border: none;
            border-radius: rem(4);
            // box-shadow: 0 rem(2) rem(4) rgba(0, 0, 0, 0.25);
            &:hover{
                background-color: color(secondary, 900);
            }
        }
    }


    
    &.outlined{

        &.primary{
            background-color: color(btow, 0);
            color: color(primary, base);
            border: 3px solid color(primary, base);
            border-radius: rem(4);
            // box-shadow: 0 rem(2) rem(4) rgba(0, 0, 0, 0.25);
            &:hover{
                background-color: color(primary, base);
                color: color(btow, 0);
            }
        }


        &.secondary{
            border: rem(3) solid color(secondary, base);
            background: none;
            color: color(secondary, base);
            border-radius: rem(4);

            &:hover{
                background: color(secondary, base);
                color : color(btow, 0);
            }
        }

    }

    &.link{
        text-decoration: none;
        
        &.primary{
            color: color(primary, base);
            &:hover{
                color: color(primary, 900);
                text-decoration: underline;
            }
        }

        &.secondary{
            color: color(secondary, base);
            &:hover{
                color: color(secondary, 900);
                text-decoration: underline;
            }
        }
    }


}
</style>