<script setup lang="js">
defineProps({
  image: String,
  link: String,
})
</script>

<template>
  <article>
    <h1 class="m-4">
      {{ image }}
    </h1>
    <div class="w-10 h-10 overflow-hidden rounded-full mt-9">
        <img :src="link" alt="" /></div>
  </article>
</template>