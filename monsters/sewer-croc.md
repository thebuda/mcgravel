---
layout: monster
title: Sewer Crocodilian
permalink: /monsters/sewer-crocodilian/

subtitle: An ancient ambush predator lurking beneath the city.
description: A massive crocodilian adapted to sewer tunnels, dragging prey into black water to drown.

tags: [beast, sewer, urban]
role: striker

size: Large
creature_type: beast
alignment: unaligned

ac: 14 (natural armor)
hp: 68 (8d10 + 24)
speed: 20 ft., swim 40 ft.

abilities:
  str: { score: 18, mod: "+4" }
  dex: { score: 12, mod: "+1" }
  con: { score: 16, mod: "+3" }
  int: { score: 2,  mod: "-4" }
  wis: { score: 12, mod: "+1" }
  cha: { score: 5,  mod: "-3" }

skills: Stealth +5, Perception +3
senses: darkvision 30 ft., passive Perception 13
languages: "-"
cr: 3 (700 XP)

traits:
  - name: Sewer Ambusher
    text: >
      The sewer crocodilian has advantage on Dexterity (Stealth) checks made in water,
      filth, or dim light. If it hits a creature it was hidden from, the attack deals an
      extra 7 (2d6) damage.

  - name: Hold Breath
    text: >
      The sewer crocodilian can hold its breath for up to 30 minutes.

actions:
  - name: Multiattack
    text: >
      The sewer crocodilian makes two attacks: one with its bite and one with its tail.

  - name: Bite
    text: >
      <em>Melee Weapon Attack:</em> +6 to hit, reach 5 ft., one target.
      <em>Hit:</em> 15 (2d10 + 4) piercing damage, and the target is grappled
      (escape DC 14). Until this grapple ends, the target is restrained.

  - name: Tail Swipe
    text: >
      <em>Melee Weapon Attack:</em> +6 to hit, reach 10 ft., one target.
      <em>Hit:</em> 9 (1d10 + 4) bludgeoning damage, and the target must succeed on a
      DC 14 Strength saving throw or be knocked prone.

bonus_actions:
  - name: Death Roll
    text: >
      The sewer crocodilian makes a Bite attack against a creature it is grappling.
      On a hit, the attack deals an extra 10 (3d6) damage, and the target must succeed
      on a DC 14 Constitution saving throw or be stunned until the end of its next turn.
---

## At a glance
- **Role:** Striker
- **Threat:** High in water or tight tunnels
- **Environment:** Flooded sewers, cisterns, collapsed tunnels
- **Signature:** Grapple → drag → death roll

## Tactics
- Begins combat hidden, attacking the first creature to step into water.
- Prioritizes grappling a single target and dragging them into deeper water.
- Uses **Death Roll** as soon as it has a restrained victim.
- If reduced below 25 HP, it disengages into submerged tunnels if possible.

## Encounter hooks
- Sewer workers report something “pulling people under” near an overflow tunnel.
- The creature has nested near an old storm drain blocking water flow.
- A criminal faction feeds captives to the beast to keep intruders away.

## Variants
- **Albino Crocodilian:** Blindsight 10 ft., loses darkvision.
- **Ancient Croc:** HP 102, Bite damage increases to 3d10, CR 4.
- **Scarred Survivor:** Missing tail (no Tail Swipe), but gains a reaction Bite when hit.
