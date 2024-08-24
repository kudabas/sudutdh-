<template>
  <div class="ac">
    <div>
      <HomeAC />
      <RekomAC />
      <PaketAC />
      <MengapaAC />
      <ProductAC />
      <KonsulAC />
      <FooterDigdaya />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import '@/assets/tailwind.css';
import HomeAC from '@/components/ac/HomeAC.vue';
import FooterDigdaya from '@/components/FooterDigdaya.vue';
import RekomAC from '@/components/ac/RekomAC.vue';
import PaketAC from '@/components/ac/PaketAC.vue';
import MengapaAC from '@/components/ac/MengapaAC.vue';
import ProductAC from '@/components/ac/ProductAC.vue';
import KonsulAC from '@/components/ac/KonsulAC.vue';

export default {
  name: 'HomeView',
  components: {
    HomeAC,
    RekomAC,
    PaketAC,
    MengapaAC,
    ProductAC,
    KonsulAC,
    FooterDigdaya
  }
}
</script>