<script>
 import ProductCard from './ProductCard.vue'
export default {
  name : "ProductList",

  components : {
    ProductCard
  },
  data() {
    return {
      listCard : [
  {
    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
]
    }
  }
  
  

}
</script>

<template>
    <section id="ProductList">
        
            <div class="container">
                <ProductCard v-for="(product,index) in listCard" :key="index"
                :details="product"/>
            </div>

    </section>
  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

#ProductList {
    background-color: black;
    height: 1000px; 
    .container {
      padding-top: 80px;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }
}

</style>