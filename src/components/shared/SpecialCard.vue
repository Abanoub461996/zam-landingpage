<template>
<div class="card">
    <figure class="card-img">
        <img src="../../assets/card-img.png" />
    </figure>
    <div class="card-content">
        <div class="card-header"><h4>title</h4> <p>rating</p></div>
        <p class="card-author">تطوير : <span>عمر برهوم</span></p>
        <p class="card-tail">نظام الولاء الأمثل الذى يمكنك من رفع مبيعاتك</p>
        <p class="card-tail">نظام الولاء الأمثل الذى يمكنك من رفع مبيعاتك</p>
    </div>
</div>
</template>
<style>
.card{
    display:flex;
    background-color:#f7f7f7;
    padding: 1rem .5rem;
    border-radius:10px;
}
.card-img{
    width: 55px;
    height: 45px;
    margin: 0 0 0 10px;
}
.card-header{
    display:flex;
    justify-content:space-between;
}
.card-content p{
    font-size: x-small;
}
</style>