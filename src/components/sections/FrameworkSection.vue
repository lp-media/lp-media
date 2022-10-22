<template>
    <div class='framework-section-root'>
        <div class='framework-section-header'>
            A Proven Strategy For Growth
        </div>
        <div class='framework-section-column-wrapper'>
            <div class='framework-column'>
                <div class='framework-title'>
                    <div class='framework-title-icon'>
                        <img class='icon' src='../../assets/icons/analyze-icon.svg'/>
                    </div>
                    <div class='framework-title-header'>
                        Analyze
                    </div>
                </div>
                <div class='framework-body'>
                    We focus on developing a meaningful relationship with all of our clients,
                    and understanding their business needs comes first.
                </div>
                <div class='framework-body'>
                    Our in house developers and experts will take a look at your existing
                    strategies to find new opportunities specific to your business objectives.
                </div>
            </div>
            <div class='framework-column'>
                <div class='framework-title'>
                    <div class='framework-title-icon'>
                        <img class='icon' src='../../assets/icons/target-icon.svg'/>
                    </div>
                    <div class='framework-title-header'>
                        Target
                    </div>
                </div>
                <div class='framework-body'>
                    Once we determine the right fit, our team will spend time finding the right
                    leads who get the most out of your services. 
                </div>
                <div class='framework-body'>
                    Then, we’ll work with you to build user specific advertisements and target
                    the most relevant platforms for optimal impact. 
                </div>
            </div>
            <div class='framework-column'>
                <div class='framework-title'>
                    <div class='framework-title-icon'>
                        <img class='icon' src='../../assets/icons/play-icon.svg'/>
                    </div>
                    <div class='framework-title-header'>
                        Execute
                    </div>
                </div>
                <div class='framework-body'>
                    Once the ads run, we’ll track their progress and performance and look for ways
                    to optimize your current campaign.
                </div>
                <div class='framework-body'>
                    Full transparency is key for any client engagement of ours, and we are happy to
                    answer any questions you have to improve your experience.
                </div>
            </div>
        </div>
    </div>
    <div class='framework-section-root-mobile'>
        <div class='framework-section-mobile-header'>
            A Proven Strategy
        </div>
        <div class='framework-section-mobile-label'>
            <div class='framework-section-mobile-label-header'>
                <img class='framework-section-mobile-label-header-icon' src='../../assets/icons/analyze-icon.svg' />
                <div class='framework-section-mobile-label-header-text'>
                    Analyze
                </div>
            </div>
            <div class='framework-section-mobile-label-body'>
                We focus on developing a meaningful relationship with all of our clients,
                and understanding their business needs comes first.
            </div>
            <div class='framework-section-mobile-label-body'>
                Our in house developers and experts will take a look at your existing
                    strategies to find new opportunities specific to your business objectives.
            </div>
        </div>
        <div class='framework-section-mobile-label'>
            <div class='framework-section-mobile-label-header'>
                <img class='framework-section-mobile-label-header-icon' src='../../assets/icons/target-icon.svg' />
                <div class='framework-section-mobile-label-header-text'>
                    Target
                </div>
            </div>
            <div class='framework-section-mobile-label-body'>
                Once we determine the right fit, our team will spend time finding the right
                leads who get the most out of your services.
            </div>
            <div class='framework-section-mobile-label-body'>
                Then, we’ll work with you to build user specific advertisements and target
                the most relevant platforms for optimal impact. 
            </div>
        </div>
        <div class='framework-section-mobile-label'>
            <div class='framework-section-mobile-label-header'>
                <img class='framework-section-mobile-label-header-icon' src='../../assets/icons/play-icon.svg' />
                <div class='framework-section-mobile-label-header-text'>
                    Execute
                </div>
            </div>
            <div class='framework-section-mobile-label-body'>
                When the ads run, we’ll track their progress and performance and look for ways
                to optimize your current campaign.
            </div>
            <div class='framework-section-mobile-label-body'>
                Full transparency is key for any client engagement of ours, and we are happy to
                answer any questions you have to improve your experience.
            </div>
        </div>
    </div>
</template>

<script>

    export default {
        name: 'FrameworkSection',
    }

</script>

<style>

    /* Mobile */
    @media screen and (max-width: 640px) {

        .framework-section-root-mobile {
            display: flex;
            flex-direction: column;
            margin-top: 10vh;
            margin-bottom: 10vh;
        }

        .framework-section-root {
            display: none;
        }

        .framework-section-mobile-header {
            display: inline-flex;
            font-family: 'K2D', sans-serif;
            line-height: 5vh;
            font-size: 8vw;
            font-weight: 300;
            margin: auto;
            margin-bottom: 5vh;
        }

        .framework-section-mobile-label {
            display: flex;
            flex-direction: column;
            justify-content: center;
            margin: auto;
            margin-bottom: 2vh;
        }

        .framework-section-mobile-label-header {
            display: inline-flex;
            margin: auto;
            margin-bottom: 2vh;
        }

        .framework-section-mobile-label-header-icon {
            height: 5vh;
        }

        .framework-section-mobile-label-header-text {
            font-family: 'K2D', sans-serif;
            font-size: 5vw;
            font-weight: 600;
            line-height: 5vh;
            margin-left: 2vw;
        }

        .framework-section-mobile-label-body {
            max-width: 85%;
            margin: auto;
            text-align: center;
            font-family: 'K2D', sans-serif;
            font-size: 4vw;
            line-height: 3vh;
            margin-bottom: 2vh;
        }
    }

    /* Desktop */
    @media screen and (min-width: 641px) {

        .framework-section-root {
            display: flex;
            flex-direction: column;
            text-align: center;
            width: 100%;
            margin-top: 15%;
        }

        .framework-section-root-mobile {
            display: none;
        }

        .framework-section-header {
            font-family: 'K2D', sans-serif;
            font-size: 3.25vw;
            margin-bottom: 6%;
        }

        .framework-section-column-wrapper {
            margin: auto;
            margin-left: 10%;
            width: 85%;
            display: inline-flex;
        }

        .framework-column {
            width: 33.33%;
            height: 100%;
        }

        .framework-title {
            font-family: 'K2D', sans-serif;
            font-weight: 400;
            font-size: 2.4vw;
            width: 100%;
            display: inline-flex;
            justify-content: left;
        }

        .framework-title-header {
            line-height: 60px;
            margin-left: 2%;
        }

        .framework-body {
            font-family: 'K2D', sans-serif;
            max-width: 80%;
            font-size: 1.5vw;
            text-align: left;
            margin-top: 5%;
            margin-left: 5%;   
        }

        .icon {
            height: 8vh;
            width: 8vw;
        }
    }

    

</style>