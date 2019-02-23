---
layout: archive
title: "Page Archive"
permalink: /page-archive/
author_profile: false
---

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

<!-- <div class="posts">
  {% for post in paginator.posts %}
  {% if post.visible== 1  %}

  <div class="post">
    <h1>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>
        <a class="subtitle" href="{{ post.url }}">
           {{ post.excerpt }}
        </a>
      </a>
  </div>
  {% endif %}
  {% endfor %}
</div> -->
