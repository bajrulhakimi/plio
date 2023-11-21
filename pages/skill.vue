<template>
    <section id="skills-and-projects" class="py-16 dark:bg-gray-800">
      <div class="container mx-auto">
        <h2 class="text-3xl font-semibold mb-8 text-center dark:text-white">Keahlian dan Proyek</h2>
  
        <!-- Keahlian -->
        <div class="mb-8 space-x-7 flex flex-wrap justify-center">
          <Icon name="ri:html5-fill" title="HTML" class="text-2xl w-8 h-8" />
          <Icon name="ri:css3-fill" title="CSS" class="text-2xl w-8 h-8" />
          <Icon name="ri:javascript-fill" title="JavaScript" class="text-2xl w-8 h-8" />
          <Icon name="ri:reactjs-fill" title="React.js" class="text-2xl w-8 h-8" />
          <Icon name="simple-icons:nuxtdotjs" title="Nuxt.js" class="text-2xl w-8 h-8" />
          <Icon name="material-symbols:php-rounded" title="Express.js" class="text-2xl w-8 h-8" />
        </div>
  
        <!-- Proyek -->
        <div>
          <h3 class="text-2xl font-semibold mb-4 dark:text-white">Proyek-Proyek Utama</h3>
  
          <ProjectCard
            title="Platform E-Commerce Terkemuka"
            description="Membangun platform e-commerce terkemuka dengan jutaan pelanggan dan transaksi harian. Menggunakan teknologi React.js dan Node.js untuk kinerja dan keamanan yang optimal."
            repositoryLink="https://github.com/username/proyek-ecommerce"
            testimonial="Kerja sama dengan tim pengembang sangat efisien. Proyek ini telah membawa perusahaan kami ke puncak dalam industri e-commerce."
          />
  
          <ProjectCard
            title="Inovasi Aplikasi Mobile"
            description="Mengembangkan aplikasi mobile inovatif dengan fokus pada pengalaman pengguna yang luar biasa. Mengintegrasikan teknologi terkini untuk memenuhi tuntutan pasar yang berkembang."
            repositoryLink="https://github.com/username/proyek-aplikasi-mobile"
            testimonial="Aplikasi mobile yang dikembangkan oleh tim ini berhasil mendapatkan perhatian positif dari pengguna kami. Desain yang responsif dan fitur yang inovatif membuatnya sukses."
          />
  
          <ProjectCard
            title="Sistem Manajemen Inventaris Otomatis"
            description="Membuat sistem manajemen inventaris otomatis menggunakan teknologi Node.js. Mengoptimalkan proses manajemen stok dan pemantauan inventaris secara real-time."
            repositoryLink="https://github.com/username/proyek-manajemen-inventaris"
            testimonial="Dengan implementasi sistem manajemen inventaris otomatis ini, perusahaan kami dapat menghemat waktu dan meningkatkan efisiensi operasional secara signifikan."
          />
  
          <!-- Tambahkan proyek lain sesuai kebutuhan -->
        </div>
      </div>
    </section>
  </template>
  
  <script>
  import ProjectCard from '~/components/ProjectCard.vue';
  
  export default {
    head: {
      title: 'Keahlian dan Proyek',
    },
    components: {
      ProjectCard,
    },
  };
  </script>
  