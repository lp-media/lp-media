<template>
    <div class='about-us-root'>
        <div class='about-us-header'>
            About Us
        </div>
        <div class='about-us-body'>
            LP Media is a digital advertising agency based out of Atlanta, GA. We are a
            client obsessed business with the best in house talent available, and we leverage
            the most modern digital tools for driving revenue for your business.
        </div>
    </div>
    <div class='about-us-root-mobile'>
        <div class='about-us-mobile-header'>
            About Us
        </div>
        <div class='about-us-mobile-body'>
            LP Media is a digital advertising agency based out of Atlanta, GA. We are a
            client obsessed business with the best in house talent available, and we leverage
            the most modern digital tools for driving revenue for your business.
        </div>
        <div class='about-us-mobile-body'>
            Interested? Fill out <a class='about-us-mobile-form-link' target='_blank' href='https://forms.gle/SD68Akub5D17iJB99'>this</a> form and get a free audit:
        </div>
    </div>
</template>

<script>

    export default {
        name: 'AboutUs',
    }

</script>

<style>

    /* Mobile */
    @media screen and (max-width: 640px) {

        .about-us-root-mobile {
            display: flex;
            flex-direction: column;
            margin-bottom: 10vh;
        }

        .about-us-root {
            display: none;
        }

        .about-us-mobile-header {
            font-family: 'K2D', sans-serif;
            line-height: 5vh;
            font-size: 8vw;
            font-weight: 300;
            margin: auto;
            margin-bottom: 2vh;
        }

        .about-us-mobile-body {
            max-width: 80%;
            margin: auto;
            text-align: center;
            font-family: 'K2D', sans-serif;
            font-size: 4vw;
            line-height: 3vh;
            margin-bottom: 2vh;
        }

        .about-us-mobile-form-link {
            color: #4c8bf5;
        }

    }

    /* Desktop */
    @media screen and (min-width: 641px) {
        .about-us-root {
            display: flex;
            flex-direction: column;
            text-align: center;
            width: 100%;
            margin-top: 15%;
        }

        .about-us-root-mobile {
            display: none;
        }

        .about-us-header {
            font-family: 'K2D', sans-serif;
            font-size: 3.25vw;
            margin-bottom: 2%;
        }

        .about-us-body {
            font-family: 'K2D', sans-serif;
            font-size: 1.5vw;
            width: 56%;
            margin: auto;
        }
    }

</style>