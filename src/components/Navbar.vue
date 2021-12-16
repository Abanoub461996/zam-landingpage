<template>

  <div class ="container">
    <div class="navbar">
    <div class="nav-logo">
      <p><span>zid</span>App Market</p>
      <figure class="logo-img">
        <img src="../assets/logo.png" />
      </figure>
      
    </div>
    <ul class="nav-links">
      <li class="nav-link">الرئيسية</li>
      <li class="nav-link">التصنيفات</li>
      <li class="nav-link">التطبيقات</li>
      <li class="nav-link">طور تطبيق</li>
    </ul>
    </div>
    
  </div>
</template>
<style>
.navbar{
  display:flex;
  justify-content:space-between;
  align-items: center;
}
.nav-links{
  width:50%;
  display:flex;
  justify-content:space-between;
}
.nav-logo{
  display:flex;
  width: 12%;
  justify-content:center;
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