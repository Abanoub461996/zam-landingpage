<template>
<section id="services">
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
          <div>
            <img src="../assets/apps-gif.gif" />
          </div>
        </div> 
        
          <figure class="pattern-area">
            <img src="../assets/Pattern.png" />
          </figure>
          <figure class="services-ellipse">
            <img src="../assets/Ellipse.png" />
          </figure>
    </div>
  </div>
  </section>
</template>
<script>
import Button from './shared/Button.vue';
import Laptop from 'vue-material-design-icons/Laptop.vue';
import CurrencyUsd from 'vue-material-design-icons/CurrencyUsd.vue';
import ApplicationCogOutline from 'vue-material-design-icons/ApplicationCogOutline.vue';



export default {
  name: 'Services',
  components: {
    Button,
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
  padding: 4rem 1rem 1.5rem 1rem;
}
.services_content{
  width:45%;
  padding-bottom: 1.5rem;
}
.service_item{
  display:flex;
  justify-content:flex-start;
  align-items: center;
  padding:.5rem;
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
  width: 700px;
}
.services_slider .slider-container{
  margin:0 auto;
}

.pattern-area{
    position:absolute;
    z-index:-1;
    left:-40px;
    top:-45px;
}
.pattern-area img{
    width:100%;;
    height:100%;
    border-radius: 0;
}
.slider-container img{
  border-radius:35px;
}
.services-ellipse{
    width:350px;
    height:350px;
    border-radius:50%;
    position:absolute;
    z-index: -1;
    top:150px;
    right: -55px;
}
</style>