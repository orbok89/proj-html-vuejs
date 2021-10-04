<template>
 
      <div class="container">
         
        <div class="promo-1">
          <div class="margine">
                <div class="grande">Winter Collection</div>
                <div class="testo">
                     STYLISH AND WARM
                </div>
                <div class="pulsante"> VIEW MORE</div>
          </div>
        </div>
        <div class="promo-2">
          <div class="margine">
                <div class="grande">Spring Collection</div>
                <div class="testo">
                     BRIGHT AND COLORFUL
                </div>
                <div class="pulsante"> VIEW MORE</div>
          </div>
        </div>
                <div class="promo-3">
          <div class="margine">
                <div class="grande">Autumn Collection</div>
                <div class="testo">
                     RICH AND CONFORTABLE
                </div>
                <div class="pulsante"> VIEW MORE</div>
          </div>
        </div>
  </div>
 
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
.margine{
     
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.testo{
   text-align: center;
   margin: 10px 0;
}
.grande{
    font-size: 40px;
    margin-top: 200px;
}
 
    .promo-1{
        width: 33%;
        height: 400px;
        background-image: url('../assets/winter_collection_bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
         
      
    }
    .promo-2{
         width: 33%;
        height: 400px;
        background-image: url('../assets/spring_collection_bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        
    }
     .promo-3{
         width: 33%;
        height: 400px;
        background-image: url('../assets/autumn_collection_bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        
    }
    .container{
        width: 100% ;
        height: 400px;
        color: white;
        margin: 0 auto;
        display: flex;
         
    }
    img{
        width: 30%;
    }
      .pulsante{
          width: 100px;
      border-radius: 15px;
      border: 2px solid white;
      margin: 10px;
      color: white;
      padding: 10px;
      background-color: rgba(255, 255, 255, 0.179);
      text-align: center;
    }
</style>