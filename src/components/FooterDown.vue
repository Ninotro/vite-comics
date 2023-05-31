<script>

export default {
  name : "FooterDown",

  
  

}
</script>

<template>
  <div id="FooterDown">
        <div class="container">
           <div class="button">
            SIGN-UP NOW!
           </div>

           <div id="social">
                <div id="follow-us">FOLLOW US</div>
                <div class="container-logo-img">
                    <img src="../assets/Immagini/footer-facebook.png" alt="">
                </div>
                <div class="container-logo-img">
                    <img src="../assets/Immagini/footer-twitter.png" alt="">
                </div>
                <div class="container-logo-img">
                    <img src="../assets/Immagini/footer-youtube.png" alt="">
                </div>
                <div class="container-logo-img">
                    <img src="../assets/Immagini/footer-pinterest.png" alt="">
                </div>
                <div class="container-logo-img">
                    <img src="../assets/Immagini/footer-periscope.png" alt="">
                </div>
           </div>
        </div>
    </div>
    
  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

#FooterDown {
    background-color:#303030;
    height: 180px;
    z-index: 5;
    

    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        
        
      .button {
        font-size: 20px;
        color: white;
        padding: 20px;
        font-weight: bold;
        text-align: center;
        width: 200px;
        border: 2px solid #0282f9;;
      }

      #social {
        display: flex;
        align-items: center;
        gap: 30px;
        #follow-us {
            color: #0282f9;
            font-weight: bold;
            font-size: 30px;
        }

        .container-logo-img {
            width: 60px;

            img {
                width: 100%;
                object-fit: cover;
            }
        }
      }
    }
}



</style>