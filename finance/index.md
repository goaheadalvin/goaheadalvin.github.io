---
layout: page
title: 金融相关
excerpt: "金融 CFA 基金 证券"
search_omit: true
---
   
&nbsp;  
  
<ul class="post-list">
{% for post in site.categories.finance %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
