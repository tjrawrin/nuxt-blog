<template>
  <header>
    <nav>
      <NuxtLink to="/posts">Blog</NuxtLink>
      <NuxtLink to="/posts/categories/development">Development</NuxtLink>
      <NuxtLink to="/posts/categories/tutorials">Tutorials</NuxtLink>
      <NuxtLink to="/projects">Projects</NuxtLink>
      <NuxtLink to="/demoreel">Demo Reel</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
.nuxt-link-exact-active {
  font-weight: bold;
}
</style>
