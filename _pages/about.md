---
layout: archive
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Hi, I'm Xinrui Liu, a second-year computer science Ph.D student at Cornell University. I'm working with Prof. Abe Davis studying human-computer interaction. Specifically, I'm interested in eye tracking, VR/AR, and interaction designs for content creation. 

Prior to my Ph.D study, I obtained the Bachelor of Science degree from University of Wisconsin-Madison with majors in computer science, neurobiology, and mathematics. During my undergraduate time, I worked in Prof. Ari Rosenberg's lab doing eye-tracking-related work. I also worked with Prof. Matthew I. Banks and Prof. Barry Van Veen analyzing human brain electrophysiological data. 

<!-- Below is a list of my publications. Please check other pages to learn more about me.

<br/>

# Publications

{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->