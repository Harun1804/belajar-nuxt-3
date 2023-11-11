<template>
  <header>
  <NuxtLink to="/">Ninja Dojo</NuxtLink>
    <ul>
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/about">About</NuxtLink></li>
      <li><NuxtLink to="/products">Products</NuxtLink></li>
    </ul>
  </header>

  <div>
    <slot />
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
