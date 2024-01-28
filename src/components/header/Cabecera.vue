<!-- eslint-disable vue/multi-word-component-names -->
<!-- eslint-disable vue/no-use-v-if-with-v-for -->
<template>
  <header v-bind:class="{ 'lg:hidden 2xl:hidden xl:hidden cel:flex md:flex w-full h-screen bg-neutral-950 items-center justify-center flex-col': isOpen }" @click="toggleMenu">
    <button class="lg:hidden 2xl:hidden xl:hidden">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="text-white w-10 h-10 absolute top-5 left-5">
  <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25H12" />
</svg>

    </button>
      <a v-if="isOpen" v-for="(link, index) in navLinks" :key="index" :href="link.url" class="text-white mt-3 mb-3 border-2 border-black w-28 h-10 grid place-items-center rounded-full bg-neutral-600">{{ link.text }}</a>
  </header>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false,
      navLinks: [
        { text: 'Mercurio', url: '#mercurio' },
        { text: 'Neptuno', url: '#neptuno' },
        { text: 'Júpiter', url: '#jupiter' },
        { text: 'Saturno', url: '#saturno' },
        { text: 'Urano', url: '#urano' },
        { text: 'Tierra', url: '#tierra' },
        { text: 'Marte', url: '#marte' },
        { text: 'Venus', url: '#venus' }
      ],
    };
  },
  methods: {
    toggleMenu() {
      this.isOpen = !this.isOpen;
    },
  },
};
</script>
