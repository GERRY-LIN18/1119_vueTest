<template>
  <div class="about">
    <h1>This is an ProductViewage</h1>
  </div>
    <Carousel v-model="value" loop>
      <CarouselItem>
        <div class="demo-carousel">
          <BigPicture :imgurl="2"></BigPicture>
        </div>
      </CarouselItem>
      <CarouselItem>
        <div class="demo-carousel">
          <BigPicture :imgurl="2"></BigPicture>
        </div>
      </CarouselItem>
      <CarouselItem>
        <div class="demo-carousel">
          <BigPicture :imgurl="3"></BigPicture>
        </div>
      </CarouselItem>
      <CarouselItem>
        <div class="demo-carousel">
          <BigPicture :imgurl="4"></BigPicture>
        </div>
      </CarouselItem>
    </Carousel>


</template>
<script>
import BigPicture from '@/components/BigPicture.vue'



// @ is an alias to /src

export default {
  name: 'ProductView',
  components: {
    BigPicture
  }
}
</script>