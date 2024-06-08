<script setup lang="js">
defineProps({
  poin: String,
  title: String,
  desc: String,
  icon: Object,
})

</script>

<template>
  <div 
    class="flex flex-row items-center justify-between flex-1 space-x-5 hover:shadow-2xl hover:rounded-2xl transition transform hover:-translate-y-1 motion-reduce:transition-none 
    motion-reduce:hover:transform-none bg-white hover:bg-dark-grey-100">

    <div class="flex items-center justify-center w-12 h-12 text-base font-bold leading-8 text-center 
 bg-white hover:bg-purple-blue-500 border-2 rounded-full text-purple-blue-500 hover:text-white border-purple-blue-500">
      {{ poin }} </div>
      <div class="flex flex-col flex-1">
        <h1 class="text-base font-bold leading-8 text-dark-grey-900">
          {{ title }}
        </h1>
        <p class="text-base font-medium leading-8 text-dark-grey-600">
            {{ desc }}
              </p>
        </div>    
    </div>
    <div class="animate-bounce w-10 h-10 text-dark-grey-600">
      <component :is="icon" /> </div>

        
  
</template>