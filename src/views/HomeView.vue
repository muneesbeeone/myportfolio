<script setup>
import AboutView from '../components/AboutView.vue';
import Header from '../components/Header.vue';
import SideBar from '../components/SideBar.vue';
import Experience from '../components/Experience.vue';
import Skills from '../components/Skills.vue';



</script>

<template>
  <main class="max-w-screen-2xl p-10 mx-auto bg-slate-900 h-auto">
    <Header/>
    <div class="flex md:flex-wrap flex-wrap-reverse justify-between">
      <SideBar/>
      <AboutView/>
    </div>
    <div class="flex md:flex-wrap flex-wrap-reverse justify-between md:-mt-16">
      <Skills/>
      <Experience/>
    </div>
  </main>
</template>
