<template>
    <div class="inform">
        <div class="title">重要通告：</div>
        <div class="swiper">
                <swiper :options="swiperOption" :not-next-tick="notNextTick" ref="mySwiper"><!-- slides -->
    <swiper-slide>关于瑞丽航空有限公司秋季飞行学员的招聘声明</swiper-slide>
    <swiper-slide>第二期“空中美食节”开始筹备的通知</swiper-slide>
    <swiper-slide>关于 昆明-曼谷 落地签政策调整通知</swiper-slide>
    <swiper-slide>瑞丽航空有限公司关于邀请货运销售代理人合作的通告</swiper-slide>
    <swiper-slide>瑞丽航空有限公司关于邀请货运销售代理人合作的通告</swiper-slide>
    <swiper-slide>瑞丽航空有限公司关于邀请货运销售代理人合作的通告</swiper-slide>

    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>

                </swiper>
        </div>
    </div>
</template>
<script>
export default{
name:'inform',
     data () {
        return {
        swiperOption: {
        loop: true,
        speed:1400,
        direction:'vertical',
        autoplay:2400,
        grabCursor:true,
        preventClicks:false,
        height:100
      }
    }
  }
}
</script>
<style scoped>
.inform{
    background: rgb(40,40,40);
    height:1.2rem
}
.inform::after{
    content: '';
    display: block;
    clear: both;
}
.title{
    color: #fff;
    font-size: .4rem;
    float: left;
    text-align: center;
    width:2.4rem;
    line-height: 1.2rem;
    margin-left:3rem;
}
.swiper{
    width:7.5rem;
    position: relative;
    top:.45rem;
    height:.5rem;
    font-size: .3rem;
    line-height: .3rem;
    overflow: hidden;
    padding-right: -1rem;
    float: left;
    text-decoration: underline;
    color:#fff;
}
</style>

