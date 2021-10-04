<template>
  <div class="container">
      <div><i class="fas fa-angle-right freccia-r"></i></div>
      <div><i class="fas fa-angle-left freccia-l"></i></div>
      <h2>Best seller</h2>
      
      <div class="centro ">Must have Products from our top seller</div>
     
      <div class="flex">
          <div class="colon">
              <img   class="resize" src="@/assets/spring_printed_dress-400x520.jpg" alt="">
              
          </div>
          <div class="colon">
              <img   class="resize" src="@/assets/modern_love_tee-400x520.jpg" alt="">
           
          </div>
          <div class="colon">
              <img   class="resize" src="@/assets/black_leather_jacket-400x520.jpg" alt="">
             
          </div>
          <div class="colon">
              <img   class="resize" src="@/assets/black_elegant_leather_jacket-400x520.jpg" alt="">
             
          </div>
          <div class="colon">
              <img   class="resize" src="@/assets/hipster_black_top-400x520.jpg" alt="">
             
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
.freccia-r{
    position: absolute;
    right: 0%;
    top: 40%;
    padding: 25px 15px;
    background-color: rgba(0, 0, 0, 0.378);
    color: white;
    font-size: 20px;
}
.freccia-l{
    position: absolute;
    left: 0%;
    top: 40%;
    padding: 25px 15px;
    background-color: rgba(0, 0, 0, 0.378);
    color: white;
    font-size: 20px;
}
.resize{
    width: 100%;
}
.colon{
    width: 20%;
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
    position: relative;
    width: 70% ;
    height: 500px;
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