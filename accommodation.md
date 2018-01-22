---
title: Accommodation
layout: "page"
icon: fa-hotel
order: 3
---

Here is a list of nearby hotels. We haven't stayed at any of them ourselves, so we would advise looking at online reviews before booking.

{% google_map width="100%" src="_data" %}  

{% for hotel in site.data.accommodation %}
* [{{ hotel.title }}]({{ hotel.url }}), {{ hotel.address }}{% endfor %}
* Plus pubs, B&Bs, and Airbnb options in Yate, Chipping Sodbury, Bradley Stoke, Stoke Gifford, Harry Stoke, Little Stoke, Almondsbury, Filton, Patchway.
