---
layout: page
title: Blog
tagline: The blog for all things performance testing, brought to you by the people behind SmartLoad  
permalink: /blog/
---

SmartLoad's blog is constantly updated with documentation, best practices and business strategies around building an efficient performance testing strategy  

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt}} <!-- automatically pulls the first paragraph from jekyll in front matter, preprogrammed -->
    </li>
  {% endfor %}
</ul>
