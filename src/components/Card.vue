<template>  
  <div class="w-full rounded-lg opacity-100 lg:w-2/5 shadow-2xl lg:rounded-r-lg lg:block m-8 lg:mx-0 bgClass1 text-white">  
    <div class="p-2 md:p-8 md:pb-6 text-center lg:text-left">
      <h1 class="text-3xl font-bold">Ernesto Canquiz</h1>
      <div class="mx-auto lg:mx-0 pt-3 border-b-2 border-red-300 opacity-75 text-left">      
        <div class="flex flex-wrap my-2">
          <div class="px-1 text-left">Agile Coach</div>
          <div class="px-1 text-left">&</div>   
          <div class="px-1 text-left">Fullstack Developer</div>
        </div>      
      </div>      
    </div>
    <img src="@/assets/img/index.jpeg" class="hidden rounded-lg lg:block p-10">    
    <PersonalInformation />
    <World />
    <!--Socialite /-->    
  </div>
</template>

<script lang="ts">
import PersonalInformation from '@/components/PersonalInformation.vue'
import World from '@/components/World.vue'
import Socialite from '@/components/Socialite.vue'

export default {
   components: {
    Socialite,
    PersonalInformation,    
    World
  }
}
</script>

<style scoped>

</style>
