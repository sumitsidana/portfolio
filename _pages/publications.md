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
  {% include archive-single.html %}
{% endfor %}

<p>

<h3>Journals</h3>

1. Health monitoring on social media over time
2. User preference and embedding learning with implicit feedback for recommender systems
</p>

<p>

<h3>Conferences</h3>

1. KASANDR: a large-scale dataset with implicit feedback for recommendation
2. Learning to recommend diverse items over implicit feedback on PANDOR
3. A combination of classification based methods for recommending tweets
4. Health Monitoring on Social Media over Time
</p>