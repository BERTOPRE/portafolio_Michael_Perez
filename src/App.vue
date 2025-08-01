<template>
  <div>
    <div class="principal-container">
      <Navbar />
      <div id="inicio">
        <Banner />
      </div>
      <section class="principal-container" id="sobre-mi">
        <SobreMi />
      </section>
      <section class="principal-container" id="portafolio">
        <Portafolio />
      </section>
      <section class="principal-container" id="contactame">
        <Contactame />
      </section>
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/navbar/navbar.vue'
import Banner from '@/components/content/banner.vue'
import Footer from './components/footer/footer.vue'
import SobreMi from '@/components/content/sobre-mi.vue'
import Portafolio from '@/components/content/portafolio.vue'
import Contactame from './components/content/contactame.vue'
</script>
