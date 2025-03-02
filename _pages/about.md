---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm Yu Haoyuan.

I'm a third year undergraduate student from [HNU of CSEE](http://csee.hnu.edu.cn/), [Hunan University](https://www.hnu.edu.cn/).

I am studying computer courses and have a strong interest in computer vision.

# news

(December 21, 2024) Our work on egocentric speaker diarization has been accepted to ICASSP 2025!

# publications

{% for publication in site.publications %}
* **[{{ publication.title }}]({{ publication.link }})**
    * Authors: {{ publication.authors }}
    * Conference: {{ publication.conference }}, {{ publication.year }}
{% endfor %}