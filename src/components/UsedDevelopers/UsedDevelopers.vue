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
    <div class="UsedDevelopers__icons">
      <div class="UsedDevelopers__icon1">
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/1.svg" alt="1"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/2.svg" alt="2"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/3.svg" alt="3"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/4.svg" alt="4"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/5.svg" alt="5"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/6.svg" alt="6"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/7.svg" alt="7"
        /></router-link>
      </div>

      <div class="UsedDevelopers__icon2">
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/8.svg" alt="8"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/9.svg" alt="9"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/10.svg" alt="10"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/11.svg" alt="11"
        /></router-link>
        <router-link to="/"
          ><img src="@/assets/UsedDevelopers/12.svg" alt="12"
        /></router-link>
      </div>
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
