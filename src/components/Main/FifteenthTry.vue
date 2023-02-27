<script>

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';
import 'swiper/css/pagination';
import 'swiper/css/free-mode';

// import 'swiper/css/navigation';

import { Keyboard, Mousewheel, Pagination, Navigation, FreeMode } from 'swiper';

export default {
  name: 'FifteenthTry',
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination, Navigation, Mousewheel, Keyboard, FreeMode],
    };
  },
  data() {
    return {

    }
  },


}
</script>

<template>
  <div id="FifteenthTry" class="container p-5">
    <div class="row">
      <div class="col text-center">
        <h2>
          FifteenthTry Carousel - FreeMode
        </h2>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <swiper 
          class="mySwiper" 
          :freeMode="true"
          :mousewheel="true"
          :keyboard="true"
          :slidesPerView="2"
          :pagination="{
            clickable: true
          }" 
          :modules="modules"
        >
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
          <swiper-slide class="h-100">
            <img src="https://picsum.photos/600/300" alt="">
          </swiper-slide>
        </swiper>
      </div>
    </div>

  </div>
</template>

<style lang="scss">
// rimuoviamo il scoped è inseriamo tutto dentro un id così che crea problemi
//si deve aggiungere la parte css già pronta volendo dentro le demo
// in questo caso rimuovere w-100 per far si che le classi vngono aggiunte correttamente dalla libreria
#FifteenthTry{
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
