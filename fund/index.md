---
layout: page
title: 基金
excerpt: "基金 资管"
search_omit: true
---
   
&nbsp;  
  
<ul class="post-list">
{% for post in site.categories.fund %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
