<template>
     <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false">
            <div class="single-hero-items set-bg" style="background-image: url('img/hero-1.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>All brand, Man, Woman, Kids</span>
                            <h1>Black Friday</h1>
                            <p>
                                We will have an unexpected flash sale "Black Friday" surprise.
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="single-hero-items set-bg" style="background-image: url('img/hero-2.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>All brand, Man, Woman, Kids</span>
                            <h1>Good Price</h1>
                            <p>
                                We sell preloved items of all brands with relatively cheap prices.
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div><div class="single-hero-items set-bg" style="background-image: url('img/hero-2.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>All brand, Man, Woman, Kids</span>
                            <h1>Good Quality</h1>
                            <p>
                                We can guarantee that all items here are good quality even if they are preloved
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </carousel>
    </section>
    <!-- Hero Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel';


    export default {
        name: 'HeroAllbrands',
        components: {
            carousel
        }
    }
    </script>