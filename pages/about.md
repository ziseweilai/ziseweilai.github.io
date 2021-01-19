---
layout: page
title: About
description: 学习使我快乐
keywords: Yaqiang Wei, 位亚强
comments: true
menu: 关于
permalink: /about/
---

我是位亚强，学习使我快乐。


拼搏到无能为力，努力到感动自己。

## 教育经历
2015年-2019年  太原理工大学  学士学位

2019-至今      中国科学院大学  硕博连读

## 论文
暂无

## 专利
暂无

## 科研项目
暂无

## 联系

<!--<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'https://ziseweilai.github.io/' %}
{% endif %}
</ul>
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/gongzhonghao.jpg" alt="孔孟圣人" />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/gongzhonghao.jpg" alt="孔孟圣人" />
</li>
{% endif %}
</ul>
<div style="text-align:center"><img src ="https://raw.githubusercontent.com/ziseweilai/ziseweilai.github.io/master/images/pages/gongzhonghao.jpg" /></div>
- Github： [@ziseweilai](https://github.com/ziseweilai)
- Blog： [@ziseweilai](https://ziseweilai.github.io)
- 微信公众号：孔仁孟义（krmy2020）
<div align="center"><img width="192px" height="192px" src="https://github.com/ziseweilai/ziseweilai.github.io/raw/master/images/posts/gongzhonghao.jpg"/></div>-->

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'ziseweilai.github.io/' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/gongzhonghao.jpg" alt="孔仁孟义" />
</li>
{% endif %}
</ul>

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
