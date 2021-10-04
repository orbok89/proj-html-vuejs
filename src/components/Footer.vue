<template>
  <div class="container">
      <div class="riga-1">
          <div class="contenitore-1">
              <div class="flex">
                  <div>
                  <i class="far fa-envelope lettera"></i>
              </div>
              <div class="sottoscrizione">
                  Subcribe now and get special offert
              </div>
              </div>
              <div class="flex">
                  <div><input type="text" placeholder="Insert your mail"></div>
              <div class="pulsante">SEND</div>
              </div>
          </div>
      </div>
      <div class="riga-2">
          <div class="contenitore-2">
              <div class="colonna">
                  <img  class="resize" src="@/assets/classic_shop_logo_footer.png" alt="">
                  <div class="mt">13455 North Main street</div>
                  <div  class="mt">Nueva York, NY 55555</div>
                  <div  class="mt">Phone 1.800.55555</div>
                  <div  class="mt">Email:info@company.it</div>
                  <div class="mt">Web: Theme-fusione.com</div>
                  <div class="mt20">
                      <i class="fab fa-facebook-f mr"></i>
                    <i class="fab fa-twitter mr"></i>
                    <i class="fab fa-instagram mr"></i>
                    <i class="fab fa-youtube mr"></i>
                  </div>
              </div>
              <div class="colonna">
                  <div class="mb">
                      TOP RATED PRODUCT
                  </div>
                  <div class="flex-avatar mt">
                    <div>
                        <div> Leather gloves</div>
                        <div class="mtb"><i class="fas fa-star "></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                        <div> $45</div>
                    </div>
                    <div> <img  class="resize-avatar" src="@/assets/leather_gloves-120x156.jpg" alt=""></div>

                  </div>
                    <div class="flex-avatar mt">
                    <div>
                        <div> Leather gloves</div>
                        <div class="mtb"><i class="fas fa-star "></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                        <div> $45</div>
                    </div>
                    <div> <img  class="resize-avatar" src="@/assets/leather_gloves-120x156.jpg" alt=""></div>

                  </div>
                    <div class="flex-avatar mt">
                    <div>
                        <div> Leather gloves</div>
                        <div class="mtb"><i class="fas fa-star "></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                        <div> $45</div>
                    </div>
                    <div> <img  class="resize-avatar" src="@/assets/leather_gloves-120x156.jpg" alt=""></div>

                  </div>
              </div>
              <div class="colonna">
                  <div class="mb">
                      RECENT POST
                  </div>
                  <div class=" post">
                      <i class="fas fa-angle-right "></i> Lorem ipsum dolor sit  consectetur  
                  </div>
                  <div class=" post">
                      <i class="fas fa-angle-right "></i> Lorem ipsum dolor sit  consectetur  
                  </div>
                  <div class=" post">
                      <i class="fas fa-angle-right "></i> Lorem ipsum dolor sit  consectetur  
                  </div>
                  <div class=" post">
                      <i class="fas fa-angle-right "></i> Lorem ipsum dolor sit  consectetur  
                  </div>
                  <div class=" post">
                      <i class="fas fa-angle-right "></i> Lorem ipsum dolor sit  consectetur  
                  </div>
                 <div class=" post">
                      <i class="fas fa-angle-right "></i> Lorem ipsum dolor sit  consectetur  
                  </div>
              </div>
              <div class="colonna">
                  <div class="mb" >TAGS</div>
                  <div class="tag">
                      <span>Black</span> <span>boot</span> <span>Brown</span> <span>casual</span> <span>D&G</span> <span>Fabric</span> <span>flower</span> <span>grey</span> <span>hat</span> <span>hipster</span> <span>lines</span> <span>multi-purpose</span> <span>Nueva York</span> <span>Outdoors</span> <span>red</span> <span>responsive</span> <span>summer</span> <span>sweater</span> <span>Travel</span> <span>Warm</span> <span>White</span> <span>winter</span>
                  </div>
              </div>
          </div>
      </div>
      <div class="riga-3">
          <div class="centratura"> Copyright 2012-2020  |  Avada Theme by Theme Fusion  |  All rights Reserved  |  Powered by WordPress </div>
            <div class="pagamenti"><i class="fab fa-cc-visa mr"></i> <i class="fab fa-cc-paypal marg"></i> <i class="fab fa-cc-mastercard"></i><i class="fab fa-cc-discover"></i><i class="fab fa-amazon"></i></div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
    .marg{
        padding: 50px;
        margin: 33px;
    }
    .pagamenti{
        margin: 0 auto;
        font-size: 30px;
        color: white;
        text-align: center;
           width: 15%;
        justify-content: space-between;
        display: flex;
        align-items: center;
    }
    .riga-3{
        background-color: #1D1F22;
    }
    .centratura{
        text-align: center;
        padding: 20px;
        
        color: white;
    }
    .tag{
        
        display: flex;
        flex-wrap: wrap;
    }
    .mb{
        margin-bottom: 20px;
    }
    span{
        border: 1px solid gray;
        padding: 5px;
        margin:  3px;
    }
    .post{
        border-bottom: 1px solid gray;
        padding:  13px 0;
    
    }
    .mtb{
        margin: 15px 0;
    }
     .flex-avatar{
        display: flex;
        align-items: center;
        justify-content: space-between  ;
        width: 100%;
        height: 100px;
        border-bottom: 1px solid gray;
    }
    .resize-avatar{
        width: 60px;
    }
    .mr{
        margin-right: 10px;
    }
    .mt20{
         margin-top: 40px;
    }
    .mt{
        margin-top: 5px;
    }
    .resize{
        width: 80%;
        margin: 0 auto;
        margin-bottom: 40px;
    }
    .colonna{
        width: 25%;
        height: 350px;
        padding: 5px;
        
    }
    .contenitore-2{
        display: flex;
        width: 80%;
        height: 350px;
        margin: 0 auto;
        padding-top: 50px;
        color: white;
    }
    .riga-2{
        background-color: #2B2E32;
        width: 100%;
        height: 450px;
    }
    .lettera{
        background-color: #2B2E32;
        padding: 20px;
        color: #74797F;
        font-size: 25px;
        border-radius: 50%;
        margin-right:10px ;
    }
    .sottoscrizione{
        color: white;
        font-size: 30px;
    }
    input{
        border-radius: 20px;
        padding: 7px 20px;
    }
    .flex{
        display: flex;
        align-items: center;
    }
 .pulsante{
        background-color: #427ED1;
        padding: 7px 20px;
        color: white;
        border-radius: 20px;
        margin: 10px;
    }
    .contenitore-1{
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 80%;
        height: 150px;
        margin: 0 auto;
    }
    .riga-1{
        width: 100%;
        height: 150px;
        background-color: #303337;
    }
    .container{
        width: 100% ;
        height: 200px;
        background-color: aquamarine;
        
    }
</style>