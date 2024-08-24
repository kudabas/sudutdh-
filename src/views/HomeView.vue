<template>
  <div class="home">
    <div class="lg:pt-[70px]">
      <HomeDigdaya/>
      <AboutUs/>
      <WhyUs/>
      <OurService/>
      <OurProduct/>
      <OurClient/>
      <MariKonsul/>
      <FooterDigdaya/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import '@/assets/tailwind.css';
import HomeDigdaya from '@/components/HomeDigdaya.vue';
import AboutUs from '@/components/AboutUs.vue';
import WhyUs from '@/components/WhyUs.vue';
import OurService from '@/components/OurService.vue';
import OurProduct from '@/components/OurProduct.vue';
import OurClient from '@/components/OurClient.vue';
import MariKonsul from '@/components/MariKonsul.vue';
import FooterDigdaya from '@/components/FooterDigdaya.vue';


export default {
  name: 'HomeView',
  components: {
    HomeDigdaya,
    AboutUs,
    WhyUs,
    OurService,
    OurProduct,
    OurClient,
    MariKonsul,
    FooterDigdaya

}
}
</script>
