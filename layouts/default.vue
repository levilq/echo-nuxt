<script setup lang="ts">

</script>

<template>
  <div class="flex flex-col h-screen text-white">
    <div class="bg-blue-500 flex-1 flex overflow-y-hidden">
      <div class="sidebar bg-black w-60 flex-none flex flex-col hidden md:flex ">
          <div>
            <img class="h-16 mx-auto mt-2" src="/images/echo-wb-logo.png" alt="logo">
          </div>
          <MoleculesMenuBar />

      </div>
      <div class="content-area bg-zinc-900 flex-1 overflow-y-auto">
        <slot />
        <OrganismsFooter />
      </div>
    </div>
    <div class="bg-blue-300">bottom</div>
  </div>
</template>

<style scoped>

</style>