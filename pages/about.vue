<template>
    <section id="about1" class="py-16 bg-gray-200 dark:bg-gray-700">
      <div class="container mx-auto flex items-center mb-8">
        <div class="w-1/2">
          <!-- Foto profil -->
          <img src="/images/bajrul.jpg" alt="Profil" class="rounded-full w-60 h-60 object-cover mx-auto mb-6" />
        </div>
        <div class="w-1/2 pl-10">
          <h2 class="text-4xl font-semibold mb-4 dark:text-white">Bajrul Hakimi</h2>
          <p class="text-lg mb-4 dark:text-white">Umur: 21 tahun</p>
          <p class="text-lg mb-4 dark:text-white">Pekerjaan: Web Developer</p>
          <!-- Tambahan: Daftar Keterampilan -->
          <div class="mb-4">
            <h3 class="text-2xl font-semibold mb-2 dark:text-white">Keterampilan</h3>
            <ul class="list-disc list-inside">
              <li>HTML</li>
              <li>CSS</li>
              <li>JavaScript</li>
              <li>React.js</li>
            </ul>
          </div>
          <!-- Tambahan: Daftar Pendidikan -->
          <div class="mb-4">
            <h3 class="text-2xl font-semibold mb-2 dark:text-white">Pendidikan</h3>
            <p class="text-lg dark:text-white">Sarjana Teknik Informatika, Universitas XYZ</p>
            <p class="text-lg dark:text-white">Tahun 2019 - 2023</p>
          </div>
          <!-- Tambahan: Pengalaman Kerja -->
          <div class="mb-4">
            <h3 class="text-2xl font-semibold mb-2 dark:text-white">Pengalaman Kerja</h3>
            <p class="text-lg dark:text-white">Web Developer, Perusahaan ABC</p>
            <p class="text-lg dark:text-white">Tahun 2022 - Sekarang</p>
          </div>
        </div>
      </div>
      <p class="mx-20 text-center mb-4 dark:text-white">
        Sebagai lulusan IT yang berdedikasi, saya memiliki fondasi pendidikan yang
        kuat dan pengalaman praktis yang mendalam dalam menghadapi tantangan teknologi modern.
        Saya adalah individu yang bersemangat dan memiliki kemampuan analitis yang tinggi,
        serta komitmen untuk memahami dan menghadapi perkembangan terkini dalam dunia IT.
      </p>
    </section>
  </template>
  
  <script>
  export default {
    head: {
      title: 'Tentang Saya',
    },
  };
  </script>
  