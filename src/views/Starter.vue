<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
    <div class="shape shape-style-1 shape-default shape-skew">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
    </div>    
    <div class="container py-0 pb-lg">
        <div class="row justify-content-between align-items-center">
            <div class="col-lg-6 mb-lg-auto">
                <div class="rounded shadow-lg overflow-hidden">
                    <b-carousel id="carousel1"
                                controls
                                indicators>
                        <!-- Text slides with image -->
                        <b-carousel-slide img-src="img/theme/img-1-1200x1000.jpg"></b-carousel-slide>
                        <b-carousel-slide img-src="img/theme/img-2-1200x1000.jpg"></b-carousel-slide>
                    </b-carousel>
                </div>
            </div>
            <div class="col-lg-6 mb-lg-auto">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Soluta sed beatae atque vitae obcaecati cumque magni officiis, earum, cum praesentium suscipit distinctio fugiat, consectetur odio dicta a temporibus quo consequuntur!
            </div>    
        </div>
    </div>
    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: {
    BCarousel,
    BCarouselSlide
  }
};
</script>
<style>
</style>
