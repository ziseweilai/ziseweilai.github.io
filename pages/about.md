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
[[1]赵国贞,梁卫国,赵晨德,杨智文,位亚强. 一种基于有导师学习神经网络算法的导水裂隙带预测方法[P]. 山西省：CN111274736A,2020-06-12.](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=SCPD&dbname=SCPD2020&filename=CN111274736A&v=ewD0FiOt%25mmd2FEqmdPIu%25mmd2BnVjo1pUJZZnCY9u2xu99idB3%25mmd2FPvFfiZwMibAVtSVjaBDIMm)

## 科研项目
暂无

## 联系

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
