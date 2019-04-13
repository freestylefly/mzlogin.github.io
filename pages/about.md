---
layout: page
title: About
description: 打码改变世界
keywords: Zhuang Ma, 马壮
comments: true
menu: 关于
permalink: /about/
---

我是苍何。

我举手向苍穹，并非一定摘到星月，只是想保持这个永不屈服的姿势。

人生中一个决定牵动另一个决定，一个偶然决定另一个偶然，因此偶然从来不是偶然，一条路势必走向下一条路，回不了头。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
