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
        <h4><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>&nbsp;<i>{{ post.date | date_to_string }}</i></h4>
      </li>
    {% endfor %}
  </ul>
</div>
