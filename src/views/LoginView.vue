<template>
    <header>
  
  
      
  </header>
  
  <body>
    <nav class="navbar">
      <div class="container">
        <div class="navbar-left">
          <router-link to="/" class="navbar-brand">
            <img src="@/assets/img/avatar.png" alt="Logo" class="logo">
          </router-link>
          <router-link to="/" class="navbar-brand">
            <img src="@/assets/img/horizon.svg" alt="horizon" class="horizon">
          </router-link>
        </div>
        <div class="navbar-center">
          <ul class="navbar-nav">
            <li class="nav-item">
              <router-link class="nav-link" to="/">Product</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about">Feature</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/services">Pricing</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact">Company</router-link>
            </li>
          </ul>
        </div>
        <div class="navbar-right">
          <router-link class="nav-link" to="/login">Log in</router-link>
          <router-link class="btn" to="/signup">Sign Up</router-link>
        </div>
      </div>
    </nav>
   <!-- hero  -->
  <section class=" flex w-full my-24  ">
    <div class="w-[50%] justify-center m-2">
      <!--section gambar & text  -->
        <div class="flex mx-16">
          <img class="w-6 h-6" src="@/assets/img/icon.png"  alt="icon" >
  
          <h1 class="m-2 text-blue-600 font-bold text-xs">TRENDIEST TAILWIND TEMPLATE</h1>
        </div>
  
    
  <!-- section full text -->
        <div class="flex flex-col mx-16">
          <h1 class="m-auto text-7xl justify-start ">Take your website to the next level with Horizon UI</h1>
          <h1 class="text-blue-600 text-lg m-2 text-wrap">Save hundreds of hours trying to create and develop a dashboard from scratch.
             The fastest, most responsive & trendiest dashboard is here. Seriously</h1>
        </div>
  
        <div class="flex mx-16">
          <button class="bg-blue-800 rounded hover:bg-blue-300 p-4 text-white">Get started now</button>
          <button class="flex p-4"><img src="@/assets/img/phone.svg" alt="phone logo" class="w-6 h-6 mx-2">Book a free call</button>
        </div>
    </div>
  
  
    <!-- gambar -->
    <div class="w-[50%] flex justify-end">
      <img class="size-[80%]" src="@/assets/img/img.svg"  alt="gambar">
    </div>    
  </section>  
  <!-- how horizon work? -->
  <section class=" container flex flex-col m-auto justify-center py-20 ">
  
    <div>
      <h1 class="text-center justify-center text-4xl text-blue-950 ">How Horizon works?</h1>
      <p class="text-center justify-center p-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia inventore im</p>
    </div>
  
  
  <div class="flex justify-center items-center "> 
    <div class="flex items-center m-auto justify-center w-20 h-16 bg-blue-800 text-white text-xl font-bold rounded-full">1</div>
    <div class="justify-center p-1 m-1 text-wrap">
      <h1 class="font-bold">Create your Account</h1>
      <h1 class="justify-center ">Lorem ipsum dolor sit amet consectetur
         adipisicing elit. Mollitia inventore im</h1>
    </div>
    <div class="justify-center items-center w-8 h-8 m-auto p-1"><img src="@/assets/img/chevron.svg" alt=""></div> 
    
    <div class="flex items-center m-auto justify-center w-20 h-16 border-2 text-black text-xl font-bold rounded-full">2</div>
    <div class="justify-center items-center p-1 m-1 text-wrap">
      <h1 class="font-bold">Setup your account</h1>
      <h1 class="justify-center">Lorem ipsum dolor sit amet consectetur
         adipisicing elit. Mollitia inventore im</h1>
    </div>
    <div class="justify-center w-8 h-8 items-center m-auto p-1"><img src="@/assets/img/chevron.svg" alt=""></div> 
    
    <div class="flex items-center m-auto justify-center w-20 h-16 border-2 text-black text-xl font-bold rounded-full">3</div>
    <div class="justify-center items-center p-1 m-1 text-wrap">
      <h1 class="font-bold">Start creating with Horizon</h1>
      <h1 class="justify-center">Lorem ipsum dolor sit amet consectetur
         adipisicing elit. Mollitia inventore im</h1>
    </div>
  
  </div>
  
  </section>
  
  <section>
  
  <div class="container m-auto flex w-full ">
    <div class="py-4">
      <div class="rounded-md">
        <div class="bg-blue-700 w-24 h-24 m-auto rounded-lg">
          <img class="w-20 h-20 m-auto" src="@/assets/img/mail.png" alt="mail">
        </div>
          <h1 class="font-bold text-2xl text-center m-2">Share team inboxes</h1>
        <h2 class="text-wrap text-center ">Wheter you have a team of 2 or 200, our shared team inboxes keep everyone</h2>
      </div>
    </div>
    
    <div class="py-4 ">
      <div class="shadow-2xl shadow-gray-500 rounded-xl">
        <div class="bg-blue-700 w-24 h-24 m-auto rounded-lg">
          <img class="w-20 h-20 m-auto" src="@/assets/img/chart.png" alt="chart">
        </div>
        <h1 class="font-bold text-2xl text-center m-2">Anlytics dashboard</h1>
        <h2 class="text-wrap text-center ">Wheter you have a team of 2 or 200, our shared team inboxes keep everyone</h2>
      </div>
    </div>
    
    <div class="py-4">
      <div class="">
        <div class="bg-blue-700 w-24 h-24 m-auto rounded-lg">
          <img class="w-20 h-20 m-auto" src="@/assets/img/user.png" alt="user">
        </div>    
        <h1 class="font-bold text-2xl text-center m-2">Deliver Instructor</h1>
        <h2 class="text-wrap text-center ">Wheter you have a team of 2 or 200, our shared team inboxes keep everyone</h2>
      </div>
    </div>
  
  </div>
  </section>
  
  </body>
  
    
  <footer class="flex flex-col py-16">
    <div class="m-auto ">
      <img  src="@/assets/img/logo.png" alt="logo footer">
    </div>
  
    <div class="m-auto ">
      <a class="m-4" ref="#about">About</a>
      <a class="m-4" href="#features">Features</a>
      <a class="m-4" href="#blog">Blog</a>
      <a class="m-4" href="#resources">Resources</a>
      <a class="m-4" href="#partner">Partner</a>
      <a class="m-4" href="#help">Help</a>
      <a class="m-4" href="#term">Term</a>
    </div>
  
    <div class="flex m-auto">
      <img class="m-4" src="@/assets/img/fb.svg" alt="fb">
      <img class="m-4" src="@/assets/img/twitter.svg" alt="fb">
      <img class="m-4" src="@/assets/img/github.svg" alt="fb">
      <img class="m-4" src="@/assets/img/linkedin.svg" alt="fb">
      <img class="m-4" src="@/assets/img/ig.svg" alt="fb">
    </div>
  
    <div class="flex m-auto">
      <h1 class="m-4">© 2023, Horizon UI Library. All rights reserved.</h1>
    </div>
  
  
  </footer>
  
  </template>
  
  <script>
  export default {
    name: 'HomeView'
  }
  </script>
  
  <style scoped>
  .navbar {
  width:1140px;
  height: auto;
  }
  
  .container {
      display: flex;
  padding: 23px 0px;
  justify-content: space-between;
  align-items: center;
  align-self: stretch;
  }
  
  .navbar-left,
  .navbar-right {
    display: flex;
    align-items: center;
  }
  
  .navbar-center{
  gap: 48px;
  }
  
  .navbar-brand {
    display: flex;
    align-items: center;
    color: #fff;
    text-decoration: none;
  }
  
  .logo {
    width: 34px;
  height: 34px;
  flex-shrink: 0;
  }
  
  .horizon {
    width: 114.089px;
  height: 18.511px;
  flex-shrink: 0;
  }
  .navbar-nav {
    display: flex;
  align-items: flex-start;
  gap: 48px;
  }
  
  .nav-item {
    margin: 0 1rem;
  }
  
  .nav-link {
    color: #000;
  
  /* text-sm/Regular */
  font-family: "Plus Jakarta Sans";
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px; /* 171.429% */
  }
  
  /* .nav-link:hover {
    text-decoration: underline;
  } */
  
  .btn {
    display: flex;
  padding: 8px 16px;
  justify-content: center;
  align-items: center;
  gap: 6px;
  border-radius: 10px;
  background: #E9E3FF;
  color: var(--Primary-Purple-Blue-500, #4318FF);
  
  /* text-sm/Regular */
  font-family: "Plus Jakarta Sans";
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px; /* 171.429% */
  }
  
  
  /* .btn:hover {
    background-color: #0056b3;
  } */
  
  .frame {
    height: 640px;
  align-self: stretch;
  }
  
  .framesa{
    display: flex;
  width: 570px;
  flex-direction: column;
  align-items: flex-start;
  gap: 24px;
  }
  header {
    line-height: 1.5;
    max-height: 100vh;
  }
  
  .logo {
    display: block;
    margin: 0 auto 2rem;
  }
  
  nav {
    width: 100%;
    font-size: 12px;
    text-align: center;
    margin-top: 2rem;
  }
  
  nav a.router-link-exact-active {
    color: var(--color-text);
  }
  
  nav a.router-link-exact-active:hover {
    background-color: transparent;
  }
  
  nav a {
    display: inline-block;
    padding: 0 1rem;
    border-left: 1px solid var(--color-border);
  }
  
  nav a:first-of-type {
    border: 0;
  }
  
  @media (min-width: 1024px) {
    header {
      display: flex;
      place-items: center;
      padding-right: calc(var(--section-gap) / 2);
    }
  
    .logo {
      margin: 0 2rem 0 0;
    }
  
    header .wrapper {
      display: flex;
      place-items: flex-start;
      flex-wrap: wrap;
    }
  
    nav {
      text-align: left;
      margin-left: -1rem;
      font-size: 1rem;
  
      padding: 1rem 0;
      margin-top: 1rem;
    }
  }
  </style>