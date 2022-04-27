<template>
  <div>
    <div>
      <TheHeader />
    </div>
    <main class="flex flex-col min-h-screen">
      <HeroSection />
      <section
        class="
          flex
          justify-center
          animate-bounce
          fill-blue-800
          bg-gray-300
          rounded-full
          p-2
          h-14
          w-14
          m-auto
          mt-4
        "
      >
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
          <!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
          <path
            d="M192 384c-8.188 0-16.38-3.125-22.62-9.375l-160-160c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0L192 306.8l137.4-137.4c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25l-160 160C208.4 380.9 200.2 384 192 384z"
          />
        </svg>
      </section>
      <SkillsCards />
      <p class="text-xl text-center mt-8 text-pink-800 text">You want to learn more <button  type="submit" id="submit" class="hover:bg-pink-900 bg-pink-800 text-white p-2 text-2xl rounded-md mt-4 text"><a href="/about"> about me</a></button></p>
     
    </main>
    <TheFooter />
  </div>
</template>



<style>
body {
  cursor: pointer;
}

.text {
  font-family: cursive;
}
</style>