<script setup>
defineProps({
  text: String,
  type: {
    default: 'solid'
  }
})
</script>
<template>
  <button v-if="type == 'solid'" class="py-4  text-white bg-purple-blue-500 hover:bg-purple-blue-700 rounded-xl px-7">
    {{ text }}
  </button>
  <button v-else-if="type == 'outline'"
    class="py-4 bg-white border-2 text-purple-blue-500 hover:text-white border-purple-blue-500 hover:bg-purple-blue-500 rounded-xl px-7">
    {{ text }}
  </button>

  <button v-else-if="type == 'header'"
    class="px-4 py-2 font-bold font-sm bg-white border-2 text-blue-500 hover:text-white border-blue-500 hover:bg-blue-500 rounded-xl leading-5">
    {{ text }}
  </button>
  <button v-else-if="type == 'headerout'"
    class="px-4 py-2 font-bold font-sm bg-blue-100 text-purple-blue-500 hover:bg-purple-blue-700 rounded-xl leading-6 hover:text-white">
    {{ text }}
  </button>
</template>
