<script setup lang="ts">
const baseUrl = import.meta.env.BASE_URL;


</script>

<template>
  <main class="flex justify-center items-center w-full h-screen">
    <div>
      <button class="bg-red-500 hover:bg-red-700 text-white font-bold py-2 px-4 rounded cursor-pointer mx-auto block">
        Boton
      </button>
      <img class="mt-5" :src="`${baseUrl}/pup.jpg`"/>
    </div>
  </main>
</template>
