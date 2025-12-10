<script setup lang="ts">
definePageMeta({
  name: "projects",
});

useHead({
  title: "Chafik Chegma | Projects",
  meta: [
    {
      name: "description",
      content: "Browse all of Chafik Chegma's web development projects. Explore responsive, accessible, and modern websites, applications, and solutions I have built."
    }
  ]
});
</script>

<template>
  <section class="px-6 mx-auto max-w-7xl mt-16 lg:mt-32 pb-8">
    <Project />
  </section>
</template>
