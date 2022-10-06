---
layout: post
title:  "Welcome to application"
date:   2022-09-29 23:22:58 -0700
categories: application
author: "aptnetdb"
permalink: "/application1/"
---
This is a page for applications Hello


  <ul>
    {% for post in site.posts %}
      {% if post.categories == application %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
      {% endif %}
    {% endfor %}
  </ul>



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
