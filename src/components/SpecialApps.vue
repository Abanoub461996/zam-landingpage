<template>
    <div class="container">
    <div class="special-header">
        <h2>التطبيقات المميزة</h2>
        <p>تطبيقات تقدم حلول و خدمات مميزة نوصى بها</p>
    </div>
    <div class="cards-container">
        <SpecialCard />
        <SpecialCard />
        <SpecialCard />
        <SpecialCard />
    </div>
    <div class="special-tail">
        <Button class="special-btn"/>
    </div>
    
    </div>
</template>

<script>
import SpecialCard from './shared/SpecialCard';
import Button from './shared/Button';

export default {
  name: 'SpecialApps',
  components: {
    SpecialCard,
    Button
  }
}
</script>

<style>
.special-header{
    text-align:center;
}
.cards-container{
    display:flex;
    justify-content: space-evenly;
    margin:2rem auto;
}
.special-btn{
    background-color:white;
}
.special-tail{
    display: flex;
}
</style>