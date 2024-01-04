<template>
  <div class="UsedDevelopers">
    <div class="UsedDevelopers__title">Used by 400,000+ developers.</div>
    <div class="UsedDevelopers__swiper">
      <swiper :slides-per-view="3" :space-between="50">
        <swiper-slide
          ><router-link to="/"><SwiperSlide1 /></router-link
        ></swiper-slide>
        <swiper-slide
          ><router-link to="/"><SwiperSlide2 /></router-link
        ></swiper-slide>
        <swiper-slide
          ><router-link to="/"><SwiperSlide3 /></router-link
        ></swiper-slide>
        <swiper-slide
          ><router-link to="/"><SwiperSlide4 /></router-link
        ></swiper-slide>
        <swiper-slide
          ><router-link to="/"><SwiperSlide5 /></router-link
        ></swiper-slide>
      </swiper>
    </div>
  </div>
</template>

<script>
import SwiperSlide1 from "@/ui/SwiperSlide1.vue";
import SwiperSlide2 from "@/ui/SwiperSlide2.vue";
import SwiperSlide3 from "@/ui/SwiperSlide3.vue";
import SwiperSlide4 from "@/ui/SwiperSlide4.vue";
import SwiperSlide5 from "@/ui/SwiperSlide5.vue";
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";

export default {
  components: {
    Swiper,
    SwiperSlide,
    SwiperSlide1,
    SwiperSlide2,
    SwiperSlide3,
    SwiperSlide4,
    SwiperSlide5,
  },
};
</script>

<style lang="scss" scoped>
@import "@/components/UsedDevelopers/UsedDevelopers.scss";
</style>
