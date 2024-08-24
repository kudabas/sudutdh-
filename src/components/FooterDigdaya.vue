<template>
  <div id="footer">
    <div
      class="pt-[20px] lg:pt-[0px] 2xl:px-40 flex-container bg-gradient-to-r from-[#FFFFFF] from-35% to-[#FB6003] to-65%">
      <div class="p-3 flex flex-wrap">
        <div class="w-full self-start lg:w-1/4">
          <div class="mt-5 lg:mt-20">
            <img src="../assets/logoDig.png" alt="catra" class=" max-w-full ml-0 mb-5 lg:mx-auto" width="250" />
          </div>
          <div class="flex justify-start lg:justify-end pl-0 pr-0 lg:pl-10 lg:pr-20">
            <div class>
            
                <img src="../assets/faceb.png" alt="catra"
                  class="rounded-[20px] ml-0 lg:ml-10 max-w-full transform hover:scale-125 duration-300" />
            </div>
            <div class>
              <a href="https://www.instagram.com/sd_harmoni/" target="_blank">
                <img src="../assets/insta.png" alt="catra"
                  class="rounded-[20px] ml-0 lg:ml-10 max-w-full transform hover:scale-125 duration-300" />
              </a>
            </div>
            <div class>
              <a href="https://wa.me/6283131462238" target="_blank">
                <img src="../assets/whats.png" alt="catra"
                  class="rounded-[20px] ml-0 lg:ml-10 max-w-full transform hover:scale-125 duration-300" />
              </a>
            </div>
          </div>
          <div class="grid grid-cols-4 lg:grid-cols-3">

          </div>
        </div>
        <div class="w-full self-start ml-0 mt-4 lg:w-1/6">
          <div class="mt-10 lg:mt-20">
            <h1 class="text-md text-abhu2 font-bold mb-5">Our Service</h1>
            <h1>
              <router-link to="/cctv" custom v-slot="{ navigate }">
                <button @click="navigate" role="link">
                  <a
                    class="text-base text-abhu2 transition duration-100 ease-in-out hover:text-primary">CCTV</a></button>
              </router-link>
            </h1>
            <h1>
              <router-link to="/gps" custom v-slot="{ navigate }">
                <button @click="navigate" role="link">
                  <a class="text-base text-abhu2 transition duration-100 ease-in-out hover:text-primary">GPS (tracker)
                    Kendaraan</a></button>
              </router-link>
            </h1>
            <h1>
              <router-link to="/ac" custom v-slot="{ navigate }">
                <button @click="navigate" role="link">
                  <a class="text-base text-abhu2 transition duration-100 ease-in-out hover:text-primary">AC Mobil &
                    Ruangan</a></button>
              </router-link>
            </h1>
            <h1>
              <router-link to="/lainnya" custom v-slot="{ navigate }">
                <button @click="navigate" role="link">
                  <a class="text-base text-abhu2 transition duration-100 ease-in-out hover:text-primary">Keamanan
                    Digital Lainnya</a></button>
              </router-link>
            </h1>
          </div>
        </div>
        <div class="w-full self-start px-0 mt-4 lg:w-2/6">
          <div class="mt-10 ml-0 lg:ml-0 lg:mt-20">
            <h1 class="text-md text-abhu2 font-bold mb-5">Contact</h1>
            <h1 class="mb-3 text-base text-abhu2">
              <img src="../assets/pin.png" alt="catra" class="inline h-[25px] mr-4" />Jl. Bojong Koneng No.32,
              RT.05/RW.12, 
              <span class="block ml-[38px]">Sukapada, Kec.Cibeunying Kidul,  </span>
              <span class="block ml-[38px]">Kab.Bandung, Jawa Barat 40125</span>
            </h1>
            <h1 class="mb-3 text-base text-abhu2">
              <img src="../assets/mail.png" alt="catra" class="inline h-[25px] mr-4" />Suduttechnology@gmail.com
            </h1>
            <h1 class="mb-1 text-base text-abhu2">
              <img src="../assets/phone.png" alt="catra" class="inline h-[25px] mr-4" />+62 831-3146-2238
            </h1>
          </div>
        </div>
        <div class="w-full self-start pl-0 mt-4 lg:w-1/4">
          <div class="mt-10 lg:mt-20">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3960.9797276837967!2d107.6418135758128!3d-6.893027967455005!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e68efe8d31e2239%3A0x18f95d5ad826cdba!2sCV%20Sudut%20Digdaya%20Harmoni!5e0!3m2!1sen!2sid!4v1712208227737!5m2!1sen!2sid"
              class="rounded-lg" width="320" height="200" style="border:0;" allowfullscreen="" loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"></iframe>
            <div class="text-left lg:text-right">
              <h1 class="mt-3">Shop NOW !</h1>
              <div class="flex justify-start lg:justify-end">
                <div class="">
                    <img src="../assets/sopii.png" alt="catra"
                      class=" max-w-full ml-0 mb-5 lg:mx-auto transform hover:scale-125 duration-300" width="50" />
                </div>
                <div class="">
                  <a href="https://tokopedia.link/xFcACNvlkIb" target="_blank">
                    <img src="../assets/tokped.png" alt="catra"
                    class=" max-w-full ml-0 mb-5 lg:mx-auto transform hover:scale-125 duration-300" width="50" />
                  </a>
               
                </div>
                <div class="">
                  <a href="https://www.olx.co.id/profile/115232213" target="_blank">
                    <img src="../assets/olx.png" alt="catra"
                      class=" max-w-full ml-0 mb-5 lg:mx-auto transform hover:scale-125 duration-300" width="50" />
                  </a>
                </div>
              </div>

            </div>
          </div>
        </div>
        <hr class="w-[1221px] h-[1px] mx-auto mt-10 mb-5 border-0 bg-abhu2" />
      </div>
      <a
         class="text-base text-center text-abhu2 transition duration-100 ease-in-out hover:underline">
        <h2 class="mb-1">Copyright © 2024 CV. Sudut Digdaya Harmoni</h2>
      </a>
      <br />
    </div>

    <!-- <div class="bg-cover bg-center bg-no-repeat h-[700px] bg-cats pt-0">
        <div class="grid grid-cols-2 gap-10 pt-15 h-[700px]">
          <div class="text-left p-60">
            <p class="text-4xl font-extrabold">
              SCIENTIFICS
              <a class="text-primary">RESEARCH</a>
            </p>
            <p class="text-4xl font-extrabold">
              JOURNAL
            </p>
            <a href="https://api.whatsapp.com/send/?phone=6281120011644&text&type=phone_number&app_absent=0">
            <button
              type="button"
              class="text-bodas bg-primary hover:bg-blue-800 focus:outline-none focus:ring-4 focus:ring-blue-300 font-medium rounded-full text-sm px-5 py-2.5 text-center mr-2 mb-2 dark:bg-primary dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >Consultation NOW !</button>
          </a>
          </div>
          <div class="place-content-center">
            <div class>
              <img class="h-[629px] w-[629px]" src="../assets/home1.png" alt="homie" />
            </div>
          </div>
        </div>
    </div>-->
  </div>
</template>

<script>
import "@/assets/tailwind.css";

export default {};
</script>

<style></style>