<script>

export default {
  name : "FooterUp",

  data() {
    return {
        lists1 : [
            "Characters" ,
            "Comics" ,
            "Movies" ,
            "TV", 
            "Games",
            "Videos",
            "News",
            

        ] ,

        lists2 : [ 
            "Terms of use" ,
            "Privacy polici (New)",
            "Ad Choices" ,
            "Advertising" ,
            "jobs" ,
            "Subscriptions",
            "Talent Workshops",
            "CPSC Certificates",
            "Ratings",
            "Shop Help",
            "Contact Us"

        ],

        lists3 : [
            "DC",
            "MAD Magazine",
            "DC Kids",
            "DC Universe",
            "DC Power Visa"
        ]
    }
  }

  
  

}
</script>

<template>
    
    <div id="FooterUp">
        <div class="container">
            <div class="list">
                <ul>
                    <h1> DC COMICS</h1>
                    <li v-for="item in lists1">
                        {{item}}
                    </li>
                    <h1> SHOP </h1>
                    <li>Shop DC</li>
                    <li>Shop DC Colletibles</li>
                    
                </ul>
                <ul>
                    <h1> DC</h1>
                    <li v-for="item in lists2">
                        {{item}}
                    </li>                          
                </ul>
                <ul>
                    <h1> SITES</h1>
                    <li v-for="item in lists3">
                        {{item}}
                    </li>
                </ul>
            </div>

            <div class="container-logo">
                
            </div>
        </div>
    </div>
    
  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

#FooterUp {
    
    height: 450px;
    background-image: url(../assets/Immagini/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    
    
    .container {
        display: flex;
        justify-content: space-between;
        
        .list {
            margin-top: 30px;
            width: 700px;
            display: flex;
            justify-content: space-between;
            ul { 
                color: white;
                h1 {
                    
                    font-size: 25px;
                    margin-bottom: 15px;
                    margin-top: 20px;
                }

                li {
                    font-size: 20px;
                    margin-bottom: 8px;
                    color: #4a4f4f;
                    font-weight: bold;
                }

                
            }
            
        }

        .container-logo {
            width: 600px;
            
            background-image: url(../assets/Immagini/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-size: 100%;
            background-position: top
            
            
            
          
            
        }
        
    }
}




</style>