<template>
    <div id="hero">
        <div class="pt-[100px] lg:pt-atas 2xl:px-60 flex-container bg-blog bg-cover">
            <div class="flex flex-wrap text-center">
                <div class="w-full my-[300px] ">
                    <h1 class="font-bold text-bodas text-xxl mx-auto">
                        BLOGS
                    </h1>
                </div>
            </div>
        </div>
        <div class="flex-container pt-[100px] 2xl:px-60">
            <div class="grid grid-cols-2 gap-4 mb-4 lg:grid-cols-3 lg:gap-9 lg:mb-9">
                <div class="flex justify-end">
                    <router-link to="/kasi" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/About.png" alt="catra" class="w-[460px] transform hover:scale-105 duration-300" />
                </button>
                </router-link>
                </div>
                <div class="flex justify-center">
                    <router-link to="/ijesssb" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/IJESSSs.png" alt="catra" class="max-w-full transform hover:scale-105 duration-300" />
                    </button>
                    </router-link>
                </div>
                <div class="flex justify-start">
                    <router-link to="/ahjpmb" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/AHJPMm.png" alt="catra" class="max-w-full transform hover:scale-105 duration-300" />
                </button>
                </router-link>
                </div>
                <div class="flex justify-end">
                    <router-link to="/jtepb" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/JTEP.png" alt="catra" class="max-w-full transform hover:scale-105 duration-300" />
                </button>
                </router-link>
                </div>
                <div class="flex justify-center">
                    <router-link to="/pjlelb" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/PJLEL.png" alt="catra" class="max-w-full transform hover:scale-105 duration-300" />
                </button>
                </router-link>
                </div>
                <div class="flex justify-start">
                    <router-link to="/jogtab" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/JOGTA.png" alt="catra" class="max-w-full transform hover:scale-105 duration-300" />
                </button>
                </router-link>
                </div>
                
            </div>
            <div class="grid grid-cols-2 gap-4 lg:grid-cols-2 lg:gap-9 lg:px-60 mb-16">
                <div class="flex justify-end">
                    <router-link to="/jibbb" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/JIBBb.png" alt="catra" class="max-w-full transform hover:scale-105 duration-300" />
                </button>
                </router-link>
                </div>
                <div class="flex justify-center">
                    <router-link to="/jisb" custom v-slot="{ navigate }">
                        <button @click="navigate" role="link">
                    <img src="@/assets/journal/JISDB.png" alt="catra" class="max-w-full transform hover:scale-105 duration-300" />
                </button>
                </router-link>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
import "@/assets/tailwind.css";

export default {};
</script>
  
<style></style>