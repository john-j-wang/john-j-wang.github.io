---
layout: about
title: about
permalink: /
subtitle: Department of Mathematics, Columbia Univeristy

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>New York, NY</p>
    <p>john.wang@columbia.edu</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Master of Arts candidate at **Columbia University**, expecting to graduate in January 2027. My passion is for probability and random events; I am interested in applications such as NLP, computer vision, and quantitative risk management.

Previously, I triple majored at **UC Berkeley** with a B.S. in Statistics and Data Science and a B.A. in Economics. My experience includes developing models for volatility surface calibration and implementing new reinforcement learning agents that learn to hedge risk in novel settings.

Outside of academics, I love hiking and taking landscape photos. I am currently on a [mission](https://www.instagram.com/questto63/) to see all 63 national parks in the United States; I am currently on number 8. On my most recent trip, I visited Zion and Death Valley National Park, where I hiked up Angels Landing and through the Narrows. In September, I plan on visiting Yosemite for the second time to scale Half Dome.

<div class="news">
  {% if site.announcements.enabled %}
    <br>
    <a href="{{ '/news/' | relative_url }}" style="color: var(--global-theme-color);">View all news...</a>
  {% endif %}
</div>