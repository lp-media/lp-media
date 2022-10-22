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
    <div class='hero-section-root-mobile'>
        <div class='hero-section-mobile-image-wrapper'>
            <img class='hero-section-mobile-image' src='../../assets/hero-image-mobile.png'/>
        </div>
        <div class='hero-section-mobile-header'>
            Grow your leads with select advertising
        </div>
        <div class='hero-section-mobile-sub-header'>
            Leverage Google and Facebook marketing to drive revenue for your business
        </div>
        <a class='hero-section-mobile-audit-button-wrapper' target='_blank' href='https://forms.gle/SD68Akub5D17iJB99'>
            <button class='hero-section-mobile-audit-button'>Get your free audit</button>
        </a>
    </div>
</template>

<script>

    export default {
        name: 'HeroSection',
    }

</script>

<style>

    /* Mobile */
    @media screen and (max-width: 640px) {

        .hero-section-root {
            display: none;
        }

        .hero-section-root-mobile {
            width: 100%;
            display: flex;
            flex-direction: column;
            margin: auto;
        }

        .hero-section-mobile-image-wrapper {
            margin: auto;
        }

        .hero-section-mobile-image {
            margin-top: 2vh;
            margin-bottom: 3vh;
            max-width: 70vw;
        }

        .hero-section-mobile-header {
            text-align: center;
            font-family: 'K2D', sans-serif;
            font-size: 8vw;
            font-weight: 300;
            margin-bottom: 4vh;
        }

        .hero-section-mobile-sub-header {
            margin: auto;
            text-align: center;
            font-family: 'K2D', sans-serif;
            font-size: 4vw;
            font-weight: 300;
            max-width: 80%;
            margin-bottom: 4vh;
        }

        .hero-section-mobile-audit-button-wrapper {
            margin: auto;
        }

        .hero-section-mobile-audit-button {
            background-color: #4c8bf5;
            color: white;
            width: 40vw;
            height: 5.5vh;
            font-size: 4vw;
            margin: auto;
            border-radius: 5px;
            border: none;
            margin-bottom: 3vh;
        }
    }

    /* Desktop */
    @media screen and (min-width: 641px) {

        .hero-section-root {
            width: 100%;
            margin: auto;
            margin-top: 4%;
            display: inline-flex;
        }

        .hero-section-root-mobile {
            display: none;
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
            max-width: 80%;
            margin-left: 30%;
            font-size: 3.25vw;
        }

        .hero-text-sub-header {
            width: 90%;
            max-width: 85%;
            margin-left: 30%;
            margin-top: 3%;
            font-size: 1.53vw;
            line-height: 150%;
        }

        .hero-section-right {
            width: 50%;
            margin: auto;
            padding-top: 3%;
            margin-left: 20%;
        }

        .hero-image {
            height: 60%;
            width: 60%;
        }
    }

    

</style>