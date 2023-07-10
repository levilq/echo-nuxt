<script setup lang="ts">

</script>

<template>
  <div class="px-6 text-white">
    <div class="flex py-6 ">
      <h1 class="text-3xl font-bold">Главная</h1>
    </div>


    <div class="flex grid grid-cols-1 md:grid-cols-2">
      <!--        Echo recommended Banner start-->

      <div class="flex flex-none bg-cyan-500 rounded-2xl justify-between">
        <div class="my-auto mx-auto md:mx-0 p-5 md:pl-10">
          <h1 class="text-xl">Echo recommended</h1>
          <h1 class="pb-3 text-3xl font-bold">Fayz</h1>
          <OrganismsRecommendedAnimation></OrganismsRecommendedAnimation>
        </div>
        <div>
          <img class="hidden md:flex h-[22rem] pt-4 overflow-hidden object-cover"
               src="/images/banner.png" alt="artist">
        </div>

      </div>

      <!--        Echo recommended Banner end-->


      <!--        Top Charts-->
      <div class="px-6 invisible md:visible my-auto">
        <div class="flex justify-between">
          <h1 class="text-3xl font-bold">Top Charts</h1>
          <MoleculesMoreButton>больше музыки</MoleculesMoreButton>
        </div>
        <MoleculesSongCard></MoleculesSongCard>
        <MoleculesSongCard></MoleculesSongCard>
        <MoleculesSongCard></MoleculesSongCard>
      </div>
      <!--        End Charts-->
    </div>
  </div>
</template>

<style scoped>

</style>