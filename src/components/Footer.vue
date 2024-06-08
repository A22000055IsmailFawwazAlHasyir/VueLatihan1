<script setup lang="js">
import Navbar from './Navbar.vue';

const nav = [
  {
    href: '#about',
    title: 'About',
  },
  {
    href: '#features',
    title: 'Features',
  },
  {  href: '#blog',
    title: 'Blog',
  },
{
    href: '#resources',
    title: 'Resources',
  },
  {
    href: '#partner',
    title: 'Partner',
  },
 { 
    href: '#help',
    title: 'Help',
},
  { href: '#term',
    title: 'Term',
  },
]
</script>


<template>
    <footer>
      <div class="container">
        <div class="py-12">
          <div class="flex flex-col items-center justify-center">
            <img src="@/assets/img/logo.png" alt="logo" class="w-[156px]" />

            <nav class="flex justify-evenly my-5">

          <Navbar
          v-for="step in nav"
          :href="step.href"
          :title="step.title"
     />
    </nav>  

  <div class="flex m-auto pt-0">
    <img class="m-4" src="@/assets/img/fb.svg" alt="fb">
    <img class="m-4" src="@/assets/img/twitter.svg" alt="fb">
    <img class="m-4" src="@/assets/img/github.svg" alt="fb">
    <img class="m-4" src="@/assets/img/linkedin.svg" alt="fb">
    <img class="m-4" src="@/assets/img/ig.svg" alt="fb">
  </div>

            <p class="mt-6 text-base font-medium leading-8 text-center text-dark-grey-600">
              © 2023 Horizon UI Library. All rights reserved.
            </p>
          </div>
        </div>
      </div>
    </footer>
  </template>
  