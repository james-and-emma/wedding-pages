---
title: Taxis
layout: "page"
icon: fa-taxi
order: 4
---

Public transport is limited around our wedding venue. If you need a taxi, we suggest using one of the following options:

{% for taxi in site.data.taxis %}
* {% if taxi.url %}[{{ taxi.title }}]({{ taxi.url }}){% else %}**{{ taxi.title }}**{% endif %} -    Phone: {{ taxi.phone1 }}{% if taxi.phone2 %}, {{ taxi.phone2 }}{% endif %}{% if taxi.email %};  Email: {{ taxi.email }}{% endif %}{% endfor %}

For more local taxis, see [this link](https://www.thomsonlocal.com/Taxis/in/Winterbourne-Avon/).