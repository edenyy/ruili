<template>
     <swiper :options="swiperOption" :not-next-tick="notNextTick" ref="mySwiper">
    <!-- slides -->
    <swiper-slide><img src="../../assets/img1.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../../assets/img2.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../../assets/img3.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../../assets/img4.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../../assets/img5.jpg" alt=""></swiper-slide>
    <swiper-slide><img src="../../assets/img6.jpg" alt=""></swiper-slide>

    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
    <div class="swiper-button-prev" slot="button-prev"></div>
    <div class="swiper-button-next" slot="button-next"></div>

  </swiper>
</template>
<script>
export default{
    name:'carsoule',
     data () {
        return {
        swiperOption: {
        pagination: '.swiper-pagination',
        loop: true,
        speed:1400,
        autoplay:2400,
        preventClicks:false,
        prevButton:'.swiper-button-prev',
        nextButton:'.swiper-button-next',
        autoHeight:true
      }
    }
  }
}
</script>
<style>
.swiper-pagination-bullet-active{
    background: #fff;
}
</style>

