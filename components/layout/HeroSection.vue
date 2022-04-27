<template>
  <div class="mt-4 bg-no-repeat h-[90vh] bg-right mr-28" :style="{ backgroundImage: `url(${backgroundUrl})` }">
   <h1 class="flex justify-start font-bold text-2xl text-pink-800 ml-28 pt-56 underline decoration-sky-500">I'm Maryam Khan</h1>
   <p class="flex justify-start text-xl text-pink-800 ml-28">Front-End Dev and Web Designing</p>
    <button  type="submit" id="submit" class="hover:bg-pink-900 ml-28 bg-pink-800 text-white p-2 text-2xl rounded-md mt-4"><a href="/contact">Contact me</a></button>
    <section class=" text-pink-800 text-xl ml-28 mt-4">
     <a href="http://www.codepen.io/maryambkhan"> <font-awesome-icon :icon="['fab', 'codepen']" class="hover:text-2xl"/> </a>
     <a href="http://www.github.com/maryambkhan"> <font-awesome-icon :icon="['fab', 'github']" class="ml-4 mr-4 hover:text-2xl" /></a>
		 <a href="https://www.linkedin.com/in/maryam-khan-214a44232"><font-awesome-icon :icon="['fab', 'linkedin']" class="hover:text-2xl"/> </a>
    </section>
	</div>
</template>

<script>
import backgroundUrl from '/assets/images/hero.webp'
export default {
  data() {
    return { backgroundUrl }
  }
}
</script>
<style>
body{
  cursor: pointer;
}
</style>