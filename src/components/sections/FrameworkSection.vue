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
</template>

<script>

    export default {
        name: 'FrameworkSection',
    }

</script>

<style>

    .framework-section-root {
        display: flex;
        flex-direction: column;
        text-align: center;
        width: 100%;
        margin-top: 15%;
    }

    .framework-section-header {
        font-family: 'K2D', sans-serif;
        font-size: 48px;
        margin-bottom: 5%;
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
        font-weight: 500;
        font-size: 32px;
        width: 85%;
        display: inline-flex;
        justify-content: left;
    }

    .framework-title-header {
        line-height: 60px;
        margin-left: 5%;
    }

    .framework-body {
        font-family: 'K2D', sans-serif;
        max-width: 80%;
        font-size: 22px;
        text-align: left;
        margin-top: 5%;
        margin-left: 5%;   
    }

    .icon {
        height: 65px;
        width: 65px;
    }

</style>