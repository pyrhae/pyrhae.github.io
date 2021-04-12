---
layout: default
title: 伊萨卡
---
<div class="introduction">
  <h1>你好。</h1>

<p>
  我是明豫。欢迎你来到我的小岛上，这里有一丢丢知识，可能是关于
  英语或者数学、哲学的，还有些关于我的故事，希望能帮到你。
</p>
<p>
  浏览愉快！祝你度过美好的一天！
</p>
</div>

<hr>

<div class="toc">
  <h2>示例文章</h2>
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
