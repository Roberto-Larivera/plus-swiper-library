<script>

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';
import 'swiper/css/navigation';

import { Navigation } from 'swiper';

export default {
  name: 'SecondTry',
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Navigation],
    };
  },
  data() {
    return {

    }
  },


}
</script>

<template>
  <div class="container p-5">
    <div class="row">
      <div class="col text-center">
        <h2>
         Second Carousel - Navigation
        </h2>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <swiper class="mySwiper" :navigation="true" :modules="modules">
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="w-100 h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
        </swiper>
      </div>
    </div>

  </div>
</template>

<style lang="scss" scoped>
.mySwiper {
  background-color: lightcoral;
  width: 600px;
  height: 300px;
}

img {
  height: 100%;
}
</style>
