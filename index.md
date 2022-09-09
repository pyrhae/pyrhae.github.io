---
layout: default
title: Ithaka
---

<div class="introduction">
  <!-- <h1 align="center">明豫の岛</h1> -->



<br>
<div style="color:DodgerBlue;text-align:center">
你好, 我是明豫。<br>
这是我利用Github Pages建立的 个人博客,<br>
主要用于发布分享一些关于 <b>中学数学</b> 的知识,<br>
以及一些 个人的<b>生活随笔</b>、 <b>学外语</b> 的方法与反思。<br>
</div>
<br>

<div class="toc">
  <h3>精选文章</h3>
  <ul class="texts">
  {% for item in site.texts %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
<hr>







