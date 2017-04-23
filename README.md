<!DOCTYPE html>
<html lang="zh-hans">
<head>
	<title>csswork6</title>
   <meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href=" csswork6.css">
  <style>
  *{
	margin: 0;
	padding: 0;
}
body{
	background: rgb(93,93,93);
}
.whole{
	display: block;
	margin-top: 60px;
	margin: 60px  auto;
	height: 1386px;
	width: 980px;
	background: white;
}
.pureColor_topLeft{
  width: 110px;
  height: 61px;
  background: rgb(213,93,92);
  margin-left: 44px;
}
.pureColor_topLeft .heiti{
	font-size: 12px;
	font-family:'黑体'；
	font-color:green;
}
.line{
	margin:0 auto;
	width: 892px;
	height: 2px;
	background: #938e8c;
}
.pictureOne{
	display: inline-block;
	width: 600px;
	height: 301px;
	margin-top: 20px;
	margin-left: 44px;
	background-image: url(file:///C:/Users/lqagx/Desktop/QQ%E5%9B%BE%E7%89%8720170423143217.png)
}
.pictureOne .left{
	display: inline-block;
	width: 191px;
	height: 299px;
	background: rgb(160,197,172);
	opacity: 0.8;
	left: 0;
	z-index: 99999;
}
.pictureOne .right{
	display: inline-block;
	width: 191px;
	height: 301px;
	z-index: 99999;
	background: rgb(229,186,191);
	float: right;
	opacity: 0.6;
	position: relative;
	right: 0;
}

.part1 .first{
  font-size: 24px;
   color: #000000;
   font-family: Microsoft Yahei;
  line-height: 40px;
  text-transform: capitalize; 
   font-variant: small-caps;  /*解决首字符和之后字符高度不一 下划线对不齐的问题*/
  
} 
 .first p:first-letter{
	font-size: 30px;
}
.zhushi{
	display: inline-block;
	margin-top: 10%;
}
.zhushi a
{
	font: 12px;
	color:  #cd4a48;
	line-height: 16px;
	opacity: 0.7;

}
.text_topbottom{
   font-size: 12px;
   color: #676767;
   font-family: Microsoft Yahei;
   margin-top: 10px;
}
.leftbottom p{
	font-size: 12px;
	color:#767777;
	line-height: 16px;
}
.line_topright{
	display: block;
	width: 203px;
	height: 2px;
	background: #cc8091;
	margin-top: 23px;
	z-index: 999;
}
  </style>
</head>
<body>
   <div class="whole">
   	  <header>
   	  	  <div class="pureColor_topLeft"><label><a class="heiti">ife.baidu.com</a></label>
   	  	   <aside>2016.03</aside>
   	  	   </div>
   	  	  <div class="line"></div>
   	  </header>
   	  <!--文章第一部分-->
   	  <section class="one" > 
   	  
   	  <div>
   	  	  <a class="pictureOne"></a>
   	  	  	   <a class="left"></a>
   	  	  	   <a class="right"></a>
   	  	
   	  	  <div style="float: right;">
           <div class="line_topright"></div>
           <div style="text-decoration: underline;" class="part1">
   	  	  <p class="first">About</p>   
   	  	  <p class="first">Technologe</p>
   	  	  <section class="text_topbottom">About technologe about technology about technology</section>
           </div>
           <div>
           <p style="font-size: 116px;color: #75b86b;font-family: Microsoft Yahei;font-weight: bold;"><i>700</i>
   	  	  </p>
           <p style="font-size: 55px;color: #cc8091;font-family: Microsoft Yahei;">3.2
           <a  style="font-size: 21px;color: #cc8091;font-family: Microsoft Yahei;">css</a>
           <a style="font-size: 12px;color: #ccc;font-family: Microsoft Yahei;">csscsscsscsscsscss</a>
           </p>
   	  	  </div>
           </div>
           </div>
   	     </section>
   	  <!--文章第二部分-->
   	  <section class="part2" style="margin-left:44px ">
            <section style="width: 200px;height: 200px;display: inline-block;float:left;margin-right: 10px" >
   	  	    <p style="font:16px;color:#418c59;font-family: Microsoft Yahei;text-decoration: underline;">What</p>
           <p style="font-family:宋体;line-height: 16px; font-size: 12px;color:#231815;opacity: 0.7">端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
            </section>
              
               <section style="width: 200px;height: 200px;display: inline-block;margin-right: 10px ">
           <p style="font:16px;color:#d2994f;font-family: Microsoft Yahei;text-decoration: underline;">When</p>
           <p style="font-family: 宋体;line-height: 16px; font-size: 12px;color:#231815;opacity: 0.7">端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
            </section>

             <section style="width: 200px;height: 50px;display: inline-block;float: right;">
             <p style="font:16px;color:#cc7680;font-family: Microsoft Yahei;text-decoration: underline;">How</p>
           <p style="font-size: 12px;font-family:宋体;line-height: 16px;color:#231815;opacity: 0.7">端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
            <section class="zhushi">
            <p>what--------<a><i>40%</i></a></p>
            <p>when--------<a><i>30%</i></a></p>
            <p>where-------<a><i>20%</i></a></p>
               </section>
   	      </section>
         </section>
        <!--文章第三部分-->
        <section>

            <div style="margin-left: 44px;"><p style="font-size: 72px; color: #f5e327;font-family: 黑体;font-weight: bold;"><i>THE</i></span><span style="font-size: 42px; line-height:16px;color: #11456b;font-family:黑体"> TECHNOLOGE</span></p>
               <p style="font-size: 42px; display:inline-block;line-height:16px;color: #11456b;font-family:黑体"> OF FRONT</p>
            <p style="font-size: 33px;color: #11456b;font-family: 黑体;font-weight: bold;">前端技术领域</p>
            <div style="width: 415px;height: 2px;background:black; "></div>
            <div style="width: 415px;height: 400px;" class="leftbottom">
             <p><span style="font-size: 70px;color: #f5e347;font-family: Microsoft Yahei;display:inline-block;position:relative;margin-top:0.6em;">前</span><span style='display:inline-block;width: 28em;margin-top: 3em;'>端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端</p>
             <p style="text-indent: 2em">前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端</p>
             <p style="text-indent: 2em;">前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端</p>
             <img src="file:///C:/Users/lqagx/Desktop/QQ%E5%9B%BE%E7%89%8720170423164943.png" style="float: right;margin-bottom: 100px;z-index: 999" alt="编程图片">
            </div>
            </div>
        </section>
   	  <footer>
   	  	   
   	  </footer>
      </div>
</body>
</html>
