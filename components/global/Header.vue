<script lang="ts">
export default {
  name: 'Header'
}
</script>


<template>
  <nav class="fixed z-40 top-0 inset-x-0 pt-3 px-3" aria-label="Main Menu">
    <ul class="flex">
      <li class="flex-1">
        <nuxt-link class="btn" to="/">Home</nuxt-link>
      </li>
      <li class="flex-1 ml-2">
        <nuxt-link class="btn" to="/blog">Blog</nuxt-link>
      </li>
      <li class="flex-1 ml-2">
        <nuxt-link class="btn" to="/projects">Projects</nuxt-link>
      </li>
    </ul>
  </nav>
</template>
