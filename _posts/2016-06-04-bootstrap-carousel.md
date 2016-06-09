---
layout:     post
title:      "Bootstrap Carousel"
subtitle:   "Image slider"
date:       2016-06-04 12:00:00
author:     "midpt"
header-img: "img/blog/header/post-bg-01.jpg"
thumbnail: /img/blog/thumbs/thumb01.png
tags: [bootstrap, slider, carousel]
category: [cat03]
comments: false
share: false
---



   
## Bootstrap Carousel

<div class="container">
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
        <img src="http://www.w3schools.com/bootstrap/img_chania.jpg" alt="slide 1" />
        <div class="carousel-caption">
          <h3>Chania</h3>
          <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
        </div>
      </div>

      <div class="item">
        <img src="http://www.w3schools.com/bootstrap/img_chania2.jpg" alt="slide 2" />
        <div class="carousel-caption">
          <h3>Chania</h3>
          <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
        </div>
      </div>
    
      <div class="item">
        <img src="http://www.w3schools.com/bootstrap/img_flower.jpg" alt="slide 3" />
        <div class="carousel-caption">
          <h3>Flowers</h3>
          <p>Beatiful flowers in Kolymbari, Crete.</p>
        </div>
      </div>

      <div class="item">
        <img src="http://www.w3schools.com/bootstrap/img_flower2.jpg" alt="slide 4" />
        <div class="carousel-caption">
          <h3>Flowers</h3>
          <p>Beatiful flowers in Kolymbari, Crete.</p>
        </div>
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
</div>

<hr/>
<br/>
<br/>


## Image Slider

<!-- slider -->

	<div class="flexslider" style="display:none;">
  <ul class="slides">
    <li>
      <img src="../img/slider/bg1.jpg" />
<p class="flex-caption">Source: <a href="https://unsplash.com/">Unsplash</a></p>
    </li>
    <li>
      <img src="../img/slider/bg2.jpg" />
<p class="flex-caption">Source: <a href="https://unsplash.com/">Unsplash</a></p>
    </li>
    <li>
      <img src="../img/slider/bg3.jpg" />
<p class="flex-caption">Source: <a href="https://unsplash.com/">Unsplash</a></p>
    </li>
      </ul>
</div>