---
layout: monster
title: Sewer Ghoul
permalink: /monsters/sewer-ghoul/

subtitle: A drowned corpse animated by hunger and rot.
description: A feral undead that lurks in sewer tunnels, spreading filth and disease with every bite.

tags: [undead, sewer, urban]
role: striker

size: Medium
creature_type: undead
alignment: chaotic evil

ac: 12 (natural armor)
hp: 30 (4d8 + 12)
speed: 30 ft., climb 20 ft.

abilities:
  str: { score: 13, mod: "+1" }
  dex: { score: 14, mod: "+2" }
  con: { score: 16, mod: "+3" }
  int: { score: 7,  mod: "-2" }
  wis: { score: 10, mod: "+0" }
  cha: { score: 6,  mod: "-2" }

skills: Stealth +4, Perception +2
senses: darkvision 60 ft., passive Perception 12
languages: Common (broken)
cr: 1 (200 XP)

traits:
  - name: Filth-Rot
    text: >
      A creature damaged by the sewer ghoul’s bite must succeed on a DC 12 Constitution
      saving throw or be poisoned until the end of its next turn. If the creature is
      already poisoned, it instead takes 5 (1d10) necrotic damage.

  - name: Sewer Scuttler
    text: >
      The sewer ghoul can climb difficult surfaces, including slick stone and brick,
      without needing to make an ability check.

actions:
  - name: Multiattack
    text: >
      The sewer ghoul makes two attacks: one with its claws and one with its bite.

  - name: Claws
    text: >
      <em>Melee Weapon Attack:</em> +4 to hit, reach 5 ft., one target.
      <em>Hit:</em> 5 (1d6 + 2) slashing damage.

  - name: Bite
    text: >
      <em>Melee Weapon Attack:</em> +4 to hit, reach 5 ft., one target.
      <em>Hit:</em> 6 (1d8 + 2) piercing damage plus Filth-Rot.
---

## At a glance
- **Role:** Striker
- **Threat:** Medium — damage escalates if ignored
- **Environment:** Sewers, flooded tunnels, drainage cisterns
- **Signature:** Poison → necrotic follow-up pressure

## Tactics
- Ambushes from walls or ceilings where possible.
- Spreads attacks across targets to trigger Filth-Rot.
- Focuses on already wounded or poisoned enemies.
- Fights until destroyed; hunger overrides self-preservation.

## Encounter hooks
- Bodies found half-submerged, teeth marks clogged with sludge.
- A sewer collapse disturbed an old burial tunnel.
- A necromancer’s experiment leaked into the drainage system.

## Variants
- **Drowned Ghoul:** Gains a swim speed and advantage on attacks made underwater.
- **Plague Carrier:** Filth-Rot poison lasts 1 minute (CR 2).
- **Ash-Rot Ghoul:** Necrotic damage becomes fire damage from smoldering decay.
