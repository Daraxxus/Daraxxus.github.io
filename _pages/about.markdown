---
title: About Me
permalink: /about/
---

# About Me
Hello! My name is Gary Seah and I am a aspiring software developer. I have been programming since I was 15.

# Qualifications
{% for item in site.data.qualifications %}
<span style='font-weight: bold;'>{{item.details.name_full}}</span>
<ul>
    <li><a href="{{item.details.website}}"> {{item.details.from}} </a></li>
    <li> {{item.details.year_start}} - {{item.details.year_end}} </li>
</ul>
{% endfor %}

# Notable Achievements

