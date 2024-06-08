<script setup lang="js">
import ButtonPrimary from './buttons/ButtonPrimary.vue';
import Navbar from './Navbar.vue';

const nav = [
  {
    href: '#product',
    title: 'Product',
  },
  {
    href: '#features',
    title: 'Features',
  },
  {
    href: '#pricing',
    title: 'Pricing',
  },
{
    href: '#company',
    title: 'Company',
  },
]
</script>

<template>
  <header class="bg-white fixed font-jakarta justify-center items-center w-[93.5%] z-50">
    <div class="container grid grid-cols-3 py-6 ">
      <div class="flex items-center justify-start">
        <img src="@/assets/img/logo.png" alt="Logo" class="logo">
      </div>
      <div class="flex flex-row items-center justify-center menu">
        <Navbar
          v-for="step in nav"
          :href="step.href"
          :title="step.title"
         
       />
      </div>
      <div class="actions flex flex-row items-center justify-end space-x-4">
        <ButtonPrimary text="Log In" type="header" to="/login"  />
        <ButtonPrimary text="Sign Up" type="headerout" to="/register"  />
      </div>
    </div>
  </header>
  </template>