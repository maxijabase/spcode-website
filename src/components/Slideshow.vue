<template>
  <Carousel :autoplay="3000" :wrap-around="true">

    <Slide v-for="slide in 2" :key="slide">
      <div class="carousel__item">
        <img src="https://i.imgur.com/Zr5NZ1B.png" class="" style="width:100%">
      </div>
    </Slide>

    <template #addons>
    </template>
  </Carousel>
</template>

<script>
import { Carousel, Slide } from 'vue3-carousel';
import 'vue3-carousel/dist/carousel.css';

export default {
  components: {
    Carousel,
    Slide
  },
}
</script>

<style>

.carousel__viewport {
  background-color: #252525;
}

.carousel__item {
  min-height: 200px;
  background-color: #252525;
  display: flex;
  justify-content: center;
  align-items: center;
}

</style>