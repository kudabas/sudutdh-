<template>
  <div class="gps">
    <div>
      <HomeGPS />
      <FiturGPS />
      <PendukungGPS />
      <RekomendasiGPS />
      <PenawaranGPS />
      <MengapaGPS />
      <ProductGPS />
      <KonsulGPS />
      <FooterDigdaya />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import '@/assets/tailwind.css';
import HomeGPS from '@/components/gps/HomeGPS.vue';
import FooterDigdaya from '@/components/FooterDigdaya.vue';
import FiturGPS from '@/components/gps/FiturGPS.vue';
import PendukungGPS from '@/components/gps/PendukungGPS.vue';
import RekomendasiGPS from '@/components/gps/RekomendasiGPS.vue';
import PenawaranGPS from '@/components/gps/PenawaranGPS.vue';
import MengapaGPS from '@/components/gps/MengapaGPS.vue';
import KonsulGPS from '@/components/gps/KonsulGPS.vue';
import ProductGPS from '@/components/gps/ProductGPS.vue';

export default {
  name: 'HomeView',
  components: {
    HomeGPS,
    FiturGPS,
    PendukungGPS,
    RekomendasiGPS,
    PenawaranGPS,
    MengapaGPS,
    KonsulGPS,
    ProductGPS,
    FooterDigdaya
  }
}
</script>