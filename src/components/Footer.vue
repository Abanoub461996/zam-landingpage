<template>
  <footer>
    <div class="footer-content">
      <div class="footer-logo">
        <div>
          <p><span>zid</span>App</p>
      <p> Market</p>
        </div>
      
      <figure class="footer-img">
        <img src="../assets/footer.png" />
      </figure>
      
      </div>
      <div class="social-links">
        <Twitter />
        <Instagram />
        <Linkedin class="linkedin" />
        <Youtube />
      </div>
    </div>
  </footer>
</template>
<script>
import Youtube from "vue-material-design-icons/Youtube.vue";
import Instagram from 'vue-material-design-icons/Instagram.vue';
import Twitter from 'vue-material-design-icons/Twitter.vue';
import Linkedin from 'vue-material-design-icons/Linkedin.vue';

export default {
  components: {
    Twitter,
    Instagram,
    Youtube,
    Linkedin
  }
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Exo+2:ital,wght@0,100;1,600;1,900&family=Tajawal:wght@200;300;400;500;700;800;900&display=swap');

.footer-content{
    margin:0 auto;
    padding:2rem;
    display:flex;
    flex-direction:column;
    justify-content:center;
    width:fit-content;
  }
  .footer-content .footer-logo{
    margin:0 auto;
    display:flex;
    justify-content:center;
    width:150px;
  }
  .footer-img img{
    height:70px;
    width:70px;
  }

  .footer-logo p{
    font-family: 'Titillium Web', sans-serif;
    color:white;
    line-height:30px;
    font-weight: 400;
    }
  .footer-logo p span {
  font-weight:800;
}
.social-links{
  display:flex;
  justify-content: space-between;
  padding:1rem 0;
}
.social-links span{
  color:white;
}
</style>
