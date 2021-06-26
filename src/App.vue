<template>
  <swiper
    :slidesPerView="1"
    :slidesPerGroupSkip="1"
    :centeredSlides="false"
    :grabCursor="true"
    :breakpoints="{
      '769': {
        'slidesPerView': 2,
        'slidesPerGroup': 2,
      },
    }"
    :keyboard="{'enabled':true}"
    :pagination="{'type':'progressbar'}"
    :navigation="true"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
  >
    
    <swiper-slide><Pagina1 /></swiper-slide>
    <swiper-slide><Pagina2 /></swiper-slide>
    <swiper-slide><Pagina3 /></swiper-slide>
    <swiper-slide><Pagina4 /></swiper-slide>
    <swiper-slide><Pagina5 /></swiper-slide>
    <swiper-slide><Pagina6 /></swiper-slide>
    <swiper-slide><Pagina7 /></swiper-slide>
    <swiper-slide><Pagina8 /></swiper-slide>
    <swiper-slide><Pagina9 /></swiper-slide>
    <swiper-slide><Perceptible1 /></swiper-slide>
    <swiper-slide><Perceptible2 /></swiper-slide>
    <swiper-slide><Perceptible3 /></swiper-slide>
    <swiper-slide><Perceptible4 /></swiper-slide>
    <swiper-slide><Perceptible5 /></swiper-slide>
    <swiper-slide><Perceptible6 /></swiper-slide>
    <swiper-slide><Operable1 /></swiper-slide>
    <swiper-slide><Operable2 /></swiper-slide>
    <swiper-slide><Operable3 /></swiper-slide>
    <swiper-slide><Operable4 /></swiper-slide>
    <swiper-slide><Operable5 /></swiper-slide>
    <swiper-slide><Operable6 /></swiper-slide>
    <swiper-slide><Comprensible1 /></swiper-slide>
    <swiper-slide><Comprensible2 /></swiper-slide>
    <swiper-slide><Comprensible3 /></swiper-slide>
    <swiper-slide><Comprensible4 /></swiper-slide>
    <swiper-slide><Robusto1 /></swiper-slide>
    <swiper-slide><Robusto2 /></swiper-slide>
    <swiper-slide><Robusto3 /></swiper-slide>
    <swiper-slide><Robusto4 /></swiper-slide>
    <swiper-slide><Robusto5 /></swiper-slide>
    <swiper-slide><Robusto6 /></swiper-slide>
    <swiper-slide><Referencias /></swiper-slide>
    <swiper-slide><Referencias2 /></swiper-slide>
    <swiper-slide><Herramientas /></swiper-slide>

  </swiper>
</template>

<script>
import SwiperCore, { Pagination, Navigation, A11y, Keyboard } from 'swiper/core';
import { Swiper, SwiperSlide } from 'swiper/vue';
import Pagina1 from '@/components/Pagina1.vue';
import Pagina2 from '@/components/Pagina2.vue';
import Pagina3 from '@/components/Pagina3.vue';
import Pagina4 from '@/components/Pagina4.vue';
import Pagina5 from '@/components/Pagina5.vue';
import Pagina6 from '@/components/Pagina6.vue';
import Pagina7 from '@/components/Pagina7.vue';
import Pagina8 from '@/components/Pagina8.vue';
import Pagina9 from '@/components/Pagina9.vue';
import Perceptible1 from '@/components/Perceptible1.vue';
import Perceptible2 from '@/components/Perceptible2.vue';
import Perceptible3 from '@/components/Perceptible3.vue';
import Perceptible4 from '@/components/Perceptible4.vue';
import Perceptible5 from '@/components/Perceptible5.vue';
import Perceptible6 from '@/components/Perceptible6.vue';
import Operable1 from '@/components/Operable1.vue';
import Operable2 from '@/components/Operable2.vue';
import Operable3 from '@/components/Operable3.vue';
import Operable4 from '@/components/Operable4.vue';
import Operable5 from '@/components/Operable5.vue';
import Operable6 from '@/components/Operable6.vue';
import Comprensible1 from '@/components/Comprensible1.vue';
import Comprensible2 from '@/components/Comprensible2.vue';
import Comprensible3 from '@/components/Comprensible3.vue';
import Comprensible4 from '@/components/Comprensible4.vue';
import Robusto1 from '@/components/Robusto1.vue';
import Robusto2 from '@/components/Robusto2.vue';
import Robusto3 from '@/components/Robusto3.vue';
import Robusto4 from '@/components/Robusto4.vue';
import Robusto5 from '@/components/Robusto5.vue';
import Robusto6 from '@/components/Robusto6.vue';
import Referencias from '@/components/Referencias.vue';
import Referencias2 from '@/components/Referencias2.vue';
import Herramientas from '@/components/Herramientas.vue';

import 'swiper/swiper.scss';
import "swiper/components/pagination/pagination.min.css";
import "swiper/components/navigation/navigation.min.css";

SwiperCore.use([Pagination, Navigation, A11y, Keyboard]);

export default {
  name: 'App',
  components: {
    Swiper,
    SwiperSlide,
    Pagina1,
    Pagina2,
    Pagina3,
    Pagina4,
    Pagina5,
    Pagina6,
    Pagina7,
    Pagina8,
    Pagina9,

    Perceptible1,
    Perceptible2,
    Perceptible3,
    Perceptible4,
    Perceptible5,
    Perceptible6,

    Operable1,
    Operable2,
    Operable3,
    Operable4,
    Operable5,
    Operable6,

    Comprensible1,
    Comprensible2,
    Comprensible3,
    Comprensible4,

    Robusto1,
    Robusto2,
    Robusto3,
    Robusto4,
    Robusto5,
    Robusto6,
    
    Referencias,
    Referencias2,
    Herramientas,
  },
  methods: {
    onSwiper(swiper) {
      console.log(swiper);
    },
    onSlideChange() {
      console.log('slide change');
    },
  },
}
</script>

<style>
html,
body {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: sans-serif;
  font-size: 18px;
  height: 100%;
  width: 100%;
  overflow: hidden;
  position: relative;
  background: #d3d1ff;
  color: #222;
}
ul, ol {
  padding-left: 0;
  list-style-position: inside;
}
li {
  padding: 10px 0;
}
#presentacion,
.swiper-container,
.swiper-wrapper {
  height: 100%;
  box-sizing: border-box;
}
.swiper-slide {
  box-sizing: border-box;
  padding: 2vh 7vw;
}

@media only screen and (min-width: 769px) {
  .swiper-slide {
    padding: 12vh 7vw;
  }
  .swiper-slide:first-child {
    transition: transform 100ms;
  }
  .swiper-slide.swiper-slide-active:first-child {
    transform: translateX(50%);
    z-index: 2;
  }
  .swiper-slide:nth-child(2) {
    transition: transform 100ms;
  }
  .swiper-slide.swiper-slide-next:nth-child(2) {
    transform: translateX(100%);
    z-index: 1;
  }
}
</style>
