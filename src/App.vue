<template>
  <div id="app">
      <app-header></app-header>
      <router-view></router-view>
      
      <app-fotter></app-fotter>
      
  </div>
</template>
36
<script>
import Fotter from './components/common/Fotter'
import Header from './components/common/Header'
export default {
  


  components : {
       appFotter : Fotter,
       appHeader : Header
  }
 
 
}
</script>

<style>
</style>
