---
layout: "post"
title:  "Qualifications"
date:   2020-09-25 13:40:40 +0100
categories: jekyll update
---
<b> Qualifications:<b> <br>
<br>
{% for person in site.data.people %} 
  {{ person.name }}, {{ person.surname }} <br>
{% endfor %}