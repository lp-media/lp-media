<template>
    <NavigationBar></NavigationBar>
    <HeroSection></HeroSection>
    <FrameworkSection></FrameworkSection>
    <OptimizationSection></OptimizationSection>
    <AboutUs></AboutUs>
    <ClientForm></ClientForm>
</template>

<script>

    import NavigationBar from './sections/NavigationBar.vue'
    import HeroSection from './sections/HeroSection.vue'
    import FrameworkSection from './sections/FrameworkSection.vue'
    import OptimizationSection from './sections/OptimizationSection.vue'
    import AboutUs from './sections/AboutUs.vue'
    import ClientForm from './sections/ClientForm.vue'

    export default {
        name: 'LandingPage',
        components: {
            NavigationBar,
            HeroSection,
            FrameworkSection,
            OptimizationSection,
            AboutUs,
            ClientForm,
        },
    }

</script>

<style>

    @import url('https://fonts.googleapis.com/css2?family=K2D:ital,wght@0,100;0,200;0,400;0,500;0,600;0,700;0,800;1,100&display=swap');

    #app {
        font-family: 'K2D', sans-serif;
    }

</style>