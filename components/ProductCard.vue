<template>
  <div class="card text-center">
    <img :src="product.image" class="thumb" alt="product-thumb">
    <p class="font-bold text-gray-500 m-4 truncate">{{ product.title }}</p>
    <NuxtLink :to="`/products/${product.id}`">
      <p class="btn my-4 mx-3">View Details</p>
    </NuxtLink>
  </div>
</template>

<script setup>
const { product } = defineProps(['product'])

useHead({
  title: 'Nuxt Dojo | Merch'
})
</script>

<style scoped>
  .thumb {
    max-height: 120px;
    max-width: 70%;
    margin: 0 auto;
  }
</style>