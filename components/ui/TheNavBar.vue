<template>
  <div class="sm:flex sm:justify-center">
    <div class="sm:hidden ">
      <button @click="isOpen = !isOpen" type="button" class="hover:text-slate-600">
        <span class="font-semibold text-white text-xl ml-4">Menu</span>
      </button>
    </div>
    <div class="text">
    <div :class="isOpen ? 'block' : 'hidden'" class="items-center px-2 pt-2 pb-4 sm:flex">
    <NuxtLink to="/" class="block px-4 py-2 sm:text-2xl lg:text-2xl font-semibold text-white">About Me</NuxtLink>
    <NuxtLink  to="/education" class="block   px-4 py-2 sm:text-2xl lg:text-2xl font-semibold text-white" >Education</NuxtLink>
    <NuxtLink to="/project" class="block px-4 py-2  sm:text-2xl lg:text-2xl font-semibold text-white">Project</NuxtLink>
  </div>
  
    </div>
  </div>
</template>


<script setup>
export default {
    data() {
      return {
        isOpen: false,
      };
    },
  };
</script>