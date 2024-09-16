---
layout: page
title: Color Packets
permalink: /color-packets/
---

<ul>
{% for packet in site.data.color %}
  <li>
    <a href="https://github.com/sher1/hatchpatch/blob/main/songs/{{ packet.pdf }}">
      {{ packet.title }} - {{packet.type}}
    </a>
  </li>
{% endfor %}
</ul>
