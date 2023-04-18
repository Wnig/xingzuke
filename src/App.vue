<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

import './font/style.css';

export default {
  name: 'App',
}
</script>

<style>
  /* CSS reset */
  html{color:#000;background:#fff;-webkit-tap-highlight-color:rgba(0,0,0,0);font-family: 'PingFangSC-Thin',"Microsoft YaHei","微软雅黑","sans-serif";font-size: 12px;}
  body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,form,input,button,textarea,p,th,td,strong{padding:0;margin:0;font-family: 'PingFangSC-Thin',"Microsoft YaHei","微软雅黑","sans-serif";}
  table{border-collapse:collapse;border-spacing:0;}
  img{border:0;}
  a{text-decoration:none; color:#999; outline:none;}/*此处待添加默认链接颜色*/
  var,em,strong{font-style:normal;}
  em,strong,th,var{font-style:inherit;font-weight:inherit;}
  li{list-style:none;}
  caption,th{text-align:left;}
  h1,h2,h3,h4{font-size:100%;font-weight:normal;}
  input,button,textarea,select,option{font-family:inherit; font-size:inherit;font-style:inherit;font-weight:inherit;}
  input,button,textarea,select{*font-size:100%;}
  .clearfix:after {content:"\200B"; display:block; height:0; clear:both; }
  .clearfix { *zoom:1; }

  .pc {
    width: 100%;
    overflow: hidden;
  }
  .selection {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }

  .mob {
    display: none;
  }

  /*向下效果*/
  @-webkit-keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }
  @keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }

  @media screen and (max-width: 750px) {
    .mob {
      display: block;
    }
    .pc {
      display: none;
    }

    .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet {
      width: 2.13vw;
      height: 2.13vw;
      margin: 0 2.8vw;
      background: #000;
      opacity: 0.2;
    }
    .selection-7 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet, .selection-8 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet, .selection-11 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet, .selection-17 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet {
      background: #fff;
      opacity: 0.2;
    }
    .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active {
      opacity: 1;
      background: #5EB4D9;
    }
    .selection-7 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active, .selection-8 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active, .selection-11 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active, .selection-17 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active {
      opacity: 1;
      background: #FF9A20;
    }
    .selection-2 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet {
      background: #000;
      opacity: 1;
    }
    .selection-2 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active {
      opacity: 1;
      background: #FF9A20;
    }
  }

  @media screen and (max-width: 751px) {

  }

</style>
