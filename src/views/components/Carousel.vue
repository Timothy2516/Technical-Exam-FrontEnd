<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
        <b-carousel id="carousel1"
>
                            <!-- Text slides with image -->
                            <b-carousel-slide img-src="https://super7tech.com/web_developer_exam_sr/layout/images/OLE777_OCT_31.webp"></b-carousel-slide>
                            <b-carousel-slide img-src="https://super7tech.com/web_developer_exam_sr/layout/images/slide_two.png"></b-carousel-slide>.
                            <b-carousel-slide img-src="https://super7tech.com/web_developer_exam_sr/layout/images/slide_three.png"></b-carousel-slide>
                        </b-carousel>
    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: {
    BCarousel,
    BCarouselSlide
  },
};
</script>
<style>
</style>
