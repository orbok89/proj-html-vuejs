<template>
  <div class="container">
    <img class="resize " src="@/assets/man_testimonial.png" alt="">
    <div class="centro">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste, amet aliquam. Voluptatibus et debitis ea, fuga dolores id commodi libero hic ut ullam, aperiam culpa sed nostrum inventore ratione illum.
    </div>
    <div class="centro">
      <strong>Dario Pineda</strong>, Theme fusion
    </div>
    <div class="centro">
      <i class="far fa-circle margine"></i>
      <i class="fas fa-circle margine"></i>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
     .container{
        width: 100% ;
        height: 400px;
        background-image: url('../assets/testimonials_home_1_bg.jpg');
        background-size: cover;
        margin: 0 auto;
        color: white;
         
    }
    .resize{
      width: 70px;
       display: block;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 30px ;
    padding-top: 80px;
    }
    .centro{
      text-align: center;
      width: 50%;
      margin: 0 auto;
      margin-bottom: 30px;
    }
   .margine{
     margin: 15px 5px;
   }
</style>