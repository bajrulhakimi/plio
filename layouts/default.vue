<template>
    <div :class="{ 'dark': isDarkMode }" @scroll="handleScroll" ref="containerRef" class="max-h-screen overflow-auto">
        <header :class="{ 'show': scrolledDown, 'bg-opacity-75': scrolledUp }"
            class="fixed w-full top-0 z-10 py-2 bg-gradient-to-t dark:from-gray-50/10 dark:to-gray-50/0 from-gray-900/10 to-gray-50/0 dark:text-white transition-opacity">
            <div class="container mx-auto">
                <div class="flex justify-between items-center">
                    <router-link to="/" class="text-2xl font-semibold">Bajrul Hakimi</router-link>
                    <ul class="flex space-x-5 ml-auto mr-10">
                        <li><router-link to="/">Home</router-link></li>
                        <li><router-link to="/about">About</router-link></li>
                        <li><router-link to="/skill">Skill</router-link></li>
                        <li><router-link to="/contact">Contact</router-link></li>
                    </ul>
                    <UseDark v-slot="{ isDark, toggleDark }">
                        <button @click="toggleDark()">
                            <Icon :name="isDark ? 'ri:sun-line' : 'ri:moon-fill'" />
                        </button>
                    </UseDark>
                </div>
            </div>

        </header>


        <main @scroll="handleScroll">
            <slot />
        </main>


        <footer class="bg-gray-200 text-gray-600 py-3">
            <div class="container mx-auto text-center ">
                &copy; 2023 Proyek Saya
            </div>
        </footer>
    </div>
</template>
  
<script>
import { UseDark } from "@vueuse/components";
export default {
    components: { UseDark },
    data() {
        return {
            isDarkMode: false,
            lastScrollPos: 0,
            scrolledDown: false,
            scrolledUp: false,
        };
    },
    setup() {
        const containerRef = ref();
        return {
            containerRef
        }
    },
    methods: {
        toggleDarkMode() {
            this.isDarkMode = !this.isDarkMode;
            if (this.isDarkMode) {
                document.documentElement.classList.add("dark");
            } else {
                document.documentElement.classList.remove("dark");
            }
        },
        handleScroll() {
            const currentScrollPos = this.containerRef.scrollTop;
            if (currentScrollPos > this.lastScrollPos) {
                // Scroll ke bawah
                this.scrolledDown = true;
                this.scrolledUp = false;
            } else {
                this.scrolledDown = false;
                this.scrolledUp = true;
            }


            this.lastScrollPos = currentScrollPos;
        },
    },
    head: {
        title: "Proyek Saya",
    },
};
</script>
  
<style scoped>
header {
    transform: translateY(0);
    transition: all .2s ease-in-out;
}

header.show {
    transform: translateY(-100%);
}
</style>
  