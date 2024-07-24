---
layout: page
title: Class Tree
last_update: 22/07/2024
game_version: 11.0.0 The War Within
toc: true
big_article: true
---

# Overview: a versatile class tree

The Class tree is what we share with the other specs of Shaman. 
We have the luxury of having a very versatile Class tree that can basically adapt to any situation, with very few **mandatory** points. The choice will often be between two optional utilities.

With that being said, let's look at the content of the Class tree: 

<img src="/assets/img/guide/class_Tree.png" alt="Class Tree Classification" class="center">

## Red nodes: Always talent them
- {{ site.data.spell.lvb }} and {{ site.data.spell.cl }} are points given to us as Elemental Shaman
- {{ site.data.spell.as }}, {{ site.data.spell.planes_traveler }}, {{ site.data.spell.ee }}, {{ site.data.spell.primordial_bond }}, {{ site.data.spell.natures_guardian }}, {{ site.data.spell.brimming_with_life }} and {{ site.data.spell.elemental_warding }} are all primary defensive nodes
- {{ site.data.spell.stone_bulwark_totem }} is a new defensive totem in TWW, making it required of course
- Since {{ site.data.spell.totemic_recall }} works with {{ site.data.spell.stone_bulwark_totem }}, you always want it along with {{ site.data.spell.call_of_the_elements }}
- {{ site.data.spell.fire_and_ice }}, {{ site.data.spell.natures_fury }}, {{ site.data.spell.frs }} and the new {{ site.data.spell.enhanced_imbues }} are the few throughput nodes in our tree which we always want
- {{ site.data.spell.swg }} and {{ site.data.spell.graceful_spirit }} are too good to ever skip
- {{ site.data.spell.ag }} is our best group utility and should be used as much as possible

<br>
## Yellow nodes: Usually Good
- If the content you're doing doesn't require a kick, feel free to skip {{ site.data.spell.wind_shear }} and {{ site.data.spell.seasoned_winds }}. Otherwise, both are required talent
- {{ site.data.spell.gow }} and {{ site.data.spell.spirit_walk }} could be red nodes, given how many points we have to spend in the tree. Nonetheless, they are not exactly required and some might talent off of them. I would still pretty much always use them
- The exact same can be said for {{ site.data.spell.thunderous_paws }} and {{ site.data.spell.spirit_wolf }}
- {{ site.data.spell.wrt }} and its new follow up choice node, {{ site.data.spell.jet_stream }} vs {{ site.data.spell.ascending_air }}, is very recommended in most content, but could be skipped depending on your group composition
- {{ site.data.spell.earth_shield }} and {{ site.data.spell.elemental_orbit }} are defensive maintenance buff that are pretty low impact. A lot of players do not bother with it. It's still more than decent, especially if you maintain it between pulls in m+ or during downtime in raid
- {{ site.data.spell.refreshing_waters }} is a great talent to use in hard content (raid prog, m+ pushing, ...) but gets weaker as a patch progresses. Both your healer and you will get more gear, making you less vulnerable over time
- {{ site.data.spell.ns }} is yellow because it's a required node for the Farseer hero talents. If you are playing Stormbringer, it's a situational utility that can be skipped but great to get an extra movement global

<br>
## Green nodes: Situational Utility
- Crowd Control nodes: 
  - {{ site.data.spell.capacitor_totem }}, with {{ site.data.spell.guardians_cudgel }} or {{ site.data.spell.static_charge }}
  - {{ site.data.spell.thunderstorm }}, with {{ site.data.spell.thundershock }} or {{ site.data.spell.traveling_storms }}
  - {{ site.data.spell.hex }} and {{ site.data.spell.voodoo_mastery }}
  - {{ site.data.spell.earthgrab_totem }}
- Utility nodes:
  - {{ site.data.spell.purge }} and {{ site.data.spell.cleanse_spirit }} are perfect examples of good talents that are purely situational and can be skipped in many builds, and picked only when needed
  - {{ site.data.spell.tremor_totem }}
  - {{ site.data.spell.pct}}

