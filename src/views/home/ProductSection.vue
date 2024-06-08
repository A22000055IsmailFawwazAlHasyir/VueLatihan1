<script setup lang="js">
import { Moon, Phone } from '@/components/icons'
</script>
<template>
<section id="product" class="container max-h-lvh pt-28">
    <div class="grid w-full grid-cols-2 gap-12">
      <div class="flex flex-col items-start justify-center space-y-6">
        <div class="max-w-[80%] justify-start">
          <p class="space-x-6 text-sm text-purple-blue-500 font-display font-bold leading-5 tracking-[2.08px]"> 
            <Moon class="inline w-5 h-5 mr-3"/>TRENDIEST TAILWIND TEMPLATES
          </p>
        </div>
          <h1 class="animate-pulse text-6xl font-extrabold leading-[60px] text-dark-grey-900 mt-3">
            Take your website to the next level with Horizon UI
          </h1>


        <p class="text-base font-medium leading-8 text-dark-grey-600 max-w-[60%]">
          Save hundreds of hours trying to create and develop a dashboard from scratch. The fastest,
          most responsive & trendiest dashboard is here. Seriously.
        </p>

        <div class="flex flex-row space-x-3">
          <RouterLink
            to="/register"
            class="px-6 py-4 text-sm text-white font-bold leading-6 rounded-xl bg-blue-500"
            >Get Started Now</RouterLink
          >
          <div class="flex">
          <RouterLink
            to="/login"
            class="px-6 py-4 ext-sm font-medium leading-6 bg-white rounded-xl text-dark-grey-900"
          >
            <Phone class="inline w-6 h-6 mr-3" />
            Book a free call</RouterLink
          >
        </div>
        </div>
      </div>
      <div class="flex justify-end">
        <img src="@/assets/img/img.svg" alt="home-banner" class="w-[80%]" />
      </div>
    </div>
  </section>
</template>