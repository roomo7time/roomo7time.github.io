---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: me.jpeg
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # rendered manually in the body below under a "publications" heading
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

My research focuses on anomaly detection, particularly the theoretically principled bottlenecks in distinguishing anomalies from normal data and the scalability of detection algorithms as training data grows. In addition, I investigate how the foundational priors captured in modern generative and language models—such as diffusion models and LLMs—can be leveraged to extend anomaly detection across diverse application domains.

<h2><a href="{{ '/publications/' | relative_url }}" style="color: inherit;">publications</a></h2>

<div class="publications">
{% bibliography %}
</div>
