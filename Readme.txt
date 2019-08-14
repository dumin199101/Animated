2D&3D转换：transform
过渡：transition
自定义应用动画：animate
自定义动画：@keyframes

opacity 由 0 变 1
width 由 0 变 100
top 由 -75 变 75

zoomIn
slideIndown
slideInLeft
slideInRight
fadeInUp
fadeInLeft
bounceInDown
bounceInUp



transform:rotateY(360deg)
transform: scale(1.1)

显示信息切换：
.box9 .btm .con{position: absolute;height: 380px;top: 380px;left: 0;background: #0040AB;width: 100%;border-radius: 20px;transition: all .4s;-moz-transition: all .4s; -webkit-transition: all .4s;-o-transition: all .4s;}
.box9 .btm ul li:hover .con{top:0px;}

向上运动：
margin-top:10px;
hover:margin-top:0px;


沿顺时针旋转
@keyframes move
{ 0%{transform:rotate(0);} 50%{transform:rotate(180deg) ;} 100%{transform:rotate(360deg);}}
@-moz-keyframes move
{ 0%{transform:rotate(0);} 50%{transform:rotate(180deg) ;} 100%{transform:rotate(360deg);}}
@-webkit-keyframes move
{ 0%{transform:rotate(0);} 50%{transform:rotate(180deg) ;} 100%{transform:rotate(360deg);}}
@-o-keyframes move
{ 0%{transform:rotate(0);} 50%{transform:rotate(180deg) ;} 100%{transform:rotate(360deg);}}

@keyframes mytop {
  0% {top:80px;left: 20px;}
  50% {top:70px;left: 25px;}
  100% {top:80px;left: 20px;}
  }  

@keyframes bing1
{ 0%{opacity: .5;}   50%{opacity: 1;}  100%{opacity: .5;}}
@-moz-keyframes bing1
{ 0%{opacity: .5;}   50%{opacity: 1;}  100%{opacity: .5;}}
@-webkit-keyframes bing1
{ 0%{opacity: .5;}   50%{opacity: 1;}  100%{opacity: .5;}}
@-o-keyframes bing1
{ 0%{opacity: .5;}   50%{opacity: 1;}  100%{opacity: .5;}}

<script type="text/javascript">
    // borwserRedirect
    (function browserRedirect(){
      var sUserAgent = navigator.userAgent.toLowerCase();
      var bIsIpad = sUserAgent.match(/ipad/i) == 'ipad';
      var bIsIphone = sUserAgent.match(/iphone os/i) == 'iphone os';
      var bIsMidp = sUserAgent.match(/midp/i) == 'midp';
      var bIsUc7 = sUserAgent.match(/rv:1.2.3.4/i) == 'rv:1.2.3.4';
      var bIsUc = sUserAgent.match(/ucweb/i) == 'web';
      var bIsCE = sUserAgent.match(/windows ce/i) == 'windows ce';
      var bIsWM = sUserAgent.match(/windows mobile/i) == 'windows mobile';
	  var bIsAndroid = sUserAgent.match(/android/i) == 'android';

      if(bIsIpad || bIsIphone || bIsMidp || bIsUc7 || bIsUc || bIsCE || bIsWM || bIsAndroid ){
        window.location.href = 'http://m.goosuudata.com/';
      }
    })();
 </script>
