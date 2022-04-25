<template>
  <div class="mt-4 bg-no-repeat h-[90vh] bg-right" :style="{ backgroundImage: `url(${backgroundUrl})` }">
   <h1 class="flex justify-start font-bold text-2xl text-pink-800 ml-24 pt-56">I'm Maryam Khan</h1>
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