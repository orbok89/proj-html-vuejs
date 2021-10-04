<template>
  <div class="container">
      <h2>Featured Products</h2>
      <div class="centro ">Must have Products from our top seller</div>
      <div class="centro ">
          <span>Men</span><span class="no-border">Women</span><span>Accessories</span>
      </div>
      <div class="flex">
          <div class="colon">
              <img   class="resize" src="@/assets/black_elegant_leather_jacket-400x520.jpg" alt="">
              <div class="mtb"><strong>Black Leather Jacket</strong></div>
              <div class="mtb">Men,Jacket,Jeans</div>
              <div class="mtb">$200</div>
          </div>
          <div class="colon">
              <img   class="resize" src="@/assets/black_leather_suit-400x520.jpg" alt="">
              <div class="mtb"><strong>Black Leather Jacket</strong></div>
              <div class="mtb">Men,Jacket,Jeans</div>
              <div class="mtb">$200</div>
          </div>
          <div class="colon">
              <img   class="resize" src="@/assets/blue_jacket_and_white_stripe_tee-400x520.jpg" alt="">
              <div class="mtb"><strong>Black Leather Jacket</strong></div>
              <div class="mtb">Men,Jacket,Jeans</div>
              <div class="mtb">$200</div>
          </div>
          <div class="colon">
              <img   class="resize" src="@/assets/black_elegant_leather_jacket-400x520.jpg" alt="">
              <div class="mtb"><strong>Black Leather Jacket</strong></div>
              <div class="mtb">Men,Jacket,Jeans</div>
              <div class="mtb">$200</div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
.resize{
    width: 100%;
}
.colon{
    width: 25%;
}
.mtb{
    margin: 15px 0;
}
.flex{
    display: flex;
}
.no-border{
    border-left: 0px;
    border-right: 0px;
    background-color: #F6F6F6;
}
 span{
        border: 1px solid gray;
        padding: 10px 25px;
        ;
    }
.container{
    width: 70% ;
    height: 650px;
    margin: 0 auto;
}
h2 {
  overflow: hidden;
  text-align: center;
}

h2:before,
h2:after {
  background-color:  #d1d1d1;
  content: "";
  display: inline-block;
  height: 1px;
  position: relative;
  vertical-align: middle;
  width: 50%;
}

h2:before {
  right: 20px;
  margin-left: -50%;
}

h2:after {
  left: 20px;
  margin-right: -50%;
}
.centro{
    text-align: center;
    margin-bottom: 30px;
}
.centro{
    text-align: center;
    margin-bottom: 30px;
}
</style>