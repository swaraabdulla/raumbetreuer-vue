<script setup>

</script>
<template>
  <div class="flex flex-col h-full">
    <div class="flex bg-primary justify-center items-center p-6">
      <span class="text-white sm:text-4xl xs:text-xl text-2xl">
          Georg-Simon-Ohm-Berufskolleg
        </span>

      <div class="flex items-center justify-between space-x-4 bg-primary ml-auto">
        <span class="flex text-white text-3xl">Max Mustermann</span>
        <div class="flex gap-6">
          <button class="bg-secondary w-32 h-12 rounded-3xl text-white text-xl">Ausloggen</button>
        </div>
      </div>
    </div>
    <div class="flex flex-col w-full h-full bg-backgroundGray justify-center items-center">
      <Nuxt />
    </div>
    <div class="flex w-full h-16 py-3 bg-black self-bottom text-xs justify-center items-center">
      <span class="text-white">©Georg-Simon-Ohm Berufskolleg 2022</span>
    </div>
  </div>
</template>
