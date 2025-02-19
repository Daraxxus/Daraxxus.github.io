---
title: Projects and Achievements
permalink: /Projects_Achievements/
---

# Achievements
{% for item in site.data.achievements %}
<span style='font-weight: bold;'><a href="{{site.projects}}{{item.details.link}}"> {{item.achievementname}} </a></span>
<p> {{item.details.eventname}} | {{item.details.when}} <br> Issued by {{item.details.issuedby}} </p>
<hr>
<p> {{item.details.description}} <br> <br> </p>
{% endfor %}
