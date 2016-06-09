---
layout:     post
title:      "Bootstrap Accordian"
subtitle:   "Bootstrap accordian collapsible"
date:       2016-06-04 12:00:00
author:     "midpt"
header-img: "img/blog/header/post-bg-01.jpg"
thumbnail: /img/blog/thumbs/thumb01.png
tags: [bootstrap, alert]
category: [cat03]
comments: false
share: false
---
<style>
.collapse {
color: #696969;
font-size: 80%;
float: none;
width: 100%;


}

</style>


   
## Bootstrap Accordian

<div class="container">
  <h2>Accordion Example</h2>
  <p><strong>Note:</strong> The <strong>data-parent</strong> attribute makes sure that all collapsible elements under the specified parent will be closed when one of the collapsible item is shown.</p>
  
 <button data-toggle="collapse" data-target="#demo5">Collapsible</button>

<div id="demo5" class="collapse" style="width: 100%; float:none; ">
A wiki is run using wiki software, otherwise known as a wiki engine. There are dozens of different wiki engines in use, both standalone and part of other software, such as bug tracking systems. Some wiki engines are open source, whereas others are proprietary. Some permit control over different functions (levels of access); for example, editing rights may permit changing, adding or removing material. Others may permit access without enforcing access control. Other rules may also be imposed to organize content. A wiki engine is a type of 
</div>  
  
  
  
  <br/>
  <hr/>
  <div class="panel-group" id="accordion">
    <div class="panel panel-default">
      <div class="panel-heading">
        <h4 class="panel-title">
          <a data-toggle="collapse" data-parent="#accordion" href="#collapse1">Collapsible Group 1</a>
        </h4>
      </div>
      <div id="collapse1" class="panel-collapse collapse">
        <div class="panel-body">Lorem ipsum dolor sit amet, consectetur adipisicing elit,
        sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
      </div>
    </div>
    <div class="panel panel-default">
      <div class="panel-heading">
        <h4 class="panel-title">
          <a data-toggle="collapse" data-parent="#accordion" href="#collapse2">Collapsible Group 2</a>
        </h4>
      </div>
      <div id="collapse2" class="panel-collapse collapse">
        <div class="panel-body">Lorem ipsum dolor sit amet, consectetur adipisicing elit,
        sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
      </div>
    </div>
    <div class="panel panel-default">
      <div class="panel-heading">
        <h4 class="panel-title">
          <a data-toggle="collapse" data-parent="#accordion" href="#collapse3">Collapsible Group 3</a>
        </h4>
      </div>
      <div id="collapse3" class="collapse">
        <div style="width: 100%; float:none; ">Lorem ipsum dolor sit amet, consectetur adipisicing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
		</div>
      </div>
    </div>
  </div> 
</div>