<template>
<div class="card">
    <figure class="card-img">
        <img src="../../assets/app.png" />
    </figure>
    <div class="card-content">
        <div class="card-header"><h4>قمرة</h4> <div class="rating"><Star class="star" fillColor="yellow" size="16px"/> <span>5</span></div></div>
        <p class="card-author">تطوير : <span>عمر برهوم</span></p>
        <p class="card-tail">نظام الولاء الأمثل الذى يمكنك من رفع مبيعاتك</p>
        <p class="card-tail">نظام الولاء الأمثل الذى يمكنك من رفع مبيعاتك</p>
    </div>
</div>
</template>
<script>
    import Star from 'vue-material-design-icons/Star.vue';
    export default {
        components:{
            Star
        }
    }
</script>
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
.rating{
    display: flex;
    align-items: flex-start;
}
.rating .star{
    margin-top:3px;
    margin-left:5px;
}
.rating span{
    font-size:small;
}
.card-tail{
    padding:.1rem;
}
.card-author{
    padding-bottom:.5rem;
}
</style>