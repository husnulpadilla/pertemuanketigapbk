<template>
  <q-page class="q-pa-md">
    <Navbar />
    <Carousel />
    <div class="q-my-md">
      <ProductCard />
    </div>
    <Footer />
  </q-page>
</template>

<script setup>
import Navbar from 'components/Navbar.vue'
import Carousel from 'components/Carousel.vue'
import ProductCard from 'components/ProductCard.vue'
import Footer from 'components/Footer.vue'
</script>
