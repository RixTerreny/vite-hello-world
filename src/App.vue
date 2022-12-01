<script>
export default{components:{ AppTitle, AppHero }, img:{AppHero}}
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
</script>

<template>
  <div class="body pt-3">
    <header>
      <AppTitle class="text-white text-center "></AppTitle>
    </header>

    <body>
      <AppHero class="text-center mt-4"></AppHero>
    </body>
  </div>
  
</template>

<style>
.body{
  height: 100vh;
  background-color: var(--bs-purple); 
}
</style>