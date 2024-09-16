---
layout: page
title: Black and White Packets
permalink: /bw-packets/
---

<ul>
{% for packet in site.data.bw %}
  <li>
    <a href="https://github.com/sher1/hatchpatch/blob/main/songs/{{ packet.pdf }}">
      {{ packet.title }} - {{packet.type}}
    </a>
  </li>
{% endfor %}
</ul>
