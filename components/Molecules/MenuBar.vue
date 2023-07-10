<script setup lang="ts">

</script>

<template>
  <nuxt-link :to="{ name: 'index'}">
    <div class="text-white text-3xl flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
      <AtomsHomeIcon></AtomsHomeIcon>
      <h1 class="text-lg pt-1 pl-2">Главная</h1>
    </div>
  </nuxt-link>
  <nuxt-link :to="{ name: 'index'}">
    <div class="text-white text-3xl flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
      <AtomsBlogIcon></AtomsBlogIcon>
      <h1 class="text-lg pt-1 pl-2">Главная</h1>
    </div>
  </nuxt-link>

</template>

<style scoped>

</style>