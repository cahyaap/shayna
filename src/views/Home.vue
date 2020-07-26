<template>
  <div class="home">
    <Header />
    <Hero />
    <HomeSlider />
    <HomeGallery />
    <HomePartners />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import HomeSlider from "@/components/HomeSlider.vue";
import HomeGallery from "@/components/HomeGallery.vue";
import HomePartners from "@/components/HomePartners.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    HomeSlider,
    HomeGallery,
    HomePartners,
    Footer
  }
};
</script>
