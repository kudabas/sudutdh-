<template>
    <div id="service">
        <div class="mx-3 2xl:px-40 lg:pb-20">
            <div class="mb-10 text-center pt-20">
                <h1 class="mb-0 text-lg text-center font-bold">Fitur Pendukung</h1>
            </div>
            <div class="text-center grid justify-items-center grid-cols-2 gap-4 lg:grid-cols-4 pb-4">
                <div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/mesino.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">Matikan Mesin</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">Memaatikan mesin jarak jauh melalui aplikasi hp</h2>
                    </div>
                </div>
                <div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/notif.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">Pesan Peringatan</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">Notifikasi jika daya perangkat terputus dan unit melebihi batas kecepatan tertentu</h2>
                    </div>
                </div><div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/penya.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">Penyadapan suara</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">Mendengarkan suara di dalam mobil dengan cara menghubungi nomor gps perangkat </h2>
                    </div>
                </div><div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/outot.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">Outout Digital</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">Relay atau pemutus arus kelistrikan pada kendaraan </h2>
                    </div>
                </div>
            </div>
            <div class="text-center grid justify-items-center grid-cols-2 gap-4 lg:grid-cols-4 pb-4">
                <div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/sos.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">Tombol SOS</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">Tombol yang apabila di tekan akan langsung mengirimkan pesan kpd pemilik kendaraan </h2>
                    </div>
                </div>
                <div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/histori.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">History Perjalanan</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">Laporan perjalanan selama 30 hari </h2>
                    </div>
                </div><div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/notif.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">Notif Kendaraan</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">Pemberitahuan saat kendaraan di matikan/di nyalakan </h2>
                    </div>
                </div><div
                    class="border-solid border-4 border-bodas transition duration-300 ease-in-out hover:border-primary block max-w-[400px] rounded-[20px] shadow-lg bg-bodas bg-opacity-50 mb-10 lg:mb-10 lg:w-[300px]">
                    <div class="p-4">
                        <img src="@/assets/lapor.png" alt="catra" class="inline h-[80px] mb-3" />
                        <h1 class="text-center mb-3 text-base font-semibold leading-tight text-hideung">Laporan</h1>
                        <h2 class="text-center mb-0 text-base font-light text-abhu">laporan jarak tempuh per hari, konsumsi bbm, lama parker dll </h2>
                    </div>
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