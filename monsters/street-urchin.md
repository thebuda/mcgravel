---
layout: monster
title: Street Urchin
permalink: /monsters/street-urchin/

subtitle: A sharp-eyed survivor who hears everything and trusts no one.
description: A quick, observant street child adept at deception, evasion, and gathering information.

# Organization / filtering
tags: [npc, humanoid, urban]
role: support

# =========================================================
# Statblock data
# =========================================================

# Identity
size: Small
creature_type: humanoid (any race)
alignment: any

# Core stats
ac: 12
hp: 7 (2d6)
speed: 30 ft.

# Ability scores
abilities:
  str: { score: 8, mod: "-1" }
  dex: { score: 14, mod: "+2" }
  con: { score: 10, mod: "+0" }
  int: { score: 12, mod: "+1" }
  wis: { score: 14, mod: "+2" }
  cha: { score: 13, mod: "+1" }

# Optional lines
skills: Deception +5, Perception +4, Stealth +4, Insight +4
senses: passive Perception 14
languages: Common
cr: 1/8 (25 XP)

# Traits
traits:
  - name: Streetwise Observer
    text: >
      The street urchin has advantage on Wisdom (Perception) checks made to notice
      suspicious behavior, concealed objects, or people attempting to avoid attention
      in urban environments.

  - name: Practiced Deception
    text: >
      The street urchin has advantage on Charisma (Deception) checks made to lie
      about its identity, intentions, or recent actions.

# Actions
actions:
  - name: Improvised Weapon
    text: >
      <em>Melee or Ranged Weapon Attack:</em> +4 to hit, reach 5 ft. or range 20/60 ft., one target.
      <em>Hit:</em> 3 (1d4 + 2) bludgeoning or piercing damage.

---

## At a glance
- **Role:** Support
- **Threat:** Low — evasive, not confrontational
- **Environment:** Cities, slums, markets, docks
- **Signature:** Notices what others miss and lies without hesitation

## Tactics
- Avoids direct confrontation at all costs
- Uses crowds, corners, and elevation to escape
- Lies reflexively, even when telling the truth would suffice

## Encounter hooks
- Witnessed a crime but is telling conflicting stories
- Knows which alleyways are suddenly being avoided
- Carrying information worth more than any coin

## Variants
- **Pickpocket:** Add Sleight of Hand +4; increase Dexterity to 16
- **Runner:** Increase speed to 35 ft.; advantage on Dash checks in crowds
- **Gang Lookout:** Advantage on Perception checks to spot approaching guards
