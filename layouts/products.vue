<template>
  <header>
  <NuxtLink to="/products">Ninja Dojo</NuxtLink>
  </header>

  <div>
    <slot />
  </div>

  <footer>
    <ul>
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/about">About</NuxtLink></li>
      <li><NuxtLink to="/products">Products</NuxtLink></li>
    </ul>
  </footer>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
