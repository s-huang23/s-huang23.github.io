---
layout: default
title: About
---

<div class="about-header">
  <img class="headshot" src="{{ '/assets/images/headshot.jpg' | relative_url }}" alt="{{ site.author.name }}">
  <div class="about-meta">
    <h1 class="name">{{ site.author.name }}</h1>
    {% if site.author.title != "" %}<p class="title">{{ site.author.title }}</p>{% endif %}
    {% if site.author.location != "" %}<p class="location">{{ site.author.location }}</p>{% endif %}
  </div>
</div>

<div class="prose" markdown="1">

Hi, I'm Si Qin! My name is pronounced like the small ornament sequin.

I am currently a Master of data science student at Rice University. I aspire to leverage AI/ML to generate meaningful insights while learning and exploring interdisciplinary applications of AI/ML. I have previous hands-on experience in full-stack development and product ownership.

Currently located in Houston, TX but I grew up in Las Vegas, NV.

{% include social.html %}

</div>
