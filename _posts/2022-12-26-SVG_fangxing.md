---
title: SVG制作之方形的变换
excerpt_separator: "<!--more-->"
categories:
    - SVG制作
tags:
    - SVG
---
标签: SVG制作 移动 旋转 缩放  Markdown
<!--more-->

#### 不停转圈的方形

*动画效果：变色 移动 倒转*

<head>
		<meta charset="utf-8">
		<style>
			div{
				width: 100px;
				height: 100px;
				background: lightcyan;
				position: relative;
				animation: myfirst 5s infinite;
				animation-direction:alternate;
			}
			@keyframes myfirst{
				0%{background: lavenderblush;left: 0px;top:0px;}
				25%{background: lightgoldenrodyellow;left: 200px;top:0px;}
				50%{background:lightpink;left: 200px;top:200px;}
				75%{background: lightgreen;left: 0px;top:200px;}
				100%{background: lightsalmon;left: 0px;top:0px;}
			}
		</style>
	</head>
	<body>
		<div></div>
	</body>

#### scale+transition-delay的混合效果

*动画效果：变大 缩放 变色*

<head>
		<meta charset="utf-8">
		<style>
		div{
			width:200px;
			height:200px;
			background:#beffd3;
			
			margin:0 auto;
			transition-property:width,background,box-shadow;
			transition-timing-function:ease,linear,cubic-bezier(.44,.4,.9,.01);
			transition-duration:2s,3s,4s;
		}
		div:hover
		{
			width:400px;
			background:lightblue;
			box-shadow:inset 0 -5px 0 #c2f9ff;
		}
		</style>
	</head>
	<body>
		<div></div>
	</body>

#### transition+transform

*动画效果：变大 旋转 变色*

	<head>
		<meta charset="utf-8">
		<style>
		div{
			width:200px;
			height:200px;
			background-color:#ffd8fe;
			
			margin:0 auto;
			transition:width 2s,height 2s,background-color 2s,transform 2s;
		}
		div:hover
		{
			width:400px;
			height: 400px;
			background-color:#bcfcff;
			transform: rotate(180deg);
		}
		</style>
	</head>
	<body>
		<div></div>
	</body>



