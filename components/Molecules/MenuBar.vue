<script setup lang="ts">

</script>

<template>
  <nuxt-link :to="{ name: 'index'}">
    <div class="text-white text-[28px] flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
        <AtomsHomeIcon class="my-auto"></AtomsHomeIcon>
      <h1 class="text-lg pl-2 my-auto">Главная</h1>
    </div>
  </nuxt-link>
  <nuxt-link :to="{ name: 'public-search'}">
    <div class="text-white text-[28px] flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
      <AtomsSearchIcon></AtomsSearchIcon>
      <h1 class="text-lg pl-2 my-auto">Поиск</h1>
    </div>
  </nuxt-link>
  <nuxt-link :to="{ name: 'public-blogs'}">
    <div class="text-white text-[28px] flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
      <AtomsBlogIcon></AtomsBlogIcon>
      <h1 class="text-lg pl-2 my-auto">Блог</h1>
    </div>
  </nuxt-link>
  <nuxt-link :to="{ name: 'public-artists'}">
    <div class="text-white text-[28px] flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
      <AtomsArtistIcon></AtomsArtistIcon>
      <h1 class="text-lg pl-2 my-auto">Исполнители</h1>
    </div>
  </nuxt-link>
  <nuxt-link :to="{ name: 'public-songs'}">
    <div class="text-white text-[28px] flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
      <AtomsMusicIcon></AtomsMusicIcon>
      <h1 class="text-lg pl-2 my-auto">Песни</h1>
    </div>
  </nuxt-link>
  <nuxt-link :to="{ name: 'public-videos'}">
    <div class="text-white text-[28px] flex hover:bg-zinc-800 py-2 pl-2 rounded-lg hover:ease-in hover:duration-100 mx-1">
      <AtomsVideoIcon></AtomsVideoIcon>
      <h1 class="text-lg pl-2 my-auto">Видео</h1>
    </div>
  </nuxt-link>

</template>

<style scoped>

</style>