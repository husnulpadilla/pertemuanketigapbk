<template>
  <div class="row q-col-gutter-md q-pa-md">
    <div
      v-for="product in products"
      :key="product.id"
      class="col-xs-12 col-sm-6 col-md-4"
    >
      <q-card>
        <q-img :src="product.image" height="160px" />
        <q-card-section>
          <div class="text-h6">{{ product.name }}</div>
          <div class="text-subtitle2 text-primary">{{ product.price }}</div>
        </q-card-section>
      </q-card>
    </div>
  </div>
</template>

<script setup>
const products = [
  { id: 1, name: 'Produk A', price: 'Rp 100.000', image: 'https://via.placeholder.com/300' },
  { id: 2, name: 'Produk B', price: 'Rp 150.000', image: 'https://via.placeholder.com/300' },
  { id: 3, name: 'Produk C', price: 'Rp 200.000', image: 'https://via.placeholder.com/300' }
]
</script>
