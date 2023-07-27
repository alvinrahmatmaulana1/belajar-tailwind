<template>
  <div>
    <Navbar></Navbar>
  </div>
  <div>
    <Jumbotron></Jumbotron> <br>
    
  </div>
  <div>
    <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white"><center>Hewan</center></h1>
    <Content></Content>
  </div>
  <br>
  <div>
    <Kontak></Kontak>
  </div>
  <div>
    <Footer></Footer>
  </div>
    
  
</template>
<script setup>
import 'flowbite/dist/flowbite.js'
import Navbar from './Navbar.vue';
import Footer from './Footer.vue'
import Jumbotron from './Jumbotron.vue'
import Content from './Content.vue'
import Kontak from "./Kontak.vue";
</script>
