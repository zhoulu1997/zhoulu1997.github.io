---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

教育经历 Education
======
* 清华大学自动化系，工学学士，2019
* Bachelor of Engineering in Automation, Tsinghua University,2019
* 清华大学教育研究院，管理学硕士，2022
* Master of Management in Public Administration,Tsinghua University,2022
* 清华大学教育研究院，教育学博士研究生（在读）
* Ph.D student in Education, Tsinghua University


期刊文章 Journal Articles
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
学术会议 Conferences
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
其他产出 Other Publications
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
