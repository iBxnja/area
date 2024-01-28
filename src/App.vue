<template>
  <HelloWorld />
  <Header />
  <main class="w-full h-full">
    <Aside />
    <Inicio />
    <Informacion />
    <Planetas />
  </main>
  <Footer />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/header/Cabecera.vue'
import Footer from './components/footer/PieDePagina.vue'
import Aside from './components/aside/Costado.vue'
import Inicio from './components/sections/Comienzo.vue'
import Informacion from './components/sections/Informacion.vue'
import Planetas from './components/sections/Planetas.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
    Aside,
    Inicio,
    Informacion,
    Planetas,
    Footer
  }
}
</script>

<style>

</style>
