---
layout: page
title: About
permalink: /about/
weight: 3
---

<h2 style="text-align: center;">
<!--## **About Me** -->
About Me
</h2>

您好，我是 **吳權晏** :wave:,<br>

我對於獲得新知識充滿喜悅，特別是在機器學習領域中，從學習和理解模型、到架構和修改模型、以及將模型應用到各種例子中，這些過程都讓我感到有趣與驚喜。遇到問題時，思考原因尋找方法，在解決時能感受到自己又有所收穫。隨著AI快速成長與普及，期許自己能吸收新知的同時，將之應用於生活中的大小事。



<div class="row">
    <div class="col" style="font-size: 1.5em; line-height: 2;">
    {% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
    </div>
    <div class="col">
    {% include about/skills.html title="Other Skills" source=site.data.other-skills heading_level=3 %}
    {% include about/skills.html title="Hobbies" source=site.data.hobby heading_level=3 %}
    </div>
</div>

<div class="row">
{% include about/detail.html %}
</div>

<!--
<div class="row">
{% include about/timeline.html %}
</div>
-->