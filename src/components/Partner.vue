<template>
    <!-- Partner Logo Section Begin -->
    <div class="partner-logo">
        <div class="container">
            <carousel class="logo-carousel" :loop="true" :items="5"  :dots="false" :nav="false" :autoplay="true">
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/mango.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/Zara.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/stradivarius.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/pullandbear.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/bershka.png" alt="" />
                    </div>
                </div>
            </carousel>
        </div>
    </div>
    <!-- Partner Logo Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel'

    export default {
        name: 'Partner',
        components: {
            carousel
        }
    }
    </script>

    <style scoped>
    .logo-item {
        margin-right: 25px;
    }
    </style>