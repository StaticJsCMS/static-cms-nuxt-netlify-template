<script setup lang="ts">
definePageMeta({
  layout: 'default',
})
</script>

<template>
  <main class="px-4 py-20 min-h-screen w-full flex flex-col justify-between">
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="block text-2xl font-sans font-bold transition-colors duration-200 ease-in-out text-center">Nuxt — Tailwind — Netlify CMS</h1>
      <h2 class="subtitle text-center">Boilerplate</h2>
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Latest blog post</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>