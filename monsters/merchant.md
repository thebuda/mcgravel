---
layout: monster
title: Merchant
permalink: /monsters/merchant/

subtitle: A practiced trader whose real weapons are words and coin.
description: A civilian merchant skilled in negotiation, deception, and self-preservation.

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
  con: { score: 10, mod: "+0" }
  int: { score: 12, mod: "+1" }
  wis: { score: 11, mod: "+0" }
  cha: { score: 15, mod: "+2" }

# Optional lines
skills: Deception +4, Persuasion +4, Insight +2
senses: passive Perception 10
languages: Common plus one regional language
cr: 1/8 (25 XP)

# Traits
traits:
  - name: Silver Tongue
    text: >
      The merchant has advantage on Charisma (Persuasion or Deception) checks made
      to negotiate prices, contracts, or favors.

  - name: Self-Preservation
    text: >
      When first reduced to half its hit points or fewer, the merchant may immediately
      attempt to flee, surrender, or offer a bribe as a reaction.

# Actions
actions:
  - name: Dagger
    text: >
      <em>Melee or Ranged Weapon Attack:</em> +2 to hit, reach 5 ft. or range 20/60 ft., one target.
      <em>Hit:</em> 4 (1d4 + 2) piercing damage.

---

## At a glance
- **Role:** Support
- **Threat:** Low — dangerous socially, not physically
- **Environment:** Markets, caravans, trade roads, port towns
- **Signature:** Negotiation under pressure

## Tactics
- Avoids violence whenever possible
- Uses allies, guards, or crowds as cover
- Attempts to de-escalate with bribes or concessions

## Encounter hooks
- Selling goods tied to a recent crime or smuggling ring
- Knows who is buying unusual supplies in bulk
- Desperate to recover stolen merchandise discreetly

## Variants
- **Caravan Trader:** Increase HP to 13 (3d8); add Animal Handling +2
- **Black Market Dealer:** Replace Persuasion with Intimidation; add Stealth +2
- **Guild Factor:** Advantage on checks involving contracts, tariffs, or permits
