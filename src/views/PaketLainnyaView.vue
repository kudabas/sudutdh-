<template>
  <div class="paketlain">
    <div class="pt-[50px] lg:pt-0">
      <HomeCCTV />
      <TabPaket />
      <FooterDigdaya />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import '@/assets/tailwind.css';
import HomeCCTV from "@/components/cctv/HomeCCTV.vue";
import TabPaket from "@/components/cctv2/TabPaket.vue"
import FooterDigdaya from "@/components/FooterDigdaya.vue";

export default {
  name: 'HomeView',
  components: {
    HomeCCTV,
    TabPaket,
    FooterDigdaya
  }
}
</script>