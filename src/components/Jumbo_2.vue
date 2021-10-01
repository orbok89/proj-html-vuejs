<template>
  <div class="container">
       <img src="@/assets/winter_collection_bg.jpg" alt="">
       <img src="@/assets/spring_collection_bg.jpg" alt="">
       <img src="@/assets/autumn_collection_bg.jpg" alt="">
  </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
    .container{
        width: 100% ;
        height: 450px;
       
         
    }
    img{
        width: calc(100% / 3);
        object-fit:cover;
        height: 400px;
        object-position:top; 
    }
</style>