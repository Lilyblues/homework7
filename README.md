
<html>
<head>
<meta charset="utf-8">
<title>网传官网</title>
<link rel="stylesheet" type="text/css" href="assets/style.css" />
<link rel="stylesheet" type="text/css" href="assets/swiper-3.4.0.min.css" />
</head>

<body>
	<div class="content">
		<div class="header">
    		<img src="logo.png">
			<div class="quickLink">
				<a href="#">教师进入</a>
				<a href="#">学生进入</a>
				<a href="#">考生进入</a>  
			</div>
		</div>
	</div>
	<div class="nav">
		<ul>
            <a href="#"><li>首页</li></a>
            <a href="#"><li>首页</li></a>
            <a href="#"><li>首页</li></a>
            <a href="#"><li>首页</li></a>
            <a href="#"><li>首页</li></a>
            <a href="#"><li>首页</li></a>
            <a href="#"><li>首页</li></a>
		</ul>
	</div>
	<div class="swiper-container">
    	<div class="swiper-wrapper">
            <div class="banner1 swiper-slide"></div>
            <div class="banner2 swiper-slide"></div>
            <div class="swiper-slide">Slide 3</div> 
        </div>
        
        
         <!-- 如果需要导航按钮 -->
    	  <div class="swiper-button-prev"></div>
   	  <div class="swiper-button-next"></div>
    </div>  
    <!--!id是唯一的，class是可以复用的!-->
    <div class="container">
        <div class="row" id="row1">
            <div class="cols" id="cols1-1"></div>
            <div class="cols" id="cols1-2">
                <ul>
                    <li><span class="channel">[栏目]</span>&nbsp;&nbsp;&nbsp;<a href="#">标题标题标题标题标题</a><span class="datetime">[2017/3/31]</span></li>
                    <li><span class="channel">[栏目]</span>&nbsp;&nbsp;&nbsp;<a href="#">标题标题标题标题标题</a><span class="datetime">[2017/3/31]</span></li>
                    <li><span class="channel">[栏目]</span>&nbsp;&nbsp;&nbsp;<a href="#">标题标题标题标题标题</a><span class="datetime">[2017/3/31]</span></li>
                    <li><span class="channel">[栏目]</span>&nbsp;&nbsp;&nbsp;<a href="#">标题标题标题标题标题</a><span class="datetime">[2017/3/31]</span></li>
                    <li><span class="channel">[栏目]</span>&nbsp;&nbsp;&nbsp;<a href="#">标题标题标题标题标题</a><span class="datetime">[2017/3/31]</span></li>
                    <li><span class="channel">[栏目]</span>&nbsp;&nbsp;&nbsp;<a href="#">标题标题标题标题标题</a><span class="datetime">[2017/3/31]</span></li>
                    <li><span class="channel">[栏目]</span>&nbsp;&nbsp;&nbsp;<a href="#">标题标题标题标题标题</a><span class="datetime">[2017/3/31]</span></li>
                </ul>
             </div>
            <div class="cols" id="cols1-3">
                <span class="titleColor">学院概况</span>
                <p>网络传播学院</p>
            </div>
        </div>
        <div class="row" id="row2"></div>
        <div class="row" id="row3"></div>
    </div>  
</body> 
<script src="assets/jquery-3.1.1.min.js"></script>
<script src="assets/swiper.jquery.min.js"></script>   
<script>        
	 var mySlide = new Swiper ('.swiper-container', {
		loop: true,
		// 如果需要前进后退按钮
		nextButton: '.swiper-button-next',
		prevButton: '.swiper-button-prev',  
	  })     
	  var width=$(document).width();
	  var height=width * 300 / 2000;
	  $('.swiper-container').css('height',height + 'px');
</script>
</html>

