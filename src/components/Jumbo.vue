<template>
  <div class="container">
       <div class="bran">Brand New Arrival</div>
       <div class="margini">NEW COLLECTION FROM NUOVA YORK</div>
       <div class="flex">
         <div class="pulsante">VIEW ALL</div>
         <div class="pulsante">LOOKBOOK</div>
       </div>
        <div class="piccolo "> <i class="fab fa-cc-jcb"></i> demos</div>
        <div class="piccolo due">
           <div class="verde">
             <div class="dollaro">$</div> 39
             </div> 
             
             <div>on sale </div>
           </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
  .dollaro{
    font-size: 12px;
    position: absolute;
    z-index: 99;
    top: 0%;
    left: 3px;
  }
  .verde{
    color: #65BC7B;
    width: 45px;
    height: 25px;
    font-size: 25px;
    position: relative;
    
  }
  .piccolo{
    width: 45px;
    height: 45px;
    background-color: white;
    position: absolute;
    top: -5px;
    right: 5px;
    border-radius: 10px;
    color: black;
    box-shadow: 0px -5px 5px grey;
    padding: 5px;
     
  }
  .due{
    top: 60px;
  }
    .margini{
      margin: 10px;
    }
    .pulsante{
      border-radius: 15px;
      border: 2px solid white;
      margin: 10px;
      color: white;
      padding: 10px;
      background-color: rgba(255, 255, 255, 0.179);
    }
    .container{
        position: relative;
        width: 100% ;
        height: 400px;
        background-image: url('../assets/home1_slide_three_bg_2.jpg');
        background-size: cover;
        margin: 0 auto;
        text-align: center;
        color: white;
        padding-top: 1px;
         
    }
    .flex{
      display: flex;
      justify-content: center;
    }
    .bran{
      margin-top: 150px;
      font-size: 45px;
    }
</style>