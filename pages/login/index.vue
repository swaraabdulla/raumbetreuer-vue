<template>
  <div class="flex flex-col h-96 w-4/5 xs:w-96 bg-white rounded-3xl items-center">
    <span class="text-gray-400 text-2xl mt-8">Login-Raumbetreuer</span>

    <Input
      class="w-4/5 mt-2"
      placeholder="E-Mail"
    />

    <input
      class="w-4/5 mt-8"
      placeHolder="Passwort"
      type="password"
    />

    <div class="flex flex-col items-center w-3/5 gap-4 mt-8">
      <button class="bg-gray-300 text-gray-500 w-full h-12 rounded-2xl text-xl">
        Anmelden
      </button>
      <div class="flex flex-col items-center">
        <button class="cursor-pointer text-gray-500 hover:text-primary">
          Passwort Zurücksetzen
        </button>
        <button class="cursor-pointer text-gray-500 hover:text-primary">
          Registrieren
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
