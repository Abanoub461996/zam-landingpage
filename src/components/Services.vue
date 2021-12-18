<template>
  <div class="services">
    <div class="services_content">
      <h2>كل ما تحتاجه لنمو متجرك فى مكان واحد</h2>
      <p>مميزات سوق تطبيقات زد تساعدك فى سهولة و سرعة الإستفادة من خدمات و حلول سوق التطبيقات لنمو متجرك و مضاغفة أرباحك </p>
    <div class="service_item">
      <Laptop class="service-icon"/>
      <p> سهولة إدارة و تفعيل تطبيقات من نفس لوحة تحكم متجرك </p>
    </div>
    <div class="service_item">
      <ApplicationCogOutline class="service-icon"/>
      <p>دعم فنى و تقنى متكامل متوفر على مدار الساعة</p>
    </div>
    <div class="service_item">
      <CurrencyUsd class="service-icon"/>
      <p>أسعار تنافسية مع تجربة مجانية وباقات اشتراك متنوعة</p>
    </div>
    <Button />
    </div>
    <div class="services_slider">
      <div class="slider-container">

          <Circle />
          <Square />
        </div> 
    </div>
  </div>
</template>
<script>
import Button from './shared/Button.vue';
import Circle from './shared/Circle';
import Square from './shared/Square';
import Laptop from 'vue-material-design-icons/Laptop.vue';
import CurrencyUsd from 'vue-material-design-icons/CurrencyUsd.vue';
import ApplicationCogOutline from 'vue-material-design-icons/ApplicationCogOutline.vue';



export default {
  name: 'Services',
  components: {
    Button,
    Circle,
    Square,
    Laptop,
    CurrencyUsd,
    ApplicationCogOutline
  }
}

</script>
<style>
.services{
  display:flex;
  background-color:#f7f7f7;
  position: relative;
  z-index:-10;
  padding:1rem;
}
.services_content{
  width:50%;
}
.service_item{
  display:flex;
  justify-content:flex-start;
  align-items: center;
  padding:1rem .5rem;
}
.service_item .service-icon{
  border-radius:50%;
  margin-left:1rem;
  color:#8d5da7;
  background-color:white;
  height: 48px;
  width: 48px;
  display: inline-flex;
  align-items: center;
  justify-content: space-around;
  box-shadow: #545656 0px 0px 13px 0px;
}
.services_slider{
  position:relative;
}
.services_slider .slider-container{
  height:550px;
  width:550px;
  background-color:#8d5da7;
  margin:0 auto;
  border-radius:35px;
}
</style>