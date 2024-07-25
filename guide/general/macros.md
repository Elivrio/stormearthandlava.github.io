---
layout: page
title: Macros
last_update: 02/05/2023
game_version: 10.1.0 Dragonflight
toc: true
---

# Macros for Elemental Shaman

This page lists useful macros for playing as an Elemental Shaman in Dragonflight. It is sorted into Rotational Abilities, Cooldowns, Utility and Talent Tree Swap.
If you have suggestions to improve macros found on this page, or additional macros that are missing, please use the [Storm, Earth & Lava Discord Server to report issues](https://discord.gg/y5dUf3PWrU), alternatively seek out an Elemental MVP or Moderator on the [Earthshrine Discord Server](https://discord.gg/pGkPDzh7rP).

**Disclaimer:** Your client must be in English for these macros to work. If you play in another language, the abilities must be translated to your client's language.

# Rotational Abilities

## 1. Flame Shock

This macro will cast {{ site.data.spell.fs }} at your current Mouseover target if it is an enemy, otherwise will cast it on your current target.

```
#showtooltip
/use [@mouseover,harm,nodead][]Flame Shock
```

<br>

## 2. Primordial Wave

This macro will cast {{ site.data.spell.pw }} at your current Mouseover target if it is an enemy, otherwise will cast it on your current target.

```
#showtooltip
/use [@mouseover,harm,exists][harm]Primordial Wave
```

<br>

## 3. Earthquake

This macro will cast {{ site.data.spell.eq }} at the current location of your cursor without targeting reticule.

```
#showtooltip
/use [@cursor]Earthquake
```

<hr>

# Cooldowns

## 1. Primordial Elementalist or Liquid Magma Totem

This macro will use either {{ site.data.spell.tempest }} or {{ site.data.spell.meteor }} when {{ site.data.spell.pe }} is talented, or {{ site.data.spell.lmt }} at your Cursor location if it is talented.

```
#showtooltip
/use [known:Liquid Magma Totem,@cursor]Liquid Magma Totem;[noknown:Liquid Magma Totem,known:Storm Elemental]Tempest;[noknown:Liquid Magma Totem,known:Fire Elemental]Meteor
```

<br>

## 2. Elemental and Primordial Elementalist

This macro will summon your currently talented Elemental, and when pressed again the associated {{ site.data.spell.pe }} spell for them.

```
#showtooltip
/use [pet:Primal Storm Elemental]Tempest;[pet:Primal Fire Elemental]Meteor
/use [known:Storm Elemental]Storm Elemental;[known:Fire Elemental]Fire Elemental
```
*Note: This macro does not include {{ site.data.spell.lmt }}.*

<hr>

# Interrupts - Wind Shear
There are many ways to macro interrupt abilities, below are some examples only use whichever setup enables you to play most reliably:

## 1. Focus Kick
This macro will use {{ site.data.spell.wind_shear }} at your Focus if you have one, otherwise will interrupt your current target.

```
#showtooltip
/use [@focus,harm,exists,nodead][]Wind Shear
```

<br>

## 2. Mouseover Kick
This macro will use {{ site.data.spell.wind_shear }} on current Mouseover target if it is an enemy, otherwise will interrupt your current target.

```
#showtooltip
/use [@mouseover,harm,nodead][]Wind Shear
```

<br>

## 3. Focus + Mouseover Kick
This macro will use {{ site.data.spell.wind_shear }} at your Focus if you have one, try on your current Mouseover target if it is an enemy, otherwise will interrupt your current target.

```
#showtooltip
/use [@focus,harm,exists,nodead][@mouseover,harm,nodead][]Wind Shear
```

<br>

## 4. Specific target Kick

This macro works for specific interrupt uses, if you dislike using Focus or Mouseovers.

```
#showtooltip
/tar *enemy name here*
/use Wind Shear
/targetlasttarget
```

<hr>

# Combining similar spells

## 1. Earth Shield mouseover with Elemental Orbit 

This macro will use in that order:
- Use {{ site.data.spell.earth_shield }} on your mouseover if you are talented into {{ site.data.spell.elemental_orbit }} 
- Use {{ site.data.spell.earth_shield }} on self otherwise

```
#showtooltip
/use [@mouseover,help,nodead,known:383010][@player]Earth Shield
```

<br>

## 2. Purge/Decurse single macro

This macro will use in that order:
 - {{ site.data.spell.purge }} or {{ site.data.spell.greater_purge }} on your Mouseover target if it is an enemy,
 - {{ site.data.spell.cleanse_spirit }} on your Mouseover target if it is an enemy,
 - {{ site.data.spell.purge }} or {{ site.data.spell.greater_purge }} on current target if it is an enemy,
 - {{ site.data.spell.cleanse_spirit }} on your current target if it is an ally.

```
#showtooltip
/use [known:Purge,@mouseover,harm,nodead]Purge;[known:Greater Purge,@mouseover,harm,nodead]Greater Purge;[@mouseover,help,nodead]Cleanse Spirit;[known:purge,harm]Purge;[known:Greater Purge,harm]Greater Purge;[]Cleanse Spirit
```
*Note: This macro only works for Elemental and Enhancement. Restoration Shaman have Purify Spirit for their dispel.*

<br>

## 3. Chains Lightning/Heal single macro

This macro will use in that order:
 - {{ site.data.spell.cl }} on your Mouseover target if it is an enemy,
 - {{ site.data.spell.chain_heal }} on your Mouseover target if it is an enemy,
 - {{ site.data.spell.cl }} on current target if it is an enemy,
 - {{ site.data.spell.chain_heal }} on your current target if it is an ally.

```
#showtooltip
/use [@mouseover,harm,nodead]Chain Lightning;[@mouseover,help,nodead]Chain Heal;[harm]Chain Lightning;[]Chain Heal
```

<br>

## 4. Ancestral Spirit/Healing Surge single macro

This macro will use in that order:
- {{ site.data.spell.ancestral_spirit }} at your current Mouseover target if they are a dead ally
- {{ site.data.spell.healing_surge }} at your current Mouseover target if they are a living ally 
- {{ site.data.spell.ancestral_spirit }} at your current target if they are a dead
- {{ site.data.spell.healing_surge }} otherwise

```
#showtooltip
/use [@mouseover,help,dead]Ancestral Spirit;[@mouseover,help,nodead]Healing Surge;[dead]Ancestral Spirit;Healing Surge
```

<br>
## 5. Castsequence Buffs macro 

This macro put {{ site.data.spell.skyfury }}, {{ site.data.spell.lightning_shield }}, {{ site.data.spell.flametongue_weapon }} and {{ site.data.spell.thunderstrike_ward }} (if known) in the same keybind to avoid bar bloat. 

It will reset to {{ site.data.spell.skyfury }} after 3 seconds of not pressing it. The reset is in place to allow you to easily rebuff your raid multiple times mid pull.

```
#showtooltip
/castsequence [known:462757] reset=3 Skyfury, Lightning Shield, Flametongue Weapon, Thunderstrike Ward; [] reset=3 Skyfury, Lightning Shield, Flametongue Weapon
```

<hr>
# Totems at cursor location

## 1. Earthbind Totem

This macro will cast {{ site.data.spell.earthbind_totem }} at the current location of your cursor without targeting reticule.

```
#showtooltip
/use [@cursor]Earthbind Totem
```
*Note: this will work with {{ site.data.spell.earthgrab_totem }} without changing the macro*

<br>

## 2. Capacitor Totem

This macro will cast {{ site.data.spell.capacitor_totem }} at the current location of your cursor without targeting reticule.

```
#showtooltip
/use [@cursor]Capacitor Totem
```

<br>

## 3. Totemic Projection

This macro will cast {{ site.data.spell.totemic_projection }} at the current location of your cursor without targeting reticule.

```
#showtooltip
/use [@cursor]Totemic Projection
```
