---
title: 不停转圈的方形
excerpt_separator: "<!--more-->"
categories:
    - SVG制作
tags:
    - SVG
---
标签: SVG制作 变色 移动 倒转  Markdown
<!--more-->

* 正方形有规律的绕着轨道旋转，到起点时又倒着转回去

	 <style>
     .body {
	width:600px;
	height:600px;
}
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