---
layout: page
title: Blog
tagline: Best blog ever
permalink: /blog/
---

LoadNinja's blog is constantly updated with documentation and best practises regarding performance testing

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt}} <!-- automatically pulls the first paragraph from jekyll in front matter, preprogrammed -->
    </li>
  {% endfor %}
</ul>
