<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Vuwi Template',
  meta: [
    { name: 'description', content: 'Starter template using Vitesse + Vuwi components' },
  ],
})
</script>

<template>
  <router-view />
</template>
