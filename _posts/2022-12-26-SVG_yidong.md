---
title: 永不停歇地旋转
excerpt_separator: "<!--more-->"
categories:
    - SVG制作
tags:
    - SVG
---
标签: SVG制作 变色 旋转  Markdown
<!--more-->

* 渐变的线条绕着图形边框一直旋转


	 <style>
		html {
  height: 100%;
  background: #223;
  display: grid;
  place-items: center;
}

.box {
  --border-size: 3px;
  --border-angle: 0turn;
  width: 60vmin;
  height: 50vmin;
  background-image: conic-gradient(
      from var(--border-angle),
      #213,
      #112 50%,
      #213
    ),
    conic-gradient(from var(--border-angle), transparent 20%, #08f, #f03);
  background-size: calc(100% - (var(--border-size) * 2))
      calc(100% - (var(--border-size) * 2)),
    cover;
  background-position: center center;
  background-repeat: no-repeat;

  animation: bg-spin 3s linear infinite;
  @keyframes bg-spin {
    to {
      --border-angle: 1turn;
    }
  }

  &:hover {
    animation-play-state: paused;
  }
}

@property --border-angle {
  syntax: "<angle>";
  inherits: true;
  initial-value: 0turn;
}
		</style>

  <div class="box"></div>