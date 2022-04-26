<template>
  <div>
    <div class="text-center mt-4 text-pink-800 gap-4 text">
      <h1 class="sm:text-3xl md:text-4xl lg:text-4xl mb-4 mt-4">About Me</h1>
    </div>
    <div class="max-w-md mx-auto overflow-hidden md:max-w-2xl">
      <div class="md:flex">
        <div class="md:shrink-0 mr-4 align-top">
          <img src="/images/portfolio-post.png" alt="education" class="w-65" />
        </div>
        <div
          class="
            text-left
            max-w-prose
            mx-auto
            sm:text-sm
            md:text-xl
            text-pink-800 text
          "
        >
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ab nostrum
            cumque deserunt vero delectus dolorum laboriosam earum debitis
            deleniti id, quae natus aliquam et corporis doloribus laudantium
            odio voluptatum recusandae.
          </p>
          <p></p>
          <section class="ml-8 text-violet-700 text-xl mb-2">
            <a href="http://www.codepen.io/maryambkhan">
              <font-awesome-icon
                :icon="['fab', 'codepen']"
                class="hover:text-2xl"
              />
            </a>
            <a href="http://www.github.com/maryambkhan">
              <font-awesome-icon
                :icon="['fab', 'github']"
                class="hover:text-2xl"
            /></a>
            <a href="https://www.linkedin.com/in/maryam-khan-214a44232"
              ><font-awesome-icon
                :icon="['fab', 'linkedin']"
                class="hover:text-2xl"
              />
            </a>
          </section>
        </div>
      </div>
    </div>
  </div>
</template>
