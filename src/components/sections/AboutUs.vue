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
</template>

<script>

    export default {
        name: 'AboutUs',
    }

</script>

<style>

    .about-us-root {
        display: flex;
        flex-direction: column;
        text-align: center;
        width: 100%;
        margin-top: 15%;
    }

    .about-us-header {
        font-family: 'K2D', sans-serif;
        font-size: 48px;
        margin-bottom: 2%;
    }

    .about-us-body {
        font-family: 'K2D', sans-serif;
        font-size: 22px;
        width: 56%;
        margin: auto;
    }

</style>