<template>
<button>
    <div class="btn-main">
    <div> تصفح التطبيقات</div>
    
    <div class="btn-arrow">
    <svg style="width:24px;height:24px" viewBox="0 0 24 24">
    <path fill="currentColor" d="M20,11H8L13.5,18.5L12.08,19.92L4.16,12L12.08,4.08L13.5,5.5L8,11H20Z" />
    </svg>
    </div>
    </div>
</button>

</template>
<style>
button{
    color:#fdb515;
    font-size:1.3em;
    padding: 0.5rem 5rem;
    border-radius:10px;
    background-color:#8d5da7;
    font-family: inherit;
    font-size: larger;
    margin:1rem auto;
    cursor: pointer;
}
.btn-main{
    display: flex;
}
.btn-arrow{
    height: 24px;
    margin-top: 6px;
    margin-right: 10px;
    -webkit-animation-name: zoomer;
    -webkit-animation-iteration-count: infinite;
    animation-timing-function: cubic-bezier(.5,.2,.3,1);
    animation-duration: 2s;
}
button:hover .btn-arrow{
    -webkit-animation-name: barrelRoll;
    -webkit-animation-duration: .4s;
    -webkit-animation-timing-function: ease;
    -webkit-animation-iteration-count: 1;
}
</style>