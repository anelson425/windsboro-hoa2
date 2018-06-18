---
layout: page
title: "Amenities"
permalink: "/amenities/"
header:
  image_fullwidth: header_windsboro.jpg
---

<div class="row t100">
  {% for amenity in site.data.amenities %}
    {% include _amenity-widget.html amenity=amenity %}
  {% endfor %}
</div><!-- /.row -->

