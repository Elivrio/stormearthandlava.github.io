---
layout: page
title: Elemental hidden tricks
last_update: 24/07/2024
game_version: 11.0.0 Dragonflight
toc: true
big_article: true
---

# Welcome, read First

This page aims to display and discuss the recommended and most widely-used Builds available to Elemental. This is not an exhaustive list of all options and *does not imply that any build **not** shown here is automatically terrible/unplayable*.  
In practical terms we cannot account for every build variation and effort has been largely focused on the highest performing / most popular builds. If you find something that you feel works or performs better than what is listed here feel free to contact the team on [Storm, Earth & Lava Discord](https://discord.gg/y5dUf3PWrU) or [Earthshrine #Elemental Channel](https://discord.gg/earthshrine)

<hr>
# Lava Burst
Probably the most basic interaction but you have to start this guide somewhere: {{ site.data.spell.lvb }} crit are calculated on-hit and not on cast. Which means you can cast {{ site.data.spell.lvb }} into {{ site.data.spell.fs }} and guarantee that {{ site.data.spell.lvb }} will crit.

This is especially useful on pre-pulls, where you should cast {{ site.data.spell.lvb }} 1.8s before pull then {{ site.data.spell.fs }} on pull.

<hr>
# Fire and Storm Elemental pre-pull

{{ site.data.spell.fe }} and {{ site.data.spell.se }} will start attacking your target if you cast them while targeting an enemy, even if you are not in combat.

As you mostly care about their side effect and not their direct damage, you want to cast them pre-pull to gain uptime on the boss.  

So how do you do that? Quite simply frankly. You clear targets, cast your Elemental, then target your enemy and start casting. Be warned that `/cleartarget` macros (and all macros in general) do not work to make this process automatic. It used to, but was fixed in DF prepatch.

<hr>
# Mastery, Overloads and Chain Lightning



<hr>
# Liquid Magma Totem

### 1. Using Liquid Magma Totem to spread Flame Shock

There's some logic in how {{ site.data.spell.lmt }} applies {{ site.data.spell.fs }}:
- If there are 3 targets without {{ site.data.spell.fs }} in range, {{ site.data.spell.lmt }} will smartly apply {{ site.data.spell.fs }} to them. 
- If there aren't, it will target either random or enemies nearest to it. 

It's also worth noting that {{ site.data.spell.lmt }} is very bad with verticality and often misses mobs that are above or below it (like on a hill).

Going into a pack with some leftover maelstrom, you'll want to do something like this to spread {{ site.data.spell.fs }} efficently : 
1. {{ site.data.spell.pw }} 
1. {{ site.data.spell.eq }} 
1. {{ site.data.spell.fs }} with {{site.data.spell.sop }}
1. {{ site.data.spell.lmt }}

<br>
### 2. Liquid Magma Totem also does damage
{{ site.data.spell.lmt }} is not only a spreading tool, it does a lot of damage and scales with haste.
if you are planning to use 2 {{ site.data.spell.lmt }} in a pack thanks to :TR:, the second one should (almost) never be used as a spreadtool. Since {{ site.data.spell.lmt }} scales with haste, you want to get :SpE: before  using that second totem. Cast sequence will be similar to this going into a pack with leftover maelstrom:
1. {{ site.data.spell.pw }} 
1. {{ site.data.spell.eq }} 
1. {{ site.data.spell.fs }} with {{site.data.spell.sop }}
1. {{ site.data.spell.lmt }}
1. {{ site.data.spell.lvb }}
1. {{ site.data.spell.totemic_recall }}
1. {{ site.data.spell.lmt }}

<br>
### 3. Liquid Magma Totem is a frail Lady
Do. Not. Kill. {{ site.data.spell.lmt }}. It can rip aggro if you put it down before tank gets aggro and it will get one shotted. 

Sure, it already spread {{ site.data.spell.fs }} but you're still losing a lot of damage.

<hr>
# Deeply Rooted Elements

Casting {{ site.data.spell.lava_burst }} has an ever increasing chance to trigger {{ site.data.spell.ascendance }}, starting with a double 0% chance then incrementing by 1% per cast (0%, 0%, 1%, 2%, 3%, 4%, ...). This averages out to the 7% chance stated by the tooltip.

<img src="/assets/img/guide/DRE_proc_chart.png" alt="DRE proc Chart">

This behaviour implies low chance of back to back procs, as well as low chance of no procs for a extended period. 

What becomes apparent is that you can and should play around your current proc chance. Let's say you're at the end of a mythic+ pack and your {{ site.data.spell.dre }} counter is at 11%. You're likely to proc {{ site.data.spell.asc }} in your next 3 to 5 {{ site.data.spell.lvb }} casts. If you stop casting {{ site.data.spell.lvb }} until next pack, you increase your chance of proccing {{ site.data.spell.asc }} when it matters in the next pack instead of proccing it on almost dead mobs.

This weakaura (must include link, ping me in Discord if I forgot to update this line) will help you track your {{ site.data.spell.dre }} counter in game and play around it.

<hr> 
# Flash of Lightning

Sometimes assessing the strength of talents is tricky, arguably one of the best examples of this is {{ site.data.spell.fol }}.
This is because the game does no real work to inform you what "Nature" spells are. To help with this, here is a list of all the known spell cooldowns that are reduced by {{ site.data.spell.fol }}.

- {{ site.data.spell.ag }}
- {{ site.data.spell.as }}
- {{ site.data.spell.bl }}
- {{ site.data.spell.capacitor_totem }}
- {{ site.data.spell.cleanse_spirit }}
- {{ site.data.spell.earthbind_totem }}
- {{ site.data.spell.earthgrab_totem }}
- {{ site.data.spell.ee }}
- {{ site.data.spell.fs }}
- {{ site.data.spell.greater_purge }}
- {{ site.data.spell.gow }}
- {{ site.data.spell.healing_stream_totem }}
- {{ site.data.spell.hex }}
- {{ site.data.spell.lightning_lasso }}
- {{ site.data.spell.ns }}
- {{ site.data.spell.pct }}
- {{ site.data.spell.pw }} (soon TM)
- {{ site.data.spell.ankh }}
- {{ site.data.spell.swg }}
- {{ site.data.spell.sbt }} (soon TM)
- {{ site.data.spell.se }}
- {{ site.data.spell.sk }}
- {{ site.data.spell.thunderstorm }}
- {{ site.data.spell.totemic_projection }}
- {{ site.data.spell.totemic_recall }}
- {{ site.data.spell.tremor_totem }}
- {{ site.data.spell.wrt }}
- {{ site.data.spell.wind_shear }}

Spells that it doesn't work with but maybe should?
- {{ site.data.spell.spirit_walk }}

<hr>
# Future ideas
### New Icefury
Deck of card? 
### Fusion of the Elements 
How to efficiently proc it

<hr>

Are there other tips and tricks that you think should make the list? Feel free to ping elivrio in Earthshrine and let me know how you feel!