<script>
import AppHeader from './components/AppHeader.vue'
import Jumbotron from './components/Jumbotron.vue'
import MenuPrincipale from './components/MenuPrincipale.vue'
import FooterUp from './components/FooterUp.vue'
import FooterDown from './components/FooterDown.vue'
import ProductList from './components/ProductList.vue'


export default {
  components : {
      AppHeader,
      Jumbotron,
      MenuPrincipale,
      FooterUp,
      FooterDown,
      ProductList
    
  }

}
</script>

<template>
  <body>
    
      <AppHeader/>
    
    <main>
      <Jumbotron/>
      <ProductList/>
      <MenuPrincipale/>
      


    </main>
      <footer>
        <FooterUp/>
        <FooterDown/>


      </footer>
    
    
  </body>
  
</template>

<style lang="scss" >
@use "./styles/partials/variable.scss" as* ;
@use "./styles/general.scss" as* ;
</style>
