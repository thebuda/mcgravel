---
layout: monster
title: Barkeeper
subtitle: A silver-tongued tavern hand who knows every table, door, and hiding spot.
description: A commoner-plus NPC built for fast table use, with a home-field edge inside their own bar.
permalink: /monsters/barkeeper/
tags: [npc, humanoid, social, urban]
role: controller

# Statblock data (auto-rendered by monster.html)
size: Medium
creature_type: humanoid (any race)
alignment: any

ac: 12 (leather apron)
hp: 9 (2d8)
speed: 30 ft.

abilities:
  str: { score: 10, mod: "+0", save: "+0" }
  dex: { score: 12, mod: "+1", save: "+1" }
  con: { score: 11, mod: "+0", save: "+0" }
  int: { score: 10, mod: "+0", save: "+0" }
  wis: { score: 11, mod: "+0", save: "+0" }
  cha: { score: 14, mod: "+2", save: "+2" }

skills: Insight +2, Persuasion +4
senses: passive Perception 10
languages: Common plus one other
cr: 1/4 (50 XP)

traits:
  - name: Master of the Bar
    text: >
      While inside their own tavern or bar, the barkeeper has advantage on Dexterity (Acrobatics) checks and on opportunity attacks.
      In addition, difficult terrain caused by furniture doesn’t cost the barkeeper extra movement.

  - name: Disarming Presence
    text: >
      The barkeeper has advantage on Charisma (Persuasion) checks made to calm hostile creatures that can hear them,
      provided the barkeeper and the target aren’t already engaged in combat.

actions:
  - name: Dagger
    text: >
      <em>Melee or Ranged Weapon Attack:</em> +3 to hit, reach 5 ft. or range 20/60 ft., one target.
      <em>Hit:</em> 4 (1d4 + 2) piercing damage.

  - name: Improvised Strike
    text: >
      <em>Melee Weapon Attack:</em> +2 to hit, reach 5 ft., one target.
      <em>Hit:</em> 2 (1d4) bludgeoning damage. This often represents a tankard, bottle, ladle, or chair-leg.

---

## At a glance
- **Role:** Controller (de-escalation + positioning)
- **Threat:** Low (but annoying on home turf)
- **Environment:** Taverns, inns, docks, back alleys
- **Signature:** Home-field advantage inside their own bar

## Tactics
- Try to **talk first**. The barkeeper’s goal is to stop a fight, not win one.
- If blades come out, fight **near furniture**—use tight angles and opportunity attacks.
- Use **Improvised Strike** when you want a nonlethal tavern-brawl vibe.

## Encounter hooks
- The barkeeper recognizes one PC from a past incident—and isn’t sure whether to help or sell them out.
- A regular vanished; the barkeeper knows who they left with, but won’t talk without leverage.
- Someone is paying for information from this bar, and the barkeeper is stuck in the middle.

## Variants
- **Hardcase Barkeeper (tougher):** HP 13 (3d8); add Athletics +3; Master of the Bar also grants advantage on Dexterity saving throws while in the bar.
- **Well-Connected Owner (social):** Replace Dagger with a light crossbow behind the counter; add Deception +4; Disarming Presence works even if a fight has started (once per scene, one creature that can hear them).
