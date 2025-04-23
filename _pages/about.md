---
layout: about
title: about
permalink: /
subtitle: <a href='#'>National University of Singapore</a>. School of Computing.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: 

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---



My name is Tiancheng Xing(邢天骋). I'm currently a Master student at School of Computing,  National University of Singapore(NUS). I'm working as a student researcher in TEST lab at NUS, advised by Prof.Manuel Rigger. Before that, I obtained my bachelor's degree in Software Institute, Nanjing University(NJU).



I'm currently working on Database Testing and some LLM topics.

```{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}```