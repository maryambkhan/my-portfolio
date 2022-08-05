<template>
  <div>
    <!--About Me-->
    <h1 class="ml-8 pt-10 font-semibold text-2xl text-gray-500">
    Hi👋, My name is <span class="text-white text-2xl">Maryam Khan</span>.
    I recently finished my <span class="text-white text-2xl">Web Developer</span> program at <span class="text-white text-2xl">SAIT</span>.
    I learned these frameworks <span class="text-white text-2xl">Vue and Nuxt</span> in school. I'm also learning <span class="text-white text-2xl">React</span>.
    My favourite CSS Framework is <span class="text-white text-2xl">TailwindCSS</span>, I'm looking forward to learn more CSS frameworks.
    I think learning never stops. I try to improve my skills everyday and learn something new.</h1>
    <h1 class="ml-8 pt-10 font-semibold text-2xl text-gray-500">
      Tools I'm Using! <span class="text-white text-2xl">HTML, Tailwindcss, CSS, Javascript, Nuxt.js, Vue.js, Reactjs, Git, Figma, Strapi, Storyblok,
      Node.js</span>
    </h1>
    <!--Social Media-->
    <section class="flex ml-8 text-white text-xl mt-4">
      <p class=" text-gray-500 font-semibold text-2xl ">Find Me on</p>
      <a href="http://www.codepen.io/maryambkhan">
        <font-awesome-icon :icon="['fab', 'codepen']" class="ml-4 hover:bg-gray-500" />
      </a>
      <a href="http://www.github.com/maryambkhan">
        <font-awesome-icon :icon="['fab', 'github']" class="ml-4 mr-4 hover:bg-gray-500"
      /></a>
      <a href="https://www.linkedin.com/in/maryam-khan-214a44232"
        ><font-awesome-icon :icon="['fab', 'linkedin']" class="hover:bg-gray-500" />
      </a>
    </section>
    
     
  </div>
</template>


<style>
body {
  cursor: pointer;
}
</style>