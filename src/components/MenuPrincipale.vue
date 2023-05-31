<script>

export default {
  name : "MenuPrincipale",

  
  

}
</script>

<template>
    
    <section id="MenuPrincipale">
        <div class="container">
           <div class="img-and-text">
                <div class="container-img">
                    <img src="../assets/Immagini/buy-comics-digital-comics.png" alt="">
                </div>
                <div class="text">DIGITAL COMICS </div>
           </div>
           <div class="img-and-text">
                <div class="container-img">
                    <img src="../assets/Immagini/buy-comics-merchandise.png" alt="">
                </div>
                <div class="text">DC MERCHANDISE </div>
           </div>
           <div class="img-and-text">
                <div class="container-img">
                    <img src="../assets/Immagini/buy-comics-subscriptions.png" alt="">
                </div>
                <div class="text">SUBSCRIPTION </div>
           </div>
           <div class="img-and-text">
                <div class="container-img">
                    <img src="../assets/Immagini/buy-comics-shop-locator.png" alt="">
                </div>
                <div class="text">COMIC SHOP LOCATOR </div>
           </div>
           <div class="img-and-text">
                <div class="container-img">
                    <img src="../assets/Immagini/buy-comics-digital-comics.png" alt="">
                </div>
                <div class="text">DC POWER VISA </div>
           </div>
        </div>
    </section>
  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

#MenuPrincipale {
    background-color:#0282f9;
    height: 200px;
    z-index: 3;

    .container {
        display: flex;
        justify-content: space-around;
        .img-and-text {
            display: flex;
            align-items: center;
            gap: 20px;

            .text {
                color: white;
                font-weight: bold;
                font-size: 20px;
            }

            .container-img {
                width: 70px;
                img {
                    width: 100%;
                    object-fit: cover;
                }
            }
        }
    }
}




</style>