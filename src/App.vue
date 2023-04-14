<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<!-- <link rel="stylesheet" href="/./tailwind/output.css" /> -->


<template>
  <!-- <div  class="center">
    <a>
      <img src="nip.jpg" class="logo nip">
    </a>
  </div>
  <div>
    
  </div> -->

  <div class="max-w-sm rounded overflow-hidden shadow-lg nip">
  <img class="nip logo" src="nip.jpg">
  <div class="px-6 py-4">
    <div class="font-bold text-xl mb-2 name">Muhammad Anif Bin Ilham</div>
    <p class="text-gray-700 text-base text">Group Code : DWDT07</p>
    <p class="text-gray-700 text-base text">Student ID : 21FTT1288</p>
    <p class="text-gray-700 text-base text">Course : Diploma in Web Development</p>
    <br>
    <p class="text-gray-700 text-base text">Just some guy, likes things that he likes and dislikes things that he dislikes.</p>
  </div>
  <div class="px-6 pt-4 pb-2">
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#student</span>
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#webdeveloper</span>
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#poliproudbruneian</span>
  </div>
</div>

</template>


<style scoped>


.logo {
  height: 30em;
  width: auto;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

</style>
