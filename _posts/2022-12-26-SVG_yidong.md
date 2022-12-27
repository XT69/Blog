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
.fond{position:absolute;padding-top:85px;top:0;left:0; right:0;bottom:0;
 background-color:#00506b;}

.style_prevu_kit
{
    display:inline-block;
    border:0;
    width:96px;
    height:110px;
    position: relative;
    -webkit-transition: all 200ms ease-in;
    -webkit-transform: scale(1); 
    -ms-transition: all 200ms ease-in;
    -ms-transform: scale(1); 
    -moz-transition: all 200ms ease-in;
    -moz-transform: scale(1);
    transition: all 200ms ease-in;
    transform: scale(1);   

}
.style_prevu_kit:hover
{
    box-shadow: 0px 0px 150px #000000;
    z-index: 2;
    -webkit-transition: all 200ms ease-in;
    -webkit-transform: scale(0.6);
    -ms-transition: all 200ms ease-in;
    -ms-transform: scale(0.6);   
    -moz-transition: all 200ms ease-in;
    -moz-transform: scale(0.6);
    transition: all 200ms ease-in;
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