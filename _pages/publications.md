---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  <div class="publication-entry">
    {% include archive-single.html %}
    {% if post.image %}
      <div class="publication-image">
        <img src="{{ base_path }}/images/{{ post.image }}" alt="{{ post.title }} image" style="max-width: 300px; margin-top: 10px;">
      </div>
    {% endif %}
  </div>
{% endfor %}