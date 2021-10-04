<template>
  <div class="confetti">
      <div class="container">
         
        <div class="promo-1">
          <div class="margine">
                <div class="grande">70% off</div>
                <div class="testo">
                     ratione assumenda deleniti placea quaerat repellendus 
                </div>
                <div class="pulsante"> VIEW MORE</div>
          </div>
        </div>
        <div class="promo-2">
          <div class="margine">
                <div class="grande">Free shipping</div>
                <div class="testo">
                     ratione assumenda deleniti placea quaerat minus?
                </div>
                <div class="pulsante"> VIEW MORE</div>
          </div>
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
    margin: 30px;
}
.testo{
    line-height: 200%;
    width: 50%;
}
.grande{
    font-size: 50px;
}
.confetti{
    background-image: url('../assets/bkgd_confetti-compressor.jpg');
}
    .promo-1{
        width: calc( 50% - 20px);
        height: 400px;
        background-image: url('../assets/promo_box_1_bg.jpg');
        background-size: contain;
        background-repeat: no-repeat;
         
        margin: 50px 10px;
    }
    .promo-2{
         width: calc( 50% - 20px);
        height: 400px;
        background-image: url('../assets/promo_box_2_bg.jpg');
        background-size: contain;
        background-repeat: no-repeat;
        margin:  50px 10px;
    }
    .container{
        width: 70% ;
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