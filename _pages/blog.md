---
title: "Air Mail - Blog"
layout: blog
excerpt: "Air Care - Blog"
sitemap: false
permalink: /blog/
---

# Air Mail by Nirvan Bhattacharyya
### A Blog about Atmospheric Science, Travel, and Other

<div>
  <ul style="list-style-type:None;">
    {% for post in site.posts %}
      <li>
        <u><h3><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3></u>
        <i>{{ page.date | date_to_string }}</i>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>
</div>
