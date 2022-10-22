<template>
    <div class='client-form-root'>
        <div class='client-form-header'>
            Interested? Fill out <a class='form-link' target='_blank' href='https://forms.gle/SD68Akub5D17iJB99'>this</a> form and get a free audit:
        </div>
    </div>
</template>

<script>

    export default {
        name: 'ClientForm',
    }

</script>

<style>

    /* Mobile */
    @media screen and (max-width: 640px) {
        .client-form-root {
            display: none;
        }
    }

    /* Desktop */
    @media screen and (min-width: 641px) {
        .client-form-root {
            display: flex;
            flex-direction: column;
            text-align: center;
            width: 100%;
            margin-top: 3%;
            margin-bottom: 35vh;
        }

        .client-form-root-mobile {
            display: none;
        }

        .client-form-header {
            font-family: 'K2D', sans-serif;
            font-size: 1.5vw;
            width: 56%;
            margin: auto;
        }

        .form-link {
            color: #4c8bf5;
        }
    }

</style>