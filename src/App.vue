<template>
  <div id="app">
    <Header/>
    <Jumbo/>
    <F_product/>
    <Jumbo_2/>
    <Best_seller/>
    <Jumbo_3/>
    <New_arrival/>
    <Jumbo_4/>
    <Vlog/>
    <Carrello/>
    <Marchi/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import F_product from './components/F_product.vue'
import Jumbo_2 from './components/Jumbo_2.vue'
import Best_seller from './components/Best_seller.vue'
import Jumbo_3 from './components/Jumbo_3.vue'
import New_arrival from './components/New_arrival.vue'
import Jumbo_4 from './components/Jumbo_4.vue'
import Vlog from './components/Vlog.vue'
import Carrello from './components/Carrello.vue'
import Marchi from './components/Marchi.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    F_product,
    Jumbo_2,
    Best_seller,
    Jumbo_3,
    New_arrival,
    Jumbo_4,
    Vlog,
    Marchi,
    Carrello,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Roboto', sans-serif;
}
body{
   margin: 0;
   border: 0;
   box-sizing: border-box;
 }
  

@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

 
</style>

