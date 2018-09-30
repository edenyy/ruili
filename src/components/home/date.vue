<template>
<div class='date'>
<div class="top">
<div class="flight"><i class="iconfont icon-feiji"></i> 预定您的航班</div>
<div class='hotel'><i class="iconfont icon-jiudian"></i> 机票+酒店</div>
</div>
<div class='clear'><div class="trip"><input type="radio" name="radio" value="1">单程
<input type="radio" name="radio" value="2">往返</div></div>
<div class="location">
<div>出发地<br><input id='cf' type="text"></div>
<div>到达地 <br><input type="text" id='dd'></div>
</div>
<div class="day"><div class="left"><calendar theme='#c30d23' inputwidth='142px' ></calendar></div>
<div class="right"><calendar theme='#c30d23' inputwidth='142px' ></calendar></div></div>
<button id='btn'>搜索航班</button>
</div>
</template>
<script>
import calendar from 'auto-calendar'
export default{
name:'date',
components:{
    calendar
}
}
</script>
<style scoped>
.date{
    width:7.6rem;
    height:4.6rem;
    background: #fff;
    position:absolute;
    top:4rem;
    left:3rem;
    z-index: 20;
    border-radius: .1rem
}
.top{
    display: flex;
    margin:0.2rem;
    justify-content: space-between;
    font-size: .35rem
}
.flight{
    background: #c30d23;
    color:#fff;
    cursor: pointer;
    padding:.2rem;
    border-radius: .1rem;
    margin-left: .4rem
}
.hotel{
    padding: .2rem;
    cursor: pointer;
    color:#c30d23;
    margin-right:.4rem;
}
.clear{
    margin-bottom: .2rem
}
.clear::after{
content: '';
display: block;
clear: both;
}
.trip{

    float: left;
    margin-left: .6rem
}
.trip input{
margin-right:.2rem
}
.location{
    display: flex;
    justify-content: space-around;
    padding:.1rem .2rem;
}
#cf,#dd{
    color:black;
    border: .02rem solid #ccc;
    height:.5rem;
    width:2.8rem;

}
.day{
   padding: 0 .2rem;
    justify-content: space-around;
    display: flex
}
#btn{
    width:2rem;
    height:.6rem;
    background: #c30d23;
    color:#fff;
    cursor: pointer;
    border-radius: .1rem;
    position:relative;
    top:.4rem
}
</style>

