<template>
    <section id="contact" class=" bg-gray-200 dark:bg-gray-700 h-screen">
        <div class="container mx-auto h-full flex items-center flex-col justify-center">
            <h2 class="text-4xl font-semibold mb-8 text-center dark:text-white">Hubungi Bajrul Hakimi</h2>

            <!-- Informasi Kontak -->
            <div class="flex flex-col md:flex-row justify-center items-center space-y-6 md:space-y-0 md:space-x-8">
                <!-- Card: Email -->
                <ContactCard title="Email" icon="ri:mail-fill" link="mailto:bajrulhakimi04@gmail.com"
                    content="bajrulhakimi04@gmail.com" />

                <!-- Card: LinkedIn -->
                <ContactCard title="LinkedIn" icon="ri:linkedin-box-fill" link="https://linkedin.com/in/Bajrul-Hakimi"
                    content="Bajrul Hakimi" />

                <!-- Card: GitHub -->
                <ContactCard title="GitHub" icon="uil:github" link="https://github.com/bajruhakimi"
                    content="bajrulhakimi" />
            </div>

            <!-- Sosial Media -->
            <div class="flex justify-center items-center mt-8">
                <ul class="flex space-x-5">
                    <li>
                        <a href="https://www.facebook.com/bajrul.hakimi" target="_blank" rel="noopener noreferrer">
                            <Icon name="ri:facebook-circle-fill" class="w-8 h-8" />
                        </a>
                    </li>
                    <li>
                        <a href="https://www.instagram.com/bajrul.hakimi" target="_blank" rel="noopener noreferrer">
                            <Icon name="ri:instagram-line" class="w-8 h-8" />
                        </a>
                    </li>
                    <li>
                        <a href="https://twitter.com/HakimiBajrul" target="_blank" rel="noopener noreferrer">
                            <Icon name="ri:twitter-fill" class="w-8 h-8" />
                        </a>
                    </li>
                    <li>
                        <a href="https://wa.me/+62082387901257" target="_blank" rel="noopener noreferrer">
                            <Icon name="ri:whatsapp-line" class="w-8 h-8" />
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>
  
<script>
import ContactCard from '~/components/ContactCard.vue';

export default {
    head: {
        title: 'Hubungi Bajrul Hakimi',
    },
    components: {
        ContactCard,
    },
};
</script>
  