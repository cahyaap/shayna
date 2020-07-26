<template>
  <div class="partner-logo">
    <div class="container">
      <Carousel class="logo-carousel" :loop="true" :nav="false" :items="5" :dots="false" :autoplay="true">
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-1.png" alt />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-2.png" alt />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-3.png" alt />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-4.png" alt />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-5.png" alt />
          </div>
        </div>
      </Carousel>
    </div>
  </div>
</template>

<script>
import Carousel from 'vue-owl-carousel';
export default {
    name: 'HomePartners',
    components: {
        Carousel
    }
}
</script>