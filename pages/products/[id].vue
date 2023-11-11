<template>
  <div>
    <h1>Product Detail for {{ id }}</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem nostrum id molestiae dignissimos corrupti pariatur nam voluptates. Quaerat sapiente dolorem veniam ratione a sit commodi, magnam explicabo non culpa officia consequuntur dolorum perspiciatis, in, amet quia nam ipsam. Doloribus.</p>
  </div>
</template>

<script setup>
const { id } = useRoute().params
definePageMeta({
    layout:'products'
  })
</script>

<style scoped>

</style>