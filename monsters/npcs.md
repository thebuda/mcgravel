---
layout: page
title: NPCs
permalink: /monsters/npcs/
---

<p class="page-intro">
Everyday townsfolk, officials, and civilians. These NPCs are designed for social scenes,
investigation, and low-level conflict — not heroic combat.
</p>

<ul class="monster-list">
{% assign npc_monsters = site.monsters | where_exp: "m", "m.tags contains 'npc'" | sort: "title" %}
{% for monster in npc_monsters %}
  <li class="monster-list-item">
    <a href="{{ monster.url }}">{{ monster.title }}</a>
    {% if monster.subtitle %}
      <span class="monster-subtitle"> — {{ monster.subtitle }}</span>
    {% endif %}
  </li>
{% endfor %}
</ul>

{% if npc_monsters.size == 0 %}
<p>No NPCs found.</p>
{% endif %}
