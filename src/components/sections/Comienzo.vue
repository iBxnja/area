<template>
    <section class="w-full h-screen flex items-center justify-center flex-col">
        <img :src="area" alt="area" class="cel:w-36 w-40 mb-5" />
        <h2 class="cel:text-2xl text-3xl font-bold text-transparent bg-clip-text bg-[radial-gradient(ellipse_at_bottom_left,_var(--tw-gradient-stops))] from-purple-500 via-violet-100 to-indigo-800">Bienvenido astronauta</h2>
        <span class="cel:text-center cel:text-2xl font-normal text-3xl mt-1 tracking-widest text-transparent bg-clip-text bg-[radial-gradient(ellipse_at_bottom_right,_var(--tw-gradient-stops))] from-purple-500 via-violet-100 to-indigo-800">¿Listo para dar un paseo por el espacio?</span>
        <div class="flex items-center justify-center gap-20 mt-5">
          <a href="https://github.com/iBxnja"><i class="fa-brands fa-github text-transparent bg-clip-text bg-[radial-gradient(ellipse_at_bottom_left,_var(--tw-gradient-stops))] from-purple-500 via-violet-100 to-indigo-800 text-4xl"></i></a>
          <a href="www.linkedin.com/in/diego-benjamin-vallory-52b793263"><i class="fa-brands fa-linkedin text-transparent bg-clip-text bg-[radial-gradient(ellipse_at_bottom_left,_var(--tw-gradient-stops))] from-purple-500 via-violet-100 to-indigo-800 text-4xl"></i></a>
        </div>
    </section>
</template>

<script>
import area from '../../assets/area.png';

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Inicio',
  data() {
    return {
      area: area,
    };
  }
};
</script>
