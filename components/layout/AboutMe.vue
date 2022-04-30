<template>
  <div>
    <div class="text-center mt-4 text-pink-800 gap-4 text">
      <h1 class="sm:text-3xl md:text-4xl lg:text-4xl mb-4 mt-10">About Me</h1>
    </div>
    <div>
      <p class="sm:text-sm md:text-xl text-pink-800 max-w-prose mx-auto">
        Hi, I am Maryam Khan. I graduated from the Web Developer at SAIT in 2022.  I think learning never stops. I try to improve my skills everyday and learn something new.
      </p>

      <div class="text-center mt-4 text-pink-800 gap-4 text">
        <h1 class="sm:text-3xl md:text-4xl lg:text-4xl mb-4 mt-4">
         Tools I'm Using!
        </h1>
      </div>
      <p class="sm:text-sm md:text-xl text-pink-800 text-center">
        HTML, CSS, Javascript, Nuxt2.js, Tailwindcss, Git, Figma, Strapi, Storyblok, Node.js
      </p>
    </div>
    <!--Icons-->
    <section class="ml-8 text-violet-700 text-xl text-center mt-8">
      <a href="http://www.codepen.io/maryambkhan">
        <font-awesome-icon
          :icon="['fab', 'codepen']"
          class="hover:text-pink-800"
        />
      </a>
      <a href="http://www.github.com/maryambkhan">
        <font-awesome-icon
          :icon="['fab', 'github']"
          class="ml-4 mr-4 hover:text-pink-800"
      /></a>
      <a href="https://www.linkedin.com/in/maryam-khan-214a44232"
        ><font-awesome-icon
          :icon="['fab', 'linkedin']"
          class="hover:text-pink-800"
        />
      </a>
    </section>
  </div>
</template>


