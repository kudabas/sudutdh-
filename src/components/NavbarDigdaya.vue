<template>
  <div class="font-Montserrat" id="app">
    <nav class="fixed w-full z-10 top-0 shadow-xl flex items-center justify-between flex-wrap bg-light px-4 2xl:px-48">
      <div class="flex items-center flex-no-shrink text-blue mr-6 pt-2 pb-2">
        <a href="https://sudutdh.com/">
          <img src="@/assets/logoDig.png" width="200" alt="logo" />
        </a>
      </div>
      <div class="block sm:hidden">
        <button @click="toggle"
          class="flex items-center px-3 py-2 border rounded text-teal-lighter border-teal-light hover:text-white hover:border-white">
          <svg class="fill-current h-3 w-3 bg-primary" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>
      <div :class="open ? 'block' : 'hidden'" class="w-full items-center text-center sm:flex sm:w-auto">
        <div class="text-sm sm:flex-grow pt-2">
          <router-link to="/" custom v-slot="{ navigate }">
            <button @click="navigate" role="link">
              <a class="no-underline block mt-4 sm:inline-block sm:mt-0 text-gray-600 hover:text-primary mr-4">Home</a>
            </button>
          </router-link>
          <a href="#aboutu"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-gray-600 hover:text-primary mr-4">
            About Us
          </a>
          <a href="#why"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-gray-600 hover:text-primary mr-4">Why Us</a>
          <a href="#service"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-gray-600 hover:text-primary mr-4">Our
            Service</a>
            <a href="https://wa.me/6283131462238"
            class="no-underline block mt-4 sm:inline-block sm:mt-0 text-gray-600 hover:text-primary mr-4">Consultation</a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
import "@/assets/tailwind.css";

export default {
  data() {
    return { open: false };
  },
  methods: {
    toggle() {
      this.open = !this.open;
    }
  }
};
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>