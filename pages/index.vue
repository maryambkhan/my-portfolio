<template>
  <div>
    <div>
      <TheHeader />
    </div>
    <main class="flex flex-col min-h-screen">
      <HeroSection />
     
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