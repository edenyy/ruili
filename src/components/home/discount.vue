<template>
<div>
<div class="gap"></div>
<div class="discount"><div class="content">
<div class="head"><div class="title">优惠产品</div></div>
<div class="product">
    <div><img src="https://www.rlair.net/BasicInfo/ResourceFile/GetResourceFileById?id=118" alt=""></div>
    <div><img src="https://www.rlair.net/BasicInfo/ResourceFile/GetResourceFileById?id=141" alt=""></div>
    <div><img src="https://www.rlair.net/BasicInfo/ResourceFile/GetResourceFileById?id=16" alt=""></div>
    <div><img src="https://www.rlair.net/BasicInfo/ResourceFile/GetResourceFileById?id=204" alt=""></div>
</div>
<div class="head"><div class="title">特价机票</div></div>
<div class="layout">
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
<div class="tickets">
    <div class="item"><div class="place">太原——呼和浩特</div>
    <div class="date">2018—10—26</div>
    <div class="price">￥190</div>
    </div>
</div>
</div>
</div>
</div>

</div>
</template>
<script>
  export default{
      name:'discount',

  }
</script>
<style scoped>
.gap{
    width:100%;
    height:.1rem;
    background: #fff;
}
.layout{
    overflow: hidden;
    margin:0 99px
}
.discount{
    width:100%;
    background: rgb(40,40,40);
    height:9.6rem;
    display: flex;
    justify-content: center
}
.content{
    background: #fff;
    width:80%;
}
.head{
    background: #c30d23;
    height:1.2rem
}
.title{
color:#fff;
float:left;
font-size: .5rem;
font-weight:bold;
line-height: 1.2rem;
margin-left: .3rem
}
.product{
    display: flex;
    justify-content: space-between
}
.product img{
    height:3.2rem;
    width:5.8rem
}
.item{
    width:5rem;
    height:2rem;
    position: relative;
    border:0.02rem solid rgb(40,40,40);
    border-top: none
}
.place{
    font-size:.36rem;
    font-weight: .3rem;
    width:3rem;
    margin:.2rem;
    float: left;
}
.tickets{
    position: relative;
    float:left
}
.price{
    width:1.5rem;
    position: absolute;
    bottom:.2rem;
    right:.4rem;
    font-size: .5rem;
    color:#c30d23;
}
.date{
    font-size:.32rem;
    width:2.6rem;
    float: left;
}
</style>

