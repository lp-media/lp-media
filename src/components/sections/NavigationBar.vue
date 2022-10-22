<template>
    <div class='nav-bar-root'>
        <div class='nav-bar-left'>
            <div class='logo-wrapper'>
                <img class='logo-image' src='../../assets/lp-media-logo.png'/>
                <div class='logo-text'>LP Media</div>
            </div>
            <div class='link-wrapper'>
                <div @click='scrollToTop()' class='link'>Solutions</div>
                <div @click='scrollToFramework()' class='link'>Framework</div>
                <div @click='scrollToAboutUs()' class='link'>Company</div>
            </div>
        </div>
        <div class='nav-bar-right'>
            <div class='border-link-wrapper'><a class='border-link' target='_blank' href='https://forms.gle/SD68Akub5D17iJB99'>Contact Us</a></div>
        </div>
    </div>
</template>

<script>

    export default {
        name: 'NavigationBar',
        methods: {
            scrollToTop() {
                window.scrollTo( { top: 0, behavior: 'smooth' } )
            },
            scrollToFramework() {
                window.scrollTo( { top: 750, behavior: 'smooth' } )
            },
            scrollToAboutUs() {
                window.scrollTo( { top: 2000, behavior: 'smooth' } )
            }
        }
    }

</script>

<style>

    /* Mobile */
    @media screen and (max-width: 640px) {

        .nav-bar-root {
            width: 100%;
            height: 20%;
            margin-bottom: 5vh;
            display: inline-flex;
            border-bottom: 1px solid #DFDFDF;
            justify-content: center;
        }

        .nav-bar-left {
            width: 100%;
            display: inline-flex;
            justify-content: center;
        }

        .logo-wrapper {
            display: inline-flex;
        }

        .logo-image {
            width: 10vw;
            padding-bottom: 2vh;
            padding-top: 1vh;
        }

        .logo-text {
            display: none;
        }

        .link-wrapper {
            display: none;
        }

        .nav-bar-right {
            display: none;
        }
    }

    /* Desktop */
    @media screen and (min-width: 641px) {

        .nav-bar-root {
            width: 90%;
            height: 40%;
            margin: 5vh 2vw 2vh 2vw;
            display: inline-flex;
        }

        .nav-bar-left {
            width: 80%;
            display: inline-flex;
            justify-content: left;
        }

        .nav-bar-right {
            width: 20%;
            display: inline-flex;
            justify-content: right;
        }

        .logo-wrapper {
            height: 100%;
            display: inline-flex;
            padding-left: 3%;
        }

        .logo-image {
            height: 15vh;
            width: 5vw;
            max-height: 50%;
            max-width: 50%;
        }

        .logo-text {
            margin-top: 2%;
            margin-left: 8%;
            width: 20vw;
            font-family: 'K2D', sans-serif;
            font-size: 2.5vw;
            cursor: default;
        }

        .link-wrapper {
            position: relative;
            left: -5vw;
            height: 50%;
            display: inline-flex;
            justify-content: right;
            font-family: 'K2D', sans-serif;
            font-size: 1.5vw;
        }

        .link {
            margin: 2.6vh 3vw 0 3vw;
            font-size: 1.5vw;
            cursor: pointer;
        }

        .link:hover {
            border-bottom: 2px solid black;
        }

        .border-link-wrapper {
            padding-top: 3%;
            margin-top: 5%;
        }

        .border-link {
            font-size: 1.5vw;
            height: 60%;
            text-decoration: none;
            color: #000000;
        }

        .border-link:hover {
            border-bottom: 2px solid black;
            padding-bottom: 9%;
        }
    }

</style>