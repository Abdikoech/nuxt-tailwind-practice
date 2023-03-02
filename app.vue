<template> 
<section>
  <div class=" bg-gradient-to-r from-red-400 to-neutral-800 flex flex-row
     gap-4 justify-between">
        <!---logo-->
        <div class=" p-7">
            <h1 class=" text-4xl font-bold">YOLO</h1>
        </div>
        <!---navbar--->
  <div  class=" items-center justify-center flex flex-row p-8 gap-7 font-bold text-3xl">
    <nuxt-link to="/Home">Home</nuxt-link>
    <nuxt-link to="/Port">Port</nuxt-link>
    <nuxt-link to="/Login">Login</nuxt-link>
  </div>
  <!---Signup--->
        <div class=" p-7">
          <a class=" text-4xl font-bold" href="#">Sign up</a>
        </div>
    </div>
</section>
  <div>
    <NuxtPage/>
  </div>
 
</template>
