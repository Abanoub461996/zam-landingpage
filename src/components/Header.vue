<template>
  <div  class="container">
    <div class= "header-section">
      <div class= "header-section-title"> 
        <h1>طور متجرك و وسع افاق تجارتك مع سوق تطبيقات زد</h1>
        <h6>طور تجارتك من خلال تطبيقات و حلول سوق تطبيقات زد 
          التى تساعدك فى نمو ارباحك عبر إدارة عمليات متجرك بشكل فعال و احترافى</h6>
        <Button />
      
      </div>
      <div class= "header-section-content">
        <div class="slider-container">

          <Circle />
          <Square />
        </div>  
      </div>
    </div>
  </div>
</template>

<script>
import Button from './shared/Button.vue';
import Circle from './shared/Circle';
import Square from './shared/Square'
export default {
  name: 'Header',
  components: {
    Button,
    Circle,
    Square
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header-section-title{
 text-align:center;
}
.header-section-content{
  margin:4.5rem auto;
}
.slider-container {
  height:550px;
  width:80%;
  background-color:#8d5da7;
  margin:0 auto;
  position:relative;
  border-radius:35px;
}

</style>
