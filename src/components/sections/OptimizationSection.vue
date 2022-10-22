<template>
    <div class='optimization-section-root'>
        <div class='optimization-section-header'>
            Continuous Optimization
        </div>
        <div class='optimization-section-sub-header'>
            <span class='blue'>Quality</span> is always better than quantity
        </div>
        <img class='optimization-graphic' src='../../assets/optimization-graphic.png'/>
        <div class='selection-header-wrapper'>
            <div v-if='this.currentSelection == 0' class='selected-selection' @click='this.currentSelection = 0'>
                <span class='blue-bottom-border'>Manage</span>
            </div>
            <div v-else class='selection' @click='this.currentSelection = 0'>
                Manage
            </div>
            <div v-if='this.currentSelection == 1' class='selected-selection' @click='this.currentSelection = 1'>
                <span class='blue-bottom-border'>Test</span>
            </div>
            <div v-else class='selection' @click='this.currentSelection = 1'>
                Test
            </div>
            <div v-if='this.currentSelection == 2' class='selected-selection' @click='this.currentSelection = 2'>
                <span class='blue-bottom-border'>Analyze</span>
            </div>
            <div v-else class='selection' @click='this.currentSelection = 2'>
                Analyze
            </div>
        </div>
        <div v-if='currentSelection == 0' class='optimization-section-body'>
            Our comprehensive approach towards campaign management prioritizes
            the <strong>quality</strong> of traffic you get to your business. Understanding how to influence the
            quality is equally as - if not more important - than the quantity itself.
        </div>
        <div v-else-if='currentSelection == 1' class='optimization-section-body'>
            From digital advertisements to email marketing, we love testing and will prioritize tests that
            have made the most impact. We leverage the statistics to work in our favor so we can
            help <strong>your</strong> business reach its goals.
        </div>
        <div v-else-if='currentSelection == 2' class='optimization-section-body'>
            An effective marketing campaign is one that leverages a <strong>consistent</strong> approach towards
            optimization. We use the industry's leading tools to help us test new approaches - so we can
            find ways to move your revenue goals forward.
        </div>
    </div>
</template>

<script>

    export default {
        name: 'OptimizationSection',
        data() {
            return {
                currentSelection: 0,
                selection: {
                    'font-size': '24px',
                }
            }
        },
        methods: {
            selectManage() {
                this.currentSelection = 0;
            },
            selectTest() {
                this.currentSelection = 1;
            },
            selectAnalyze() {
                this.currentSelection = 2;
            }
        }
    }

</script>

<style>

    /* Mobile */
    @media screen and (max-width: 640px) {
        .optimization-section-root {
            display: none;
        }
    }

    /* Desktop */
    @media screen and (min-width: 641px) {

        .optimization-section-root {
            display: flex;
            flex-direction: column;
            text-align: center;
            width: 100%;
            margin-top: 15%;
        }

        .optimization-section-root-mobile {
            display: none;
        }

        .optimization-graphic {
            width: 70%;
            margin: auto;
        }

        .optimization-section-header {
            font-family: 'K2D', sans-serif;
            font-size: 3.25vw;
            margin-bottom: 1%;
        }

        .optimization-section-sub-header {
            font-family: 'K2D', sans-serif;
            font-size: 1.5vw;
            margin-bottom: 4%;
        }

        .blue {
            color: #4c8bf5;
        }

        .selection-header-wrapper {
            width: 60%;
            display: inline-flex;
            margin: auto;
            margin-bottom: 3.5%;
        }

        .selection {
            width: 33.33%;
            text-align: center;
            margin: auto;
            font-family: 'K2D', sans-serif;
            font-size: 2.4vw;
            cursor: pointer;
            padding-bottom: 5px;
        }

        .selected-selection {
            width: 33.33%;
            text-align: center;
            margin: auto;
            font-family: 'K2D', sans-serif;
            font-size: 2.4vw;
            cursor: pointer;
            padding-bottom: 5px;        
        }

        .optimization-section-body {
            text-align: center;
            font-family: 'K2D', sans-serif;
            font-size: 1.5vw;
            width: 57%;
            margin: auto;
        }

        .blue-bottom-border {
            border-bottom: 3px solid #4c8bf5;
        }

        .image-wrapper {
            width: 100%;
            margin: auto;
        }

        .optimization-image-wrapper {
            margin-top: 5%;
            max-width: 20%;
        }
    }

</style>