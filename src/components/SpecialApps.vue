<template>
    <div class="special-header">
        <h2>التطبيقات المميزة</h2>
        <p>تطبيقات تقدم حلول و خدمات مميزة نوصى بها</p>
    </div>
    <div class="container cards-container">
        <SpecialCard />
        <SpecialCard />
        <SpecialCard />
        <SpecialCard />
    </div>
</template>

<script>
import SpecialCard from './shared/SpecialCard';

export default {
  name: 'SpecialApps',
  components: {
    SpecialCard
  }
}
</script>

<style>
    .card-container{
        display:flex;
    }
</style>