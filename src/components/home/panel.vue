<template>
<div>
<div class='panel'>
  <div class="item img"><img src="https://www.rlair.net/image/logo.png" alt=""></div>
  <div class="item" >首页</div>
  <div class="item" @mouseover="show" @mouseout="disshow">行程预定</div>
  <div class="item">优惠产品</div>
  <div class="item">自助服务</div>
  <div class="item">信息服务</div>
  <div class="item">瑞丽客会员</div>
  <div class="item">我的瑞丽航</div>
</div>
<div class="content" v-show='reserve' ><div class='choice'>机票预定</div>
<div class='choice'>机+酒预定</div>
</div>
</div>
</template>
<script>

 export default{
     name:'panel',
     data (){
         return {
             reserve:false
         }
     },
     methods:{
         show:function(){
             this.reserve=true
         },
         disshow:function(){
             this.reserve=false
         }
     }

 }
</script>
<style scoped>
.panel{
    width:100%;
    height:1.4rem;
    background: #c30d23;
    display: flex;
    justify-content: center;
    align-items: center
}
.item{

    color:#fff;
    font-size: 0.4rem;
    margin-right:0.8rem
}
.img{
 margin-right: 1.2rem;
 position:relative;
 top:-16px;
}
.content{
    width:100%;
    background: #FFF;
    display: flex;
    position:absolute;
    z-index: 120;
    top:128px;

    justify-content: center;
    border-bottom:0.04rem solid #c30d23;
}
.choice{
    font-size: .3rem;
    margin:.2rem
}
</style>

