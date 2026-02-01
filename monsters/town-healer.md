---
layout: monster
title: Town Healer
permalink: /monsters/town-healer/

subtitle: A practical herbalist tending wounds, sickness, and superstition.
description: A non-combatant town healer who relies on herbs, poultices, and experience rather than magic.

# Organization / filtering
tags: [npc, humanoid, urban]
role: support

# =========================================================
# Statblock data
# =========================================================

# Identity
size: Medium
creature_type: humanoid (any race)
alignment: any

# Core stats
ac: 11
hp: 9 (2d8)
speed: 30 ft.

# Ability scores
abilities:
  str: { score: 9, mod: "-1" }
  dex: { score: 11, mod: "+0" }
  con: { score: 11, mod: "+0" }
  int: { score: 12, mod: "+1" }
  wis: { score: 14, mod: "+2" }
  cha: { score: 10, mod: "+0" }

# Optional lines
skills: Medicine +4, Nature +3
senses: passive Perception 12
languages: Common
cr: 1/8 (25 XP)

# Traits
traits:
  - name: Practical Healer
    text: >
      Once per day, the town healer can tend to a creature within 5 feet, restoring
      1d6 hit points or stabilizing the creature if it is dying. This is not magical healing.

  - name: Herbal Knowledge
    text: >
      The town healer has advantage on Medicine checks related to disease, poison,
      or long-term injuries.

# Actions
actions:
  - name: Improvised Strike
    text: >
      <em>Melee Weapon Attack:</em> +1 to hit, reach 5 ft., one target.
      <em>Hit:</em> 2 (1d4) bludgeoning damage.

---

## At a glance
- **Role:** Support
- **Threat:** Low — avoids combat whenever possible
- **Environment:** Villages, frontier towns, rural settlements
- **Signature:** Mundane healing without magic

## Tactics
- Avoids combat and seeks cover immediately
- Prioritizes stabilizing wounded allies or civilians
- Will surrender or flee rather than fight to the death

## Encounter hooks
- Treating victims of a spreading illness or poison
- Knows which herbs are disappearing from nearby woods
- Pressured by authorities to falsify a cause of death

## Variants
- **Plague Doctor:** Advantage on saves against disease; wears a mask
- **Hedge Witch:** Add minor superstition flavor and local taboos
- **Battlefield Medic:** Increase HP to 13 (3d8); gains proficiency with shields
