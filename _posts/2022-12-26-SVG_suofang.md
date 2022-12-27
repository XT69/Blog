---
title: 能够缩放的方形
excerpt_separator: "<!--more-->"
categories:
    - SVG制作
tags:
    - SVG
---
标签: SVG制作 缩放  Markdown
<!--more-->

* 鼠标放到图形上后，图形缩小


<style>


.style_prevu_kit
{
    display:inline-block;
    border:0;
    width:96px;
    height:110px;
    position: relative;
    -webkit-transition:  200ms ease-in-out;
    -webkit-transform: scale(1); 
	-webkit-transition-duration:1s;
    -ms-transition:  200ms ease-in-out;
	-webkit-transition-duration:1s;
    -ms-transform: scale(1); 
    -moz-transition:  200ms ease-in-out;
	-webkit-transition-duration:1s;
    -moz-transform: scale(1);
    transition:  200ms ease-in-out;
    transform: scale(1); 
	-webkit-transition-duration:1s;

}
.style_prevu_kit:hover
{
    box-shadow: 0px 0px 150px #000000;
    z-index: 2;
    -webkit-transition:  200ms ease-in-out;
    -webkit-transform: scale(0.6);
	-webkit-transition-duration:1s;
    -ms-transition:  200ms ease-in-out;
    -ms-transform: scale(0.6);   
    -moz-transition:  200ms ease-in-out; 
    -moz-transform: scale(0.6);
    transition:  200ms ease-in-out;
    transform: scale(0.6);
}
</style>

<link href='https://fonts.googleapis.com/css?family=Roboto:100,400,300,500,700' rel='stylesheet' type='text/css'>


<div style="width:500px;">

<div class="style_prevu_kit" style="background-color:#ffdbfe;"></div>
<div class="style_prevu_kit" style="background-color:#f3ff6f;"></div>
<div class="style_prevu_kit" style="background-color:#c8fa10;"></div>
<div class="style_prevu_kit" style="background-color:#00fcec;"></div>
<div class="style_prevu_kit" style="background-color:#a001fc;"></div>


<div style=" padding:5px; color:#b5e6e3; font-weight:300; font-size:30px; font-family:'Roboto';padding-top:20px;">CSS <font style="font-weight:400;">HOVER</font></div>
        <a href="http://www.wifeo.com/code" style="text-decoration:none;" target="_blank"><div style="  color:#b5e6e3; font-weight:300; font-size:20px; font-family:'Roboto';">www.wifeo.com/code</div></a>
  
</div>

<!-- partial -->
  <script  src="./script.js"></script>
