<script>

export default {
  name : "ProductCard",
  props: {
    details: Object
  }

  
  

}
</script>

<template>
    <div class="container-card">
        <div class="container-img">
            <img :src="details.thumb" alt="">
        </div>
        <h3>{{details.series}}</h3>
    </div>
  
</template>

<style lang="scss" scoped >

@use "../styles/general.scss" as* ;

.container-card {
    width: calc(100%/6 - 20px);
    
    height: 450px;
    .container-img {
        width: 100%;
        height: 350px;
        img {
            width: 100%;
            height: 100%;
            object-fit: contain
        }
    }
    h3 {
        color: white;
        text-align: center;
        font-size: 30px;
        margin-top: 20px;
    }
}

</style>