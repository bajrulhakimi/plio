<template>
  <section id="contact" class="pt-6 pb-8 bg-gray-200 dark:bg-gray-700">
    <div class="container mx-auto ">
      <h2 class="text-3xl font-semibold mb-8 dark:text-white text-center">Hubungi Saya</h2>
      <div class="flex justify-center">
        <!-- Card 1: Email -->
        <a href="mailto:bajrulhakimi04@gmail.com"
          class="w-64 bg-white dark:bg-gray-800 p-4 rounded-lg shadow-md flex items-center">
          <Icon name="ri:mail-fill" class="text-2xl w-8 h-8" />
          <div class="ml-3">
            <p class="font-semibold text-lg">Email</p> 
            <p class="text-gray-600 text-sm">bajrulhakimi04@gmail.com</p> 
          </div>
        </a>

        <!-- Card 2: LinkedIn -->
        <a href="https://linkedin.com/in/Bajrul-Hakimi" target="_blank" rel="noopener noreferrer"
          class="w-64 bg-white dark:bg-gray-800 p-4 rounded-lg shadow-md flex items-center ml-4">
          <Icon name="ri:linkedin-box-fill" class="text-2xl w-8 h-8 " />
          <div class="ml-3">
            <p class="font-semibold text-lg">LinkedIn</p>
            <p class="text-gray-600 text-sm">Bajrul Hakimi</p>
          </div>
        </a>

        <!-- Card 3: GitHub -->
        <a href="https://github.com/bajruhakimi" target="_blank" rel="noopener noreferrer"
          class="w-64 bg-white dark:bg-gray-800 p-4 rounded-lg shadow-md flex items-center ml-4">
          <Icon name="uil:github" class="text-2xl w-8 h-8" />
          <div class="ml-3">
            <p class="font-semibold text-lg">GitHub</p>
            <p class="text-gray-600 text-sm">bajrulhakimi</p>
          </div>
        </a>
      </div>
      <div class="flex justify-center items-center mt-8">
        <ul class="flex space-x-5">
          <li>
            <a href="https://www.facebook.com/bajrul.hakimi" target="_blank" rel="noopener noreferrer">
              <Icon name="ri:facebook-circle-fill" class="w-6 h-6" />
            </a>
          </li>
          <li>
            <a href="https://www.instagram.com/bajrul.hakimi" target="_blank" rel="noopener noreferrer">
              <Icon name="ri:instagram-line" class="w-6 h-6" />
            </a>
          </li>
          <li>
            <a href="https://twitter.com/HakimiBajrul" target="_blank" rel="noopener noreferrer">
              <Icon name="ri:twitter-fill" class="w-6 h-6" />
            </a>
          </li>
          <li>
            <a href="https://wa.me/+62082387901257" target="_blank" rel="noopener noreferrer">
              <Icon name="ri:whatsapp-line" class="w-6 h-6" />
            </a>
          </li>
        </ul>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  head: {
    title: 'Hubungi Saya',
  },
};
</script>
