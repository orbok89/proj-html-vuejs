<template>
    <div class="container">
        <h2>From Our Blog</h2>
        <div class="centro">The latest Classic Shop news</div>
        <div class="prova">
            <div class="colonnina">
               <img  class="resize" src="@/assets/post_img_10-300x188.jpg" alt="">
               <div class="mt"><strong> la ragazza nella natura</strong></div>
               <div class="mb">lorem ipsumm</div>
               <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus et nam placeat suscipit magnam nemo nihil consequatur quasi aperiam. Officiis itaque consequuntur provident esse ea in est ipsum porro ipsa!</div>
            </div>
            <div class="colonnina">
                <img class="resize" src="@/assets/post_img_11-300x188.jpg" alt="">
                <div class="mt"><strong> la ragazza nella natura</strong></div>
                <div class="mb">lorem ipsumm</div>
                <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus et nam placeat suscipit magnam nemo nihil consequatur quasi aperiam. Officiis itaque consequuntur provident esse ea in est ipsum porro ipsa!</div>
            
            </div>
            <div class="colonnina">
                <img class="resize" src="@/assets/post_img_12-300x188.jpg" alt="">
                <div class="mt"><strong> la ragazza nella natura</strong></div>
                <div class="mb">lorem ipsumm</div>
                <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus et nam placeat suscipit magnam nemo nihil consequatur quasi aperiam. Officiis itaque consequuntur provident esse ea in est ipsum porro ipsa!</div>
            
            </div>
        </div>
         
    </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
.mt{
    margin-top: 5px;
}
.mb{
    margin-bottom: 5px;
}
.resize{
    width: 100%;
}
 
.prova{
    display: flex;
    justify-content: space-between;
    width: 100%;
    margin: 0;
}
.colonnina{
     
    width: calc(100% / 3 - 10px);
     
}
    .container{
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
</style>