<script>

export default {
  name : "Jumbotron",

  
  

}
</script>

<template>
    <section id="Jumbotron">
        <div class="container">
            
        </div>
    </section>
    
  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

#Jumbotron {
    background-image: url(../assets/Immagini/jumbotron.jpg);
    height: 600px;
    background-repeat: no-repeat;
    background-size: cover;

    .container {
        display: flex;
        align-items: center;
        
        p {
            color: white;
            font-size: 30px;
           
        }
    }
}


</style>