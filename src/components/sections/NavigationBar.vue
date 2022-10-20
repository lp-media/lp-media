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
            <div ><a class='border-link' target='_blank' href='https://forms.gle/SD68Akub5D17iJB99'>Contact Us</a></div>
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
                window.scrollTo( { top: 700, behavior: 'smooth' } )
            },
            scrollToAboutUs() {
                window.scrollTo( { top: 2000, behavior: 'smooth' } )
            }
        }
    }

</script>

<style>

    .nav-bar-root {
        width: 95%;
        height: 100%;
        margin: 35px 35px 35px 35px;
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
    }

    .logo-image {
        max-height: 65px;
        max-width: 65px;
    }

    .logo-text {
        margin: auto;
        margin-left: 25px;
        font-family: 'K2D', sans-serif;
        font-size: 32px;
    }

    .link-wrapper {
        height: 100%;
        margin-left: 30px;
        display: inline-flex;
        justify-content: right;
        font-family: 'K2D', sans-serif;
        font-size: 22px;
    }

    .link {
        margin: 15px 35px 0px 35px;
        font-size: 22px;
        cursor: pointer;
    }

    .link:hover {
        border-bottom: 2px solid black;
    }

    .border-link {
        margin-top: 15px;
        font-size: 22px;
        text-decoration: none;
        color: #000000;
    }

    .border-link:hover {
        border-bottom: 2px solid black;
    }

</style>