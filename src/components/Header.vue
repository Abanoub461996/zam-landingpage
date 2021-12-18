<template>
<section id= "header">
  <div  class="container">
    <div class= "header-section">
      <div class= "header-section-title"> 
        <h1>طور متجرك و وسع افاق تجارتك مع سوق تطبيقات زد</h1>
        <h6>طور تجارتك من خلال تطبيقات و حلول سوق تطبيقات زد 
          التى تساعدك فى نمو ارباحك عبر إدارة عمليات متجرك بشكل فعال و احترافى</h6>
        <Button />
      
      </div>
      <div class= "header-section-content">
        <div class="banner-container">
          <figure>
            <img class="banner-gif" src="../assets/banner.gif"/>
          </figure>
          <figure class="header-ellipse">
            <img src="../assets/Ellipse.png" />
          </figure>
          <figure class="doted-area">
            <img src="../assets/Pattern.png" />
          </figure>
        </div>  
      </div>
    </div>
  </div>
  </section>
</template>

<script>
import Button from './shared/Button.vue';
export default {
  name: 'Header',
  components: {
    Button,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
section{
  margin-top: 4rem;
}
.header-section-title{
 text-align:center;
}
.header-section-content{
  margin:4.5rem auto;
  margin-bottom:10rem;
}
.banner-container {
  height:550px;
  width:850px;
  margin:0 auto;
  position:relative;
  border-radius:35px;
}
.banner-container .banner-gif{
  height:550px;
  width:850px;
  border-radius:35px;
}
.header-ellipse{
    width:400px;
    height:400px;
    border-radius:50%;
    background-color:#fed14a;
    position:absolute;
    z-index: -1;
    bottom: -95px;
    right: -80px;
}
.doted-area{
    position:absolute;
    z-index:-1;
    left:-75px;
    top:-40px;
}
.doted-area img{
    width:100%;;
    height:100%;
    border-radius: 0;
}
</style>
