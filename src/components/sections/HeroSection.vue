<template>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <div class='hero-section-root'>
        <div class='hero-section-left'>
            <div class='hero-text-header'>
                Grow leads and drive revenue with select targeted advertising
            </div>
            <div class='hero-text-sub-header'>
                We leverage Google and Facebook marketing to provide tailored growth strategies for businesses
            </div>
        </div>
        <div class='hero-section-right'>
            <img class='hero-image' src='../../assets/lp-media-hero-image.png'/>
        </div>
    </div>
</template>

<script>

    export default {
        name: 'HeroSection',
    }

</script>

<style>

    .hero-section-root {
        width: 100%;
        margin: auto;
        margin-top: 8%;
        display: inline-flex;
    }

    .hero-section-left {
        display: flex;
        padding-top: 5%;
        width: 50%;
        height: 20%;
        flex-direction: column;
        font-family: 'K2D', sans-serif;
    }

    .hero-text-header {
        width: 100%;
        max-width: 480px;
        margin-left: 30%;
        font-size: 48px;
    }

    .hero-text-sub-header {
        width: 90%;
        max-width: 480px;
        margin-left: 30%;
        margin-top: 1%;
        font-size: 22px;
        line-height: 35px;
    }

    .hero-section-right {
        width: 50%;
        margin: auto;
        padding-top: 3%;
        margin-left: 20%;
    }

    .hero-image {
        height: 335px;
        width: 335px;
    }

</style>