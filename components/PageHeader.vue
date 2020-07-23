<template>
  <header class="block md:flex items-center justify-between px-4">
    <h1 class="bg-black font-bold p-4 text-white uppercase">
      <nuxt-link to="/">Felipe Nogueira</nuxt-link>
    </h1>
    <nav class="text-center">
      <nuxt-link class="inline-block rounded mx-2 md:mx-0 p-2" to="/posts">Blog</nuxt-link>
      <nuxt-link
        class="inline-block rounded mx-2 md:mx-0 md:ml-4 p-2"
        to="/posts/categories/development"
      >Development</nuxt-link>
      <nuxt-link
        class="inline-block rounded mx-2 md:mx-0 md:ml-4 p-2"
        to="/posts/categories/tutorials"
      >Tutorials</nuxt-link>
      <nuxt-link class="inline-block rounded mx-2 md:mx-0 md:ml-4 p-2" to="/projects">Projects</nuxt-link>
      <nuxt-link class="inline-block rounded mx-2 md:mx-0 md:ml-4 p-2" to="/demoreel">Demo Reel</nuxt-link>
      <nuxt-link class="inline-block rounded mx-2 md:mx-0 md:ml-4 p-2" to="/about">About</nuxt-link>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
</style>
