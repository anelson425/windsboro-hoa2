---
layout: page
title: "Contacts"
meta_title: "Contact Us"
subheadline: ""
teaser: ""
permalink: "/contacts/"
header:
  image_fullwidth: header_windsboro.jpg
general_inbox: windsboro.charleston.hoa@gmail.com
---

<div class="medium-30 columns">
  General Inbox: <a href="mailto:{{ page.general_inbox }}">{{ page.general_inbox }}</a>

  <h2 class="font-size-h2 t10">Board Members</h2>
  {% include _contact.html members=site.data.board_members %}

  <h2 class="font-size-h2 t10">Committee Members</h2>
  {% include _contact.html members=site.data.committee_members %}
</div>
