<template>
<div class="home">
<Header></Header>
<panel></panel>
<swiper></swiper>
<date></date>
<inform></inform>
<discount></discount>
<bottom></bottom>
</div>
</template>
<script>
import Header from './home/header'
import panel from './home/panel'
import swiper from './home/swiper'
import date from './home/date'
import inform from './home/inform'
import discount from './home/discount'
import bottom from './home/bottom'
export default{
name:'home',
components:{
    Header,
    panel,
    swiper,
    date,
    inform,
    discount,
    bottom
}
}

</script>
<style>

</style>

