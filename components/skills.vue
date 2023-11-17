<template>
  <section id="skills" class="py-10 dark:bg-gray-800">
    <div class="container mx-auto">
      <h2 class="text-3xl font-semibold mb-8 text-center dark:text-white">Keahlian dan Proyek</h2>

      <!-- Keahlian -->
      <div class="mb-8 space-x-5 flex flex-wrap justify-center items-center">
        <SkillIcon name="ri:html5-fill" title="HTML" />
        <SkillIcon name="ri:css3-fill" title="CSS" />
        <SkillIcon name="ri:javascript-fill" title="JavaScript" />
        <SkillIcon name="ri:reactjs-fill" title="React.js" />
        <SkillIcon name="simple-icons:nuxtdotjs" title="Nuxt.js" />
        <SkillIcon name="material-symbols:php-rounded" title="Express.js" />
      </div>

      <!-- Contoh Proyek -->
      <div>
        <h3 class="text-2xl font-semibold mb-4 dark:text-white">Contoh Proyek</h3>

        
        <ProjectCard
          title="Proyek E-Commerce"
          description="Mengembangkan platform e-commerce menggunakan React.js dan Node.js. Proyek ini mencakup sistem pembayaran online dan manajemen inventaris."
        />

        
        <ProjectCard
          title="Proyek Blog Pribadi"
          description="Membuat blog pribadi menggunakan HTML, CSS, dan JavaScript. Proyek ini mencakup sistem manajemen konten sederhana dan integrasi API."
        />

        <!-- Tambahkan proyek lain sesuai kebutuhan -->
      </div>
    </div>
  </section>
</template>

<script>
import SkillIcon from '~/components/SkillIcon.vue';
import ProjectCard from '~/components/ProjectCard.vue';

export default {
  head: {
    title: 'Keahlian dan Proyek',
  },
  components: {
    SkillIcon,
    ProjectCard,
  },
};
</script>
