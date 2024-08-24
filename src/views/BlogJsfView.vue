<template>
    <div class="jsfb">
      <div>
        <jsfBlogs/>
        <FooterDigdaya/>
      </div>
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import '@/assets/tailwind.css';
  import jsfBlogs from '@/components/blog/jsfBlogs.vue';
  import FooterDigdaya from '@/components/FooterDigdaya.vue';
  
  export default {
    name: 'HomeView',
    components: {
      jsfBlogs,
      FooterDigdaya
  }
  }
  </script>