<template>
  <div class="cctv">
    <div class="pt-[30px] lg:pt-[70px]">
      <HomeCCTV />
      <RecomCCTV />
      <ProductCCTV />
      <PenawaranCCTV />
      <KeunggulanCCTV />
      <KonsulCCTV/>
      <ClientCCTV/>
      <FooterDigdaya />
    </div>
  </div>
</template>
  
  <script>
// @ is an alias to /src
import "@/assets/tailwind.css";
import HomeCCTV from "@/components/cctv/HomeCCTV.vue";
import FooterDigdaya from "@/components/FooterDigdaya.vue";
import RecomCCTV from "@/components/cctv/RecomCCTV.vue";
import ProductCCTV from "@/components/cctv/ProductCCTV.vue";
import PenawaranCCTV from "@/components/cctv/PenawaranCCTV.vue";
import KeunggulanCCTV from "@/components/cctv/KeunggulanCCTV.vue";
import KonsulCCTV from "@/components/cctv/KonsulCCTV.vue";
import ClientCCTV from "@/components/cctv/ClientCCTV.vue";

export default {
  name: "CctvView",
  components: {
    HomeCCTV,
    RecomCCTV,
    ProductCCTV,
    PenawaranCCTV,
    KeunggulanCCTV,
    KonsulCCTV,
    ClientCCTV,
    FooterDigdaya
  }
};
</script>