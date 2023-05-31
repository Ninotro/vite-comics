<script>

export default {
  name : "AppHeader",

  data() {
    return {
        lists : [
            "CHARACTERS" ,
            "COMICS" ,
            "MOVIES" ,
            "TV", 
            "GAMES",
            "COLLECTIBLES",
            "VIDEOS",
            "FANS",
            "NEWS",
            "SHOP",

        ]
    }
  }
  

}
</script>

<template>

    <header>
    
        <div class="container-img">
            <img src="../assets/Immagini/dc-logo.png" alt="logo">
        </div>

        <div>
            <ul>
                <li v-for="list in lists">
                    <a href="#">{{list}}</a>
                </li>
            </ul>
        </div>


    </header>

  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

header {
    margin: 30px 10%;
    
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: white;
    color: black;
    div {

        ul {
            display: flex;
            
            li{
                list-style-type: none;
                padding-right: 10px;
                font-size: 22px;
                font-weight: bold;
               
            }
            
        }
        
    }
    .container-img {
        width: 200px;
        img {
            object-fit: cover;
            max-width: 100%;
        }
    }
}
</style>