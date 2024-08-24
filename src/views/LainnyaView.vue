<template>
  <div class="lainnya">
    <div>
      <HomeLainnya />
      <RekomLainnya />
      <PenawaranLainnya />
      <MengapaLainnya />
      <ProductLainnya />
      <KonsulLainnya />
      <FooterDigdaya />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import '@/assets/tailwind.css';
import FooterDigdaya from '@/components/FooterDigdaya.vue';
import HomeLainnya from '../components/lainnya/HomeLainnya.vue';
import RekomLainnya from '@/components/lainnya/RekomLainnya.vue';
import PenawaranLainnya from '@/components/lainnya/PenawaranLainnya.vue';
import MengapaLainnya from '@/components/lainnya/MengapaLainnya.vue';
import ProductLainnya from '@/components/lainnya/ProductLainnya.vue';
import KonsulLainnya from '@/components/lainnya/KonsulLainnya.vue';

export default {
  name: 'HomeView',
  components: {
    HomeLainnya,
    RekomLainnya,
    PenawaranLainnya,
    MengapaLainnya,
    ProductLainnya,
    KonsulLainnya,
    FooterDigdaya
  }
}
</script>