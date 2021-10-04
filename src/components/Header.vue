<template>
    <div class="container">
        <div class="sopra">
          <div class="margi80">
                <div class="iconcine">
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-instagram"></i>
                    <i class="fab fa-youtube"></i>
                </div>
                <div class="spesa">
                    <div class="shopping">
                        Shopping cart
                    </div>
                    <div class="account">
                        <div>
                            My account <i class="fas fa-angle-down ml"></i>
                        </div>
                    </div>
                    <div class="cart">
                         <i class="fas fa-shopping-cart"></i> CART <i class="fas fa-angle-down ml"></i>
                    </div>
                </div>
          </div>
            
        </div>
        <div class="sotto">
            <div class="immagi">
               <img   src="@/assets/classic_shop_logo1x.png" alt="">
            </div>
            <div class="navigatore">
                <div>Home<i class="fas fa-angle-down ml"></i></div>
                <div>Shop<i class="fas fa-angle-down ml"></i></div>
                <div>Producs<i class="fas fa-angle-down ml"></i></div>
                <div>Categories<i class="fas fa-angle-down ml"></i></div>
                <div>News</div>
                <div>Elements<i class="fas fa-angle-down ml"></i></div>
                <div class="pulsante">SHOP NOW!</div>
                <div><i class="fas fa-search"></i></div>
            </div>
        </div>
    
    </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
    .pulsante{
        background-color: #427ED1;
        padding: 7px 20px;
        color: white;
        border-radius: 20px;
        margin: 10px;
        width: 90px;
        font-size: 15px;
        height: 22px;
        line-height: 22px;
        text-align: center;
    }
    .immagi{
        width: 25%;
         height: 140px;
        line-height: 140px;

    }
    .navigatore{
        width: 65%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .sotto{
        width: 70%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
    }
    .ml{
        margin-left: 5px;
    }
    .shopping{
        width: 30%;
    }
    .account{
        display: flex;
        justify-content: center;
        align-items: center;
        width: 30%;
        border: 1px solid #d1d1d1;
        height: 70px;
    }
    .cart{
        width: 50%;
        height: 70px;
        line-height: 70px;
        text-align: center;
        background-color: #FAFAFA;
    }
    .iconcine{
        width: 15%;
        justify-content: space-between;
        display: flex;
        align-items: center;
    }
    .spesa{
        display: flex;
        align-items: center;
        width: 40%;
        height: 70px;
         
    }
    .margi80{
        
        display: flex;
        justify-content: space-between;
        width: 70%;
        margin: 0 auto;
    }
    .container{
        width: 100% ;
        height: 210px;
        
        margin: 0 auto;
    }
    .sopra{
        height: 70px;
        width: 100%;
       
        border-bottom:1px solid #d1d1d1;
    }
    .pulsante:hover{
        font-size: 12px;
        padding: 8px 20px;
        background-color: wheat;
    }
</style>