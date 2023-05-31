<script>

export default {
  name : "Jumbotron",

  
  

}
</script>

<template>
    <section id="Jumbotron">
        <div class="container">
            <p> - - >  Content goes here &lt; - -   </p>
        </div>
    </section>
    
  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

#Jumbotron {
    background-color: black;
    height: 150px;

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