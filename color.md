---
layout: page
title: Color Packets
permalink: /color-packets
---
<ul>
{% for song in site.data.songss %}
  <li>
    <a href="https://github.com/sher1/hatchpatch/blob/main/songs/{{ song.file }}">
      {{ song.title }} - {{song.description}}
    </a>
  </li>
{% endfor %}
</ul>