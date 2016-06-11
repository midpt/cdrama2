---
layout:     post
title:      "FlexSlider"
subtitle:   "Image slider"
date:       2016-06-04 12:00:00
author:     "midpt"
header-img: "img/blog/header/post-bg-01.jpg"
thumbnail: /img/blog/thumbs/thumb01.png
tags: [bootstrap, slider, flexslider]
category: [cat03]
comments: false
share: false
---

## Bootstrap Carousel

<br>
<div id="myCarousel" class="carousel slide" data-ride="carousel">
	<!-- Indicators -->
	<ol class="carousel-indicators">
	  <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
	  <li data-target="#myCarousel" data-slide-to="1"></li>
	  <li data-target="#myCarousel" data-slide-to="2"></li>
	  <li data-target="#myCarousel" data-slide-to="3"></li>
	</ol>

	<!-- Wrapper for slides -->
	<div class="carousel-inner" role="listbox">
	  <div class="item active">
		<img src="img_chania.jpg" alt="Chania" width="460" height="345">
	  </div>

	  <div class="item">
		<img src="img_chania2.jpg" alt="Chania" width="460" height="345">
	  </div>

	  <div class="item">
		<img src="img_flower.jpg" alt="Flower" width="460" height="345">
	  </div>

	  <div class="item">
		<img src="img_flower2.jpg" alt="Flower" width="460" height="345">
	  </div>
	</div>

	<!-- Left and right controls -->
	<a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
	  <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
	  <span class="sr-only">Previous</span>
	</a>
	<a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
	  <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
	  <span class="sr-only">Next</span>
	</a>
</div>


   
## Flexi slider

<div class="slider">
	<div class="flexslider">
	  <ul class="slides">
			<li>
			<img src="{{site.url}}/img/slider/bg1.jpg" />
			</li>
			<li>
			<img src="{{site.url}}/img/slider/bg2.jpg" />
			</li>
			<li>
			<img src="{{site.url}}/img/slider/bg3.jpg" />
			</li>
			<li>
			<img src="{{site.url}}/img/home-bg.jpg" alt="slide 4" />
			</li>
	  </ul>
	</div>
</div>

 

 
