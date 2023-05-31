<script>
import AppHeader from './components/AppHeader.vue'
import Jumbotron from './components/Jumbotron.vue'
export default {
  components : {
      AppHeader,
      Jumbotron

  }

}
</script>

<template>
  <body>
    
      <AppHeader/>
    
    <main>
      <Jumbotron/>
    </main>
    
    
  </body>
  
</template>

<style lang="scss" >
@use "./styles/partials/variable.scss" as* ;
@use "./styles/general.scss" as* ;
</style>
