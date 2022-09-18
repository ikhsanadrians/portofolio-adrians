<script setup>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue';
import Project from './components/Project.vue';



</script>

<template>
<header>
  <Navbar/>
</header>
  <main>
   <Home></Home>
   <About></About>
   <Skills></Skills>
   <Project></Project>
    <div class="blank w-full h-[1200px]">
    </div>
</main>
  



</template>

<style scoped>

</style>
