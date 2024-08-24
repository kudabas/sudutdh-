<template>
    <div class="bg-abhu3 rounded-xl">
    <TabGroup>
        <TabList class="flex space-x-1 rounded-xl bg-bodas p-1">
        <div class="text-center mx-auto">
            <Tab class="p-3 ring-white/60 ring-offset-2 ring-offset-primary focus:outline-none focus:ring-2 rounded-xl hover:bg-bodas">Tab 1</Tab>
            <Tab class="p-3 ">Tab 2</Tab>
            <Tab class="p-3 ">Tab 3</Tab>
            <Tab class="p-3 ">Tab 4</Tab>
            <Tab class="p-3 ">Tab 5</Tab>
            <Tab class="p-3 ">Tab 6</Tab>
            <Tab class="p-3 ">Tab 7</Tab>
        </div>

        </TabList>
        <TabPanels>
            <TabPanel>
                <div class="mx-3 2xl:px-40 lg:pb-20">
                    <div class="mb-10 text-center pt-0">
                        <h1 class="mb-0 text-lg text-center font-bold">Penawaran Terbaik Paket CCTV</h1>
                        <h2 class="text-base text-abhu font-light">Rincian paket pemasangan kamera cctv lengkap siap
                            pasang</h2>
                    </div>
                    <div class="lg:px-16 text-center grid justify-items-center grid-cols-2 gap-4 lg:grid-cols-3 pb-5">
                        <div
                            class="bg-light border-solid border-4 border-primary block max-w-[500px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[350px] lg:h-[680px]">
                            <div class="p-3">
                                <h1 class="text-center mb-5 text-md font-bold leading-tight text-hideung">2 Camera 2mp
                                </h1>
                                <img src="@/assets/product/pcctv1.png" alt="catra"
                                    class="inline h-[120px] lg:h-[180px] mb-5" />
                                <div class="bg-bodas rounded-[10px] p-2 mb-5">
                                    <h1 class="text-left font-light text-sm text-abhu mb-3">
                                        Isian Paket Pemasangan CCTV 2 CH
                                        Lengkap
                                        .
                                    </h1>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>- DVR DAHUA 2MP 4CH 1 UNIT</h2>
                                        <h2>- CAM DAHUA 2MP ANALOG 2 UNIT</h2>
                                        <h2>- HARDDISK 500 GB 1 UNIT</h2>
                                        <h2>- PS JARING 10 A 1 UNIT</h2>
                                        <h2>- KONEKTOR CCTV LENGKAP</h2>
                                    </div>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>FREE</h2>
                                        <h2>- KABEL CCTV RG59 50 METER</h2>
                                        <h2>- KABEL LAN 5M + RJ 45 2PCS</h2>
                                        <h2>- KLEM, ISOLASI,KABEL TIES LENGKAP</h2>
                                        <h2>- ALAT LISTRIK LENGKAP</h2>
                                        <h2>- JASA INSTALASI</h2>
                                        <h2>- JASA SETTING DAN TRAINING LENGKAP</h2>
                                    </div>
                                    <h2 class="text-left text-sm font-bold mb-3">GARANSI DAHUA 1 TAHUN & JASA TEKNISI 3
                                        BULAN
                                    </h2>
                                </div>
                                <div class="">
                                    <a href="https://wa.me/6283131462238"
                                        class="transition duration-300 ease-in-out hover:bg-oren text-primary border-2 border-primary font-bold bg-bodas py-1 px-3 lg:py-3 lg:px-12 rounded-xl">Pilih
                                        Paket !</a>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-light border-solid border-4 border-primary block max-w-[500px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[350px] lg:h-[680px]">
                            <div class="p-3">
                                <h1 class="text-center mb-5 text-md font-bold leading-tight text-hideung">4 kamera 2mp
                                </h1>
                                <img src="@/assets/product/pcctv2.png" alt="catra"
                                    class="inline h-[120px] lg:h-[180px] mb-5" />
                                <div class="bg-bodas rounded-[10px] p-2 mb-5">
                                    <h1 class="text-left font-light text-sm text-abhu mb-3">
                                        Isian Paket Pemasangan CCTV 4 CH Lengkap
                                        .
                                    </h1>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>- DVR HIKVISION 2MP 4CH 1 UNIT</h2>
                                        <h2>- CAM HIKVISION 2MP ANALOG 4 UNIT</h2>
                                        <h2>- HARDDISK 500 GB 1 UNIT</h2>
                                        <h2>- PS JARING 10 A 1 UNIT</h2>
                                        <h2>- KONEKTOR CCTV LENGKAP</h2>
                                    </div>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>FREE</h2>
                                        <h2>- KABEL CCTV RG59 80 METER</h2>
                                        <h2>- KABEL LAN 5M + RJ 45 2PCS</h2>
                                        <h2>- KLEM, ISOLASI,KABEL TIES LENGKAP</h2>
                                        <h2>- ALAT LISTRIK LENGKAP</h2>
                                        <h2>- JASA INSTALASI</h2>
                                        <h2>- JASA SETTING DAN TRAINING LENGKAP</h2>
                                    </div>
                                    <h2 class="text-left text-sm font-bold mb-3">GARANSI HIKVISION 1 TAHUN & JASA
                                        TEKNISI 3 BULAN
                                    </h2>
                                </div>
                                <div class>
                                    <router-link to="/gps" custom v-slot="{ navigate }">
                                        <button @click="navigate" role="link">
                                            <a
                                                class="transition duration-300 ease-in-out hover:bg-oren text-primary border-2 border-primary font-bold bg-bodas py-1 px-3 lg:py-3 lg:px-12 rounded-xl">
                                                Pilih Paket !
                                            </a>
                                        </button>
                                    </router-link>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-light border-solid border-4 border-primary block max-w-[500px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[350px] lg:h-[680px]">
                            <div class="p-3">
                                <h1 class="text-center mb-5 text-md font-bold leading-tight text-hideung">8 Camera 2mp
                                </h1>
                                <img src="@/assets/product/pcctv3.png" alt="catra"
                                    class="inline h-[120px] lg:h-[180px] mb-5" />
                                <div class="bg-bodas rounded-[10px] p-2 mb-5">
                                    <h1 class="text-left font-light text-sm text-abhu mb-3">
                                        Isian Paket Pemasangan CCTV 8 CH
                                        Lengkap
                                        .
                                    </h1>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>- DVR HILOOK 2MP 4CH 1 UNIT</h2>
                                        <h2>- CAM HILOOK 2MP ANALOG 8 UNIT</h2>
                                        <h2>- HARDDISK 1000 GB 1 UNIT</h2>
                                        <h2>- PS JARING 10 A 1 UNIT</h2>
                                        <h2>- KONEKTOR CCTV LENGKAP</h2>
                                    </div>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>FREE</h2>
                                        <h2>- KABEL CCTV RG59 150 METER</h2>
                                        <h2>- KABEL LAN 5M + RJ 45 2PCS</h2>
                                        <h2>- KLEM, ISOLASI,KABEL TIES LENGKAP</h2>
                                        <h2>- ALAT LISTRIK LENGKAP</h2>
                                        <h2>- JASA INSTALASI</h2>
                                        <h2>- JASA SETTING DAN TRAINING LENGKAP</h2>
                                    </div>
                                    <h2 class="text-left text-sm font-bold mb-3">GARANSI HILOOK 1 TAHUN & JASA TEKNISI 3
                                        BULAN
                                    </h2>
                                </div>
                                <div class>
                                    <router-link to="/gps" custom v-slot="{ navigate }">
                                        <button @click="navigate" role="link">
                                            <a
                                                class="transition duration-300 ease-in-out hover:bg-primary hover:text-bodas text-primary border-2 border-primary font-bold bg-bodas py-1 px-3 lg:py-3 lg:px-12 rounded-xl">
                                                lihat
                                                Paket !
                                            </a>
                                        </button>
                                    </router-link>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="lg:px-16 text-center grid justify-items-center grid-cols-2 gap-4 lg:grid-cols-3 pb-5">
                        <div
                            class="bg-light border-solid border-4 border-primary block max-w-[500px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[350px] lg:h-[680px]">
                            <div class="p-3">
                                <h1 class="text-center mb-5 text-md font-bold leading-tight text-hideung"> 4 kamera 2mp
                                </h1>
                                <img src="@/assets/product/pcctv4.png" alt="catra"
                                    class="inline h-[120px] lg:h-[180px] mb-5" />
                                <div class="bg-bodas rounded-[10px] p-2 mb-5">
                                    <h1 class="text-left font-light text-sm text-abhu mb-3">
                                        Isian Paket Pemasangan CCTV 4 CH
                                        Lengkap
                                        .
                                    </h1>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>- NVR DAHUA 2MP 4CH 1 UNIT</h2>
                                        <h2>- IP CAM DAHUA 2MP 4 UNIT</h2>
                                        <h2>- HARDDISK 500 GB 1 UNIT</h2>
                                        <h2>- SWICTH POE / HUB 4 CH 1 UNIT</h2>
                                        <h2>- KONEKTOR CCTV LENGKAP</h2>
                                    </div>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>FREE</h2>
                                        <h2>- KABEL LAN 80 METER</h2>
                                        <h2>- KLEM, ISOLASI,KABEL TIES LENGKAP</h2>
                                        <h2>- ALAT LISTRIK LENGKAP</h2>
                                        <h2>- JASA INSTALASI</h2>
                                        <h2>- JASA SETTING DAN TRAINING LENGKAP</h2>
                                    </div>
                                    <h2 class="text-left text-sm font-bold mb-3">GARANSI DAHUA 1 TAHUN & JASA TEKNISI 3
                                        BULAN
                                    </h2>
                                </div>
                                <div class="">
                                    <a href="https://wa.me/6283131462238"
                                        class="transition duration-300 ease-in-out hover:bg-oren text-primary border-2 border-primary font-bold bg-bodas py-1 px-3 lg:py-3 lg:px-12 rounded-xl">Pilih
                                        Paket !</a>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-light border-solid border-4 border-primary block max-w-[500px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[350px] lg:h-[680px]">
                            <div class="p-3">
                                <h1 class="text-center mb-5 text-md font-bold leading-tight text-hideung">16 Camera 2mp
                                </h1>
                                <img src="@/assets/product/pcctv5.png" alt="catra"
                                    class="inline h-[120px] lg:h-[180px] mb-5" />
                                <div class="bg-bodas rounded-[10px] p-2 mb-5">
                                    <h1 class="text-left font-light text-sm text-abhu mb-3">
                                        Isian Paket Pemasangan CCTV 16 CH
                                        Lengkap
                                        .
                                    </h1>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>- NVR HIKVISION 2MP 16CH 1 UNIT</h2>
                                        <h2>- IP CAM HIKVISION 2MP 16 UNIT</h2>
                                        <h2>- HARDDISK 500 GB 1 UNIT</h2>
                                        <h2>- SWICTH POE 4 CH 1 UNIT</h2>
                                        <h2>- SWICTH POE 8 CH 1 UNIT</h2>
                                        <h2>- KONEKTOR CCTV LENGKAP</h2>
                                    </div>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>FREE</h2>
                                        <h2>- KABEL LAN 200 METER</h2>
                                        <h2>- KLEM, ISOLASI,KABEL TIES LENGKAP</h2>
                                        <h2>- ALAT LISTRIK LENGKAP</h2>
                                        <h2>- JASA INSTALASI</h2>
                                        <h2>- JASA SETTING DAN TRAINING LENGKAP</h2>
                                    </div>
                                    <h2 class="text-left text-sm font-bold mb-3">GARANSI HIKKVISION 1 TAHUN & JASA
                                        TEKNISI 3 BULAN
                                    </h2>
                                </div>
                                <div class>
                                    <router-link to="/gps" custom v-slot="{ navigate }">
                                        <button @click="navigate" role="link">
                                            <a
                                                class="transition duration-300 ease-in-out hover:bg-oren text-primary border-2 border-primary font-bold bg-bodas py-1 px-3 lg:py-3 lg:px-12 rounded-xl">
                                                Pilih Paket !
                                            </a>
                                        </button>
                                    </router-link>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-light border-solid border-4 border-primary block max-w-[500px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[350px] lg:h-[680px]">
                            <div class="p-3">
                                <h1 class="text-center mb-5 text-md font-bold leading-tight text-hideung">6 kamera 2mp
                                </h1>
                                <img src="@/assets/product/pcctv6.png" alt="catra"
                                    class="inline h-[120px] lg:h-[180px] mb-5" />
                                <div class="bg-bodas rounded-[10px] p-2 mb-5">
                                    <h1 class="text-left font-light text-sm text-abhu mb-3">
                                        Isian Paket Pemasangan CCTV Berwarna 6 CH Lengkap
                                        .
                                    </h1>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>- DVR DAHUA 2MP 8CH 1 UNIT</h2>
                                        <h2>- CAM DAHUA 2MP ANALOG FULL COLOR 6 UNIT</h2>
                                        <h2>- HARDDISK 500 GB 1 UNIT</h2>
                                        <h2>- PS JARING 10 A 1 UNIT</h2>
                                        <h2>- KONEKTOR CCTV LENGKAP</h2>
                                    </div>
                                    <div class="text-left font-light text-sm text-abhu mb-3">
                                        <h2>FREE</h2>
                                        <h2>- KABEL CCTV RG59 90 METER</h2>
                                        <h2>- KABEL LAN 5M + RJ 45 2PCS</h2>
                                        <h2>- KLEM, ISOLASI,KABEL TIES LENGKAP</h2>
                                        <h2>- ALAT LISTRIK LENGKAP</h2>
                                        <h2>- JASA INSTALASI</h2>
                                        <h2>- JASA SETTING DAN TRAINING LENGKAP</h2>
                                    </div>
                                    <h2 class="text-left text-sm font-bold mb-3">GARANSI DAHUA 1 TAHUN & JASA TEKNISI 3
                                        BULAN
                                    </h2>
                                </div>
                                <div class>
                                    <router-link to="/gps" custom v-slot="{ navigate }">
                                        <button @click="navigate" role="link">
                                            <a
                                                class="transition duration-300 ease-in-out hover:bg-primary hover:text-bodas text-primary border-2 border-primary font-bold bg-bodas py-1 px-3 lg:py-3 lg:px-12 rounded-xl">
                                                lihat
                                                Paket !
                                            </a>
                                        </button>
                                    </router-link>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="grid justify-items-center">
                        <router-link to="/cctv" custom v-slot="{ navigate }">
                            <button @click="navigate" role="link">
                                <a
                                    class="transition duration-300 ease-in-out hover:bg-primary hover:text-bodas text-primary border-2 border-primary font-bold bg-bodas py-3 px-12 rounded-xl">Paket
                                    Lainnya !</a>
                            </button>
                        </router-link>
                    </div>
                </div>
            </TabPanel>
            <TabPanel>Content 2</TabPanel>
            <TabPanel>Content 3</TabPanel>
            <TabPanel>Content 4</TabPanel>
            <TabPanel>Content 5</TabPanel>
            <TabPanel>Content 6</TabPanel>
            <TabPanel>Content 7</TabPanel>
        </TabPanels>
    </TabGroup>
</div>
</template>

<script setup>
import { TabGroup, TabList, Tab, TabPanels, TabPanel } from '@headlessui/vue'
</script>