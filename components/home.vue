<template>
    <section id="home" class="pt-20 pb-5 dark:bg-gray-800">
        <div class="container mx-auto text-center">
            <p class="text-lg dark:text-white">Saya Bajrul Hakimi</p>
            <h1 class="text-6xl font-bold mb-2 dark:text-white">SELAMAT DATANG</h1>
            <h1 class="text-6xl font-bold mb-10 dark:text-white">DI WEBSITE SAYA</h1>
        </div>
        <div class="bg-slider flex space-x-4">
            <div class="slide" style="background-image: url('/images/pm.jpg');"></div>
            <div class="slide" style="background-image: url('/images/pl.png');"></div>
            <div class="slide" style="background-image: url('/images/pn.jpg');"></div>
        </div>
    </section>
</template>

<style scoped>
.bg-slider {
    height: 350px;
    overflow: hidden;
    position: relative;
    display: flex;
}

.slide {
    flex: 1;
    height: 100%;
    background-size: cover;
    background-position: center;
    position: relative;
    border-radius: 15px; /* Sesuaikan nilai sesuai keinginan Anda */
}
</style>

<script>
export default {
    head: {
        title: 'Halaman Beranda',
    },
};
</script>
