<template lang="pug">
main
  h1 {{title}}
</template>


<script>
export default {
    data: function() {
        return {
            title: 'My First Vue + Webpack + Scss + Pug + Yarn Project'
        }
    }
}
</script>

<style lang="scss" scoped>
    h1 {
    font-family: Dosis;
    font-weight: 200;
    text-align: center;
    display: block;
    color: #fff;
    width: 100%;
    letter-spacing: 1px;
    -webkit-transform-style: preserve-3d;
    -moz-transform-style: preserve-3d;
    transform-style: preserve-3d;
    -webkit-transform: translate3d(0,0,0);
    -moz-transform: translate3d(0,0,0);
    transform: translate3d(0,0,0);
    opacity: 0;
    -webkit-animation: anim 3.2s ease-out forwards 1s;
    animation: anim 3.2s ease-out forwards 1s;
    }
    strong {
    display: block;
    font-weight: 400;
    }


    @-webkit-keyframes anim {
    0% {
        text-shadow: 0 0 50px #fff;
        letter-spacing: 40px;
        opacity: 0;
        -webkit-transform: rotateY(-90deg);
    }
    50% {
        text-shadow: 0 0 1px #fff;
        opacity: 0.8;
        -webkit-transform: rotateY(0deg);
    }
    75% {
        text-shadow: 0 0 1px #fff;
        opacity: 0.8;
        -webkit-transform: rotateY(0deg) translateZ(60px);
    }
    100% {
        text-shadow: 0 0 1px #fff;
        opacity: 0.8;
        letter-spacing: 8px;
        -webkit-transform: rotateY(0deg) translateZ(100px);
    }

    }
    @keyframes anim {
    0% {
        text-shadow: 0 0 50px #fff;
        letter-spacing: 40px;
        opacity: 0;
        -moz-transform: rotateY(-90deg);
    }
    50% {
        text-shadow: 0 0 1px #fff;
        opacity: 0.8;
        -moz-transform: rotateY(0deg);
    }
    75% {
        text-shadow: 0 0 1px #fff;
        opacity: 0.8;
        -moz-transform: rotateY(0deg) translateZ(60px);
    }
    100% {
        text-shadow: 0 0 1px #fff;
        opacity: 0.8;
        letter-spacing: 8px;
        -moz-transform: rotateY(0deg) translateZ(100px);
    }

    }
</style>

