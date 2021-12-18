<template>

  <div class ="container">
    <div class="navbar">
      <figure class="logo-img">
        <img src="../assets/zid-logo.png" />
      </figure>
      <ul class="nav-links">
        <li class="nav-link">الرئيسية</li>
        <li class="nav-link">التصنيفات</li>
        <li class="nav-link">التطبيقات</li>
        <li class="nav-link">طور تطبيق</li>
      </ul>
    </div>
    
  </div>
</template>
<script>

</script>
<style>
.navbar{
  display:flex;
  justify-content:space-between;
  align-items: center;
  margin:0.3rem 0;
}
.nav-links{
  width:50%;
  display:flex;
  justify-content:space-between;
  cursor: pointer;
}
.nav-logo{
  display:flex;
  width: 12%;
  justify-content:center;
  cursor: pointer;
}
.nav-logo figure{
  height:40px;
  width:40px;
}
.nav-logo p{
    color:#8d5da7;
    margin: 0;
    padding: 0;
    line-height:22px;
    font-weight: 300;
    font-size: normal;
}
.nav-logo p span {
  font-weight:800;
}
</style>