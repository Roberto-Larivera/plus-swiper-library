<script>

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';
import 'swiper/css/pagination';

import { Pagination } from 'swiper';

export default {
  name: 'ThenthTry',
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination],
    };
  },
  data() {
    return {

    }
  },


}
</script>

<template>
  <div id="thenth-try" class="container p-5">
    <div class="row">
      <div class="col text-center">
        <h2>
          ThenthTry Carousel - Space Between
        </h2>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <swiper class="mySwiper" :spaceBetween="30" :pagination="{
          clickable: true
        }" :modules="modules">
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

<style lang="scss">
// rimuoviamo il scoped ?? inseriamo tutto dentro un id cos?? che crea problemi
//si deve aggiungere la parte css gi?? pronta volendo dentro le demo

#thenth-try{
  .mySwiper {
  background-color: lightcoral;
  width: 600px;
  height: 300px;
}

img {
  height: 100%;
}
}
.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;

  /* Center slide text vertically */
  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
