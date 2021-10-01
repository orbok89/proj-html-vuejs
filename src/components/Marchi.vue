<template>
 <div class="sfondo">
    <div class="container2">
        <div class="centro">
            BRAND LOGOS
        </div>
        <div class="flex">
            <img src="@/assets/b_logotype_6.png" alt="">
            <img src="@/assets/b_logotype_7.png" alt="">
            <img src="@/assets/b_logotype_1.png" alt="">
            <img src="@/assets/b_logotype_2.png" alt="">
            <img src="@/assets/b_logotype_3.png" alt="">
        </div>
    </div>
 </div>
</template>

<script>
export default {

}
</script>

<style scoped  lang="scss">
    .sfondo{
        background-color: #F6F6F6;
    }
    .container2{
        width: 80% ;
        height: 200px;
        padding-top: 50px;
        margin: 0 auto;
    }
    .centro{
        text-align: center;
        padding-bottom: 20px;
    }
    .flex{
        display: flex;
        justify-content: space-between;
    }

</style>