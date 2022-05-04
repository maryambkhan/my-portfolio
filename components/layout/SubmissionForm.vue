<template>
<div>
	<!--form-->
     <section class="mx-auto mt-2 bg-gray-300 max-w-6xl py-12 px-12">
			 <div class="text">
			 <h1 class="text-center text-pink-800 text-4xl mb-4 font-bold">GET IN TOUCH !</h1></div>
  <form action="https://formspree.io/f/mgedpkbn" method="POST"  class="flex justify-center">
    <fieldset>
        <!--first name-->
      <div>
        <label for="user" class="after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Full Name</label>
        <input type="text" name="firstname" id="user"  required="" class="sm:w-11/12 md:w-full mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2" >
        </div>
       
      <!--email-->
      <div>
        <label for="email" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Email</label>
        <input type="email" name="email" id="email"  required="" class="sm:w-11/12 md:w-full mt-2 px-3 py-2 bg-white rounded-md border  border-slate-500  ml-2 " >
      </div>

      <!--message-->
      <label for="message" class="mt-2 after:content-['*'] after:ml-0.5 after:text-red-700 block text-lg  text-slate-700 font-bold">Message</label>
      <textarea type="message" name="message" id="message" rows="4" cols="20"  required="" class="sm:w-11/12 md:w-full mt-2 px-3 py-2 bg-white border rounded-md border-slate-500 ml-2 " > 
      </textarea>
  
      <!--button-->
      <div class="-mx-3 md:flex mt-2">
          <div class="md:w-full px-3">
      <button  type="submit" id="submit" class="hover:bg-pink-900  bg-pink-800 text-white p-2 text-2xl rounded-md">Submit</button>
          </div>
      </div>
    </fieldset>
  </form>
  </section>
</div>
</template>