<br>
## Blue nodes: Low impact or pathing nodes
- {{ site.data.spell.healing_stream_totem }}, paired with {{ site.data.spell.elemental_resistance }}, is a fire and forget group cd that has multiple severe drawbacks, namely:
  - It's on the GCD, making you lose a cast
  - You cannot control its target, making it unpredictible and globally low "relevant" healing
  - With {{ site.data.spell.inundate }} being passive in TWW, you will gain 8 maelstrom when you using it
  - Nonetheless, {{ site.data.spell.elemental_resistance }} is not negligeable DR when it works and it makes for a good pathing node toward {{ site.data.spell.elemental_warding }}
- {{ site.data.spell.totemic_focus }} is nice for {{ site.data.spell.wrt }} or {{ site.data.spell.hst }} duration, but is mostly used for pathing toward {{ site.data.spell.stone_bulwark_totem }}
- Similarly, {{ site.data.spell.totemic_projection }} has some nice uses with {{ site.data.spell.wrt }} or {{ site.data.spell.earthgrab_totem }} but is mostly used for pathing
- {{ site.data.spell.totemic_surge }} is a small passive gains that you won't notice most of the time. It's mostly used for pathing when you do not have {{ site.data.spell.wind_shear }} to go with {{ site.data.spell.seasoned_winds }}
- {{ site.data.spell.mana_spring }} is better in raid content than it is in party, but lacking nonetheless. The numbers on it are too low to make it a good talent
- {{ site.data.spell.lightning_lasso }} can have some uses as an additional CC in m+, but the uptime loss makes it less relevant
- {{ site.data.spell.winds_of_alakir }} is on the brim of being grey, but giving additional {{ site.data.spell.ghost_wolf }} mobility in dungeon can be a cool gain if you have nothing else to pick

<br>
## Grey Nodes: Probably not played ever
- We don't really have any incentives to ever press {{ site.data.spell.chain_heal }}. Pairing it with {{ site.data.spell.natures_swiftness }} can be a small healing burst on a group but it's honestly too low to ever bother talenting it
- You cannot do damage in {{ site.data.spell.ghost_wolf }}, and {{ site.data.spell.ancestral_wolf_affinity }} helps when staying in {{ site.data.spell.ghost_wolf }}, making it non-ideal
- Even if  {{ site.data.spell.encasing_cold }} and {{ site.data.spell.arctic_snowstorm }} are both super cool in theory, we have {{ site.data.spell.earthbind_totem }} baseline already providing slows making them obselete

<hr>

# Raid Class Tree

Most of the time, the class tree in Raid will have this base.

<div class="iframe-holder">
  <iframe src="https://mimiron.raidbots.com/simbot/render/talents/CYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIEAAWmmZGmtFzMTjZMzshlZYwYYWGDAgB?width=650&level=80" frameborder="0" width="530px" height="100%"></iframe>
</div>


#### Points that are easily droppable
- {{ site.data.spell.mana_spring }}
- {{ site.data.spell.hst }} and {{ site.data.spell.elemental_resistance }}
  - You can path through {{ site.data.spell.cleanse_spirit }} to get {{ site.data.spell.elemental_warding }}
- {{ site.data.spell.refreshing_waters }}
- {{ site.data.spell.spirit_wolf }}

#### Logical points
- If you have {{ site.data.spell.wind_shear }}, you should always get {{site.data.spell.seasoned_winds }} with it. You can remove {{ site.data.spell.totemic_surge }} in that case.
- If you have {{ site.data.spell.thunderstorm }} and its follow-up node, you can drop {{ site.data.spell.totemic_projection }} and {{ site.data.spell.totemic_focus }}
- If you have {{ site.data.spell.pct }}, you can drop {{ site.data.spell.totemic_projection }}

<hr>

# Mythic + Class Tree

Most of the time, the class tree in Mythic+ will have this base.

<div class="iframe-holder">
  <iframe src="https://mimiron.raidbots.com/simbot/render/talents/CYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIEAAz20MYstwMTYmZmlhlZMDmlBLzMAAG?width=650&level=80" frameborder="0" width="530px" height="100%"></iframe>
</div>

#### Points that are easily droppable
- {{ site.data.spell.winds_of_alakir }}
- {{ site.data.spell.wind_rush_totem }} and {{ site.data.spell.ascending_air }}
- {{ site.data.spell.lightning_lasso }}, this spell is not used as a damaging spell, only a CC.
- {{ site.data.spell.thunderous_paws }}
- {{ site.data.spell.elemental_orbit }} and {{ site.data.spell.earth_shield }}



