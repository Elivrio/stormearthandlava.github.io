---
layout: page
title: Builds
last_update: 02/05/2023
game_version: 10.1.0 Dragonflight
toc: true
big_article: true
---

# Welcome, read First

This page aims to display and discuss the recommended and most widely-used Builds available to Elemental.

This is not an exhaustive list of all options and does not imply that any build **not** shown here is automatically terrible/unplayable.  

In practical terms we cannot account for every build variation and effort has been largely focused on the highest performing / most popular builds. If you find something that you feel works or performs better than what is listed here feel free to contact the team on [Storm, Earth & Lava Discord](https://discord.gg/y5dUf3PWrU) or [Earthshrine #Elemental Channel](https://discord.gg/earthshrine)

<hr>

# Raid

<p align="center" style="color:red">Click on a build banner to expand it.</p>

<div class="accordion dungeon-accordion" id="accordion-psurge">
<div class="card">
<div class="card-header" id="pswlr">
<div data-toggle="collapse" data-target="#pswlr-collapse" aria-expanded="false" aria-controls="pswlr-collapse" class="builds-header pswlr"><h2>Icyhot 2.0</h2></div>
</div>
<div id="pswlr-collapse" class="collapse" aria-labelledby="pswlr" data-parent="#accordion-psurge">
<div class="card-body" markdown="1">

## Overview

It works similarly to the Primordial Surge Build from Dragonflight. You always want to keep your {{ site.data.spell.lvb }} charges rolling while spending your maelstrom and {{ site.data.spell.if }} charges.

Keeping {{ site.data.spell.fs }} on up to 6 targets is also a priority as it will give you a lot value from {{ site.data.spell.sfd }}, {{ site.data.spell.lvs }}, {{ site.data.spell.sf }} and {{ site.data.spell.magma_chamber }}. Try to get as much value as possible from {{ site.data.spell.splintered }} as well.

<div class="iframe-holder">
  <iframe src="https://www.raidbots.com/simbot/render/talents/CYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAMLz2yYwYmZZbmZmZmxYAAAAAAAAAAhAAw20MzgtFmZCjZmlhlZMDGjlZZmZmBMjxA?width=620&level=80" frameborder="0" width="530px" height="100%"></iframe>
</div>

<hr>

## Stats
The best way to know what's the best piece for you will always be to sim yourself. I know it's a meme at this point, but it's the just the truth.

Check out [Raidbots' Top Gear](https://www.raidbots.com/simbot/topgear) to see what the best option is for you out of what's available in your bag. If you need specific information on how Elemental sims, you can check [this guide]({{ site.baseurl }}{% link blog/_posts/2023-01-02-simming.md %}).

The stat priority goes like this: ```Int >>> Haste > Vers > Crit > Mastery```. Again, remember that your sims will take priority over this in your gearing process.

Generally, Haste will make the rotation easier to execute and further improve your ability to adapt to movement so it will always be a solid stat to go for.

Similarly, versatility will give flat Damage Reduction, increasing your chances to live at all time. A dead DPS doesn't do damage, so some DR is always valuable.

<hr>

## Key Notes

The build is really simple if you've played Elemental Shaman before. You want to keep your {{ site.data.spell.lvb }} charges rolling. You want to use {{ site.data.spell.eb }} to dump maelstrom. You want to use {{ site.data.spell.if }} because of its high value. You want to maximise your {{ site.data.spell.mote }} usage.

With {{ site.data.spell.if }}, buffed {{ site.data.spell.frs }} and {{ site.data.spell.lvb }}, you can often move during your rotation. Try to take advantage of those instant casts to move where you went to be next.

{{ site.data.spell.eq }} replaces {{ site.data.spell.eb }} at 4 or more targets.

{{ site.data.spell.dre }} procs do not impact rotation priority and should be read the same regardless. In practice this means 'filler' spells like {{ site.data.spell.if }} and buffed {{ site.data.spell.frs }} are eliminated when {{ site.data.spell.dre }} procs happen *unless you have to move* because {{ site.data.spell.lvb }} will always be available during them. You will also continue to spend maelstrom on {{ site.data.spell.eb }} as usual.

If talented, use {{ site.data.spell.lmt }} on CD if no adds are going to spawn soon.

<hr>
## Opener
The <span style="color:red">red arrow</span> indicates the time the boss is pulled. Please note that openers are a minor and nit-picky increase (or sometimes decrease!), and adapting to the fight is much more important.

~2.8 seconds from pull
<div class="opener">
    <div class="skill fe"><span>FE</span></div>
    <div class="arrow"></div>
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow pull"></div>
    <div class="skill pw"><span>PW</span></div>
    <div class="arrow"></div>
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow"></div>
    <div class="skill asc"><span>ASC</span></div>
</div>

During {{ site.data.spell.asc }}, make sure to spend your maelstrom before overcapping then continue with the normal rotation.

<hr>

## Rotation / Priority List

### 1 Target
1. {{ site.data.spell.fe }} if it is available. If you're talented into {{ site.data.spell.echo_of_the_elementals }}, make sure to wait until your current elemental expires (or to dismiss it). The previous Elemental needs to die or you won't get the lesser One.
1. Maintain {{ site.data.spell.fs }} on your target at all times, don't forget {{ site.data.spell.pw }} applies one!
1. {{ site.data.spell.pw }} on cooldown, try to line up its use with {{ site.data.spell.asc }}.
1. {{ site.data.spell.asc }} on cooldown.
1. {{ site.data.spell.eb }} when you have more than 90 maelstrom, preferably with {{ site.data.spell.mote }} buff active.
1. {{ site.data.spell.lvb }}.
1. {{ site.data.spell.if }} and make sure you consume {{ site.data.spell.fusion_of_elements }} before casting it again.
1. {{ site.data.spell.frs }} with {{ site.data.spell.if }} and {{ site.data.spell.mote }}.
1. {{ site.data.spell.lb }} as your single target filler.

<br>
### 2 Targets
If you find yourself using this build on 2 or more targets it is less than ideal.
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. Maintain {{ site.data.spell.fs }} on both targets at all times, don't forget {{ site.data.spell.pw }} applies one!
 1. {{ site.data.spell.pw }} if it is available
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.eb }} if you have {{ site.data.spell.lvb }} on at least one charge, preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.cl }}

<br>
### 3 Targets
If you find yourself using this build on 3 or more targets it is less than ideal
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. Maintain {{ site.data.spell.fs }} on all targets at all times, don't forget {{ site.data.spell.pw }} applies one!
 1. {{ site.data.spell.pw }} if it is available
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.eb }} if you have {{ site.data.spell.lvb }} on at least one charge, preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.cl }}

<br>
### 4 Targets
If you find yourself using this build on 4 or more targets it is less than ideal
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. Maintain {{ site.data.spell.fs }} on all targets at all times, don't forget {{ site.data.spell.pw }} applies one!
 1. {{ site.data.spell.pw }} if it is available
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.eq }} preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.cl }}

<br>
### 5+ Targets
If you find yourself using this build on 5 or more targets it is less than ideal
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. Maintain {{ site.data.spell.fs }} on all targets at all times, don't forget {{ site.data.spell.pw }} applies one!
 1. {{ site.data.spell.pw }} if it is available
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.eq }} preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.cl }}

</div>
</div>
</div>
<div class="card">
<div class="card-header" id="liwlr">
<div data-toggle="collapse" data-target="#liwlr-collapse" aria-expanded="false" aria-controls="liwlr-collapse" class="builds-header liwlr"><h2>Flashing Lightning</h2></div>
</div>
<div id="liwlr-collapse" class="collapse" aria-labelledby="liwlr" data-parent="#accordion-psurge">
<div class="card-body" markdown="1">

## Overview

It works similarly to the Primordial Surge Build from Dragonflight. You always want to keep your {{ site.data.spell.lvb }} charges rolling while spending your maelstrom and {{ site.data.spell.if }} charges.

Keeping {{ site.data.spell.fs }} on up to 6 targets is also a priority as it will give you a lot value from {{ site.data.spell.sfd }}, {{ site.data.spell.lvs }}, {{ site.data.spell.sf }} and {{ site.data.spell.magma_chamber }}. Try to get as much value as possible from {{ site.data.spell.splintered }} as well.

<div class="iframe-holder">
  <iframe src="https://www.raidbots.com/simbot/render/talents/CYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAMbzyyMjZGmZjxMDmZGAAAAAAAAAQIAAmtpZAbLMmgZmZZYZmZGMLjlZZmZmZGDzwA?width=620&level=80" frameborder="0" width="530px" height="100%"></iframe>
</div>

<hr>

## Stats
The best way to know what's the best piece for you will always be to sim yourself. I know it's a meme at this point, but it's the just the truth.

Check out [Raidbots' Top Gear](https://www.raidbots.com/simbot/topgear) to see what the best option is for you out of what's available in your bag. If you need specific information on how Elemental sims, you can check [this guide]({{ site.baseurl }}{% link blog/_posts/2023-01-02-simming.md %}).

The stat priority goes like this: ```Int >>> Haste > Vers > Crit > Mastery```. Again, remember that your sims will take priority over this in your gearing process.

Generally, Haste will make the rotation easier to execute and further improve your ability to adapt to movement so it will always be a solid stat to go for.

Similarly, versatility will give flat Damage Reduction, increasing your chances to live at all time. A dead DPS doesn't do damage, so some DR is always valuable.

<hr>

## Key Notes

This build is one of the easiest to play in the history of WoW. Basically, you spam {{ site.data.spell.lb }} to get more usages of {{ site.data.spell.pw }}, {{ site.data.spell.ancestral_swiftness }}, {{ site.data.spell.sk }} and {{ site.data.spell.se }} thanks to {{ site.data.spell.fol }}.

Spamming {{ site.data.spell.lb }} becomes very fast with high {{ site.data.spell.wind_gust }} stacks and makes {{ site.data.spell.cota }} cast even more while they are up.

You still do not want to overcap maelstrom. {{ site.data.spell.es }} does a lot of damage and most importantly provides both {{ site.data.spell.lr }} and {{ site.data.spell.sop }}.

You do not want to cast {{ site.data.spell.lvb }} ever outside of the opener or to proc {{ site.data.spell.splintered_elements }}. Nothing. Else. However, when you do cast {{ site.data.spell.lvb }}, you want to take advantage of {{ site.data.spell.mote }} with {{ site.data.spell.es }}.

If talented, use {{ site.data.spell.lmt }} alongside {{ site.data.spell.pw }} to get more value from {{ site.data.spell.splintered_elements }}.

The thing that will make you gain a lot of damage is your maelstrom management. You want to pool at least 110 maelstrom when {{ site.data.spell.sk }} is close to being available, to easily buff both {{ site.data.spell.lb }} with {{ site.data.spell.sop }}.

{{ site.data.spell.eq }} replaces {{ site.data.spell.es }} at 2 or more targets. {{ site.data.spell.cl }} replaces {{ site.data.spell.lb }} at 2 or more targets except on 2 targets with {{ site.data.spell.sop }}.

<hr>
## Opener
The <span style="color:red">red arrow</span> indicates the time the boss is pulled. Please note that openers are a minor and nit-picky increase (or sometimes decrease!), and adapting to the fight is much more important.

~2.8 seconds from pull
<div class="opener">
    <div class="skill se"><span>SE</span></div>
    <div class="arrow"></div>
    <div class="skill sk"><span>SK</span></div>
    <div class="arrow"></div>
    <div class="skill pw"><span>PW</span></div>
    <div class="arrow pull"></div>
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow"></div>
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow"></div>
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow"></div>
    <div class="skill lb"><span>LB</span></div>
    <div class="arrow"></div>
    <div class="skill es"><span>ES</span></div>
    <div class="arrow"></div>
    <div class="skill lb"><span>LB</span></div>
</div>

The goal of this opener is to use {{ site.data.spell.lvb }} to generate enough maelstrom to cast {{ site.data.spell.es }} and get {{ site.data.spell.sop }} for {{ site.data.spell.lb }} with {{ site.data.spell.sk }}.

The problem with this opener is that the {{ site.data.spell.es }} is not guaranteed. You need to get an additional 4 maelstrom from overloads to be able to execute it. Which means there's some variance to it. Still, it allows you to fish for {{ site.data.spell.potm }} and still guarantee some value off of {{ site.data.spell.mote }}.

Note that {{ site.data.spell.se }} is indeed cast before {{ site.data.spell.sk }} in the opener because of {{ site.data.spell.fury_of_the_storms }}. The Lightning Elemental from {{ site.data.spell.fury_of_the_storms }} does more DPS than {{ site.data.spell.se }} and that makes {{ site.data.spell.sk }} more valuable if you cast it second.

<hr>

## Rotation / Priority List

### 1 Target
1. {{ site.data.spell.se }} on cooldown.
1. {{ site.data.spell.ancestral_swiftness }} on cooldown.
1. {{ site.data.spell.pw }} on cooldown.
1. Maintain {{ site.data.spell.fs }} on your target at all times, don't forget {{ site.data.spell.pw }} applies one!
1. {{ site.data.spell.sk }} on cooldown
1. {{ site.data.spell.lb }} with {{ site.data.spell.sop }}.
1. {{ site.data.spell.es }} with {{ site.data.spell.mote }}.
1. With 45 maelstrom and {{ site.data.spell.pw}}, use {{ site.data.spell.lvb }}.
1. {{ site.data.spell.es }} if you are close to capping maelstrom or to gain {{ site.data.spell.sop }}.
1. {{ site.data.spell.lb }}.

### 2 Targets
1. {{ site.data.spell.se }} on cooldown.
1. {{ site.data.spell.ancestral_swiftness }} on cooldown.
1. {{ site.data.spell.pw }} on cooldown.
1. {{ site.data.spell.sk }} on cooldown
1. {{ site.data.spell.lb }} with {{ site.data.spell.sop }}.
1. {{ site.data.spell.eq }} with {{ site.data.spell.mote }}.
1. With 45 maelstrom and {{ site.data.spell.pw}}, use {{ site.data.spell.lvb }}.
1. {{ site.data.spell.eq }} if you are close to capping maelstrom or to gain {{ site.data.spell.sop }}.
1. {{ site.data.spell.cl }}.

### 3-5 Targets
1. {{ site.data.spell.se }} on cooldown.
1. {{ site.data.spell.ancestral_swiftness }} on cooldown.
1. {{ site.data.spell.pw }} on cooldown.
1. {{ site.data.spell.sk }} on cooldown
1. {{ site.data.spell.eq }} with {{ site.data.spell.mote }}.
1. With 45 maelstrom and {{ site.data.spell.pw}}, use {{ site.data.spell.lvb }}.
1. {{ site.data.spell.eq }} if you are close to capping maelstrom or to gain {{ site.data.spell.sop }}.
1. {{ site.data.spell.cl }}.

### 6+ Targets
1. {{ site.data.spell.se }} on cooldown.
1. {{ site.data.spell.ancestral_swiftness }} on cooldown.
1. {{ site.data.spell.pw }} on cooldown.
1. {{ site.data.spell.sk }} on cooldown
1. {{ site.data.spell.cl }} with {{ site.data.spell.sop }}.
1. {{ site.data.spell.eq }} with {{ site.data.spell.mote }}.
1. With 45 maelstrom and {{ site.data.spell.pw}}, use {{ site.data.spell.lvb }}.
1. {{ site.data.spell.eq }} if you are close to capping maelstrom or to gain {{ site.data.spell.sop }}.
1. {{ site.data.spell.cl }}.

</div>
</div>
</div>
</div>

<hr>

# Cleave/Priority Damage

Predominately aimed at M+ content these build variants focus on the power of {{ site.data.spell.fs }} and its supporting talents to deal AoE damage, all variants include {{ site.data.spell.dre }} by default as the build spends a lot of its time using the {{ site.data.spell.lvs }} procs it generates so it provides a lot of value on average but is not the focus of the build - if desired you can swap this point to a more consistent option.

<p align="center" style="color:red">Click on a build banner to expand it.</p>

<div class="accordion dungeon-accordion" id="accordion-wildfire">
<div class="card">
<div class="card-header" id="wfaoe">
<div data-toggle="collapse" data-target="#wfaoe-collapse" aria-expanded="false" aria-controls="wfaoe-collapse" class="builds-header wfaoe"><h2>Wildfire "Full" AoE</h2></div>
</div>
<div id="wfaoe-collapse" class="collapse" aria-labelledby="wfaoe" data-parent="#accordion-wildfire">
<div class="card-body" markdown="1">

## What does this build do?

We heard you like {{ site.data.spell.fs }} and {{ site.data.spell.lvs }} so this build is entirely committed to the idea of maintaining {{ site.data.spell.fs }} on multiple targets and utilizing all the benefits associated with consuming {{ site.data.spell.lvs }}.

Staples of wildfire as a M+ include {{ site.data.spell.sfd }}, {{ site.data.spell.splinter }}, {{ site.data.spell.sk }}. There are more swaps you could make within this archetype like {{ site.data.spell.sop }} swapped for {{ site.data.spell.afs }} which significantly simplifies your perceived gameplay, but in reality is weaker in most ways so all the variants below use {{ site.data.spell.sop }}.

## What does it look like?

There are multiple possible variants of this build that do not include rotational priority changes, these will all play similarly and you can choose between them based on personal preference and/or sim results. The 4 builds linked below are, at least in my opinion, the 'standard' setups with one taking {{ site.data.spell.imp_ftw }} with {{ site.data.spell.potm }}, another opting to go for {{ site.data.spell.flow_of_power }} and {{ site.data.spell.swelling_maelstrom }}, another one playing {{ site.data.spell.searing_flames }} instead of {{ site.data.spell.echo_chamber }} and the last one simply taking {{ site.data.spell.if }} and {{ site.data.spell.electrified_shocks }}.

### Standard build without Elemental Blast
The standard build for a non-{{ site.data.spell.eb }} build.
<div class="iframe-holder">
<iframe src="https://www.raidbots.com/simbot/render/talents/BYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAg0SrIJtkACSjS0SLJOQOAAAAAAgSASJJKpJg0SSaKhgQEgA?width=530&level=70" frameborder="0" width="530px" height="100%"></iframe>
  </div>

### Swelling Maelstrom Variant
{{ site.data.spell.swelling_maelstrom }} will give you more room to effectively use your {{ site.data.spell.sop }} and pool Maelstrom.
<div class="iframe-holder">
<iframe src="https://www.raidbots.com/simbot/render/talents/BYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAg0Sr0SSLJgQSjS0STCRAAAAAAKBIlkokmASLJppECCRAC?width=530&level=70" frameborder="0" width="530px" height="100%"></iframe>
  </div>

### Searing Flames Variant
For better overall Maelstrom generation.
<div class="iframe-holder">
<iframe src="https://www.raidbots.com/simbot/render/talents/BYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAg0SrIJtkACSjSOQLtkQOAAAAAAgSASJJKpJg0SSaKhgQEgA?width=530&level=70" frameborder="0" width="530px" height="100%"></iframe>
  </div>

### Icefury Variant
{{ site.data.spell.if }} gives use some cleave in low target count and flows nicely for Maelstrom generation.
<div class="iframe-holder">
<iframe src="https://www.raidbots.com/simbot/render/talents/BYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAg0SrIJtkASLSjS0STiDEAAAAAAKBIlkokmASLJppECCRAC?width=530&level=70" frameborder="0" width="530px" height="100%"></iframe>
</div>

<hr>

## Stats

### Always remember to sim your current options appropriately
 - [Raidbots](https://www.raidbots.com/simbot/topgear)
 - For more information [How Does Elemental Sim?]({{ site.baseurl }}{% link blog/_posts/2023-01-02-simming.md %})  

### Simplified
This is quick and dirty, your sims will take priority in your gearing process.
 - Haste / Crit > Mastery / Vers
 - Remember that generally Haste will make the rotation easier to execute and further improve your ability to adapt to movement so will always be a solid stat to go for, and more flexible than Mastery given Haste is also very good in all AoE-focused builds

 <hr>

## Rotation

### Key Notes
 - If targets will survive for a while you will want {{ site.data.spell.fs }} ticking on them, don't forget to monitor this particularly on higher keys where you can get real value!
 - {{ site.data.spell.lmt }}’s periodic damage scales dynamically with haste, therefore it can be used to setup a pull by applying {{ site.data.spell.fs }} before gaining the {{ site.data.spell.splinter }} haste buff without losing out on too much potential damage. You should still aim to use {{ site.data.spell.lmt }} while having the {{ site.data.spell.splinter }} haste buff or {{ site.data.spell.bl }} if possible, but don't lose setup time for it.
 - {{ site.data.spell.sop }} is there to amplify what you're already aiming to do at different target counts which can be quite handy
    * 1-2 Targets = {{ site.data.spell.lb }}
    * 3-5 Targets = {{ site.data.spell.fs }} if and only if you need to spread {{ site.data.spell.fs }}, otherwise ignore and waste {{ site.data.spell.sop }} buffs.
    * 6+ Targets = {{ site.data.spell.cl }} whenever possible, if you have to move then using a buff on {{ site.data.spell.fs }} is fine too
    * {{ site.data.spell.sop }} will also make you want to delay casting {{ site.data.spell.sk }} on 1-2 targets or 6+ targets in order to benefit from their combined effects.
 - {{ site.data.spell.dre }} procs do not really change the priority of what you're doing, they mainly act to provide value from not having to manually refresh your current {{ site.data.spell.fs }} dots and that translates into more {{ site.data.spell.cl }} casts which leads to more {{ site.data.spell.eq }} casts. Note: {{ site.data.spell.lvbm }} replaces {{ site.data.spell.cl }} in the priority when {{ site.data.spell.dre }} procs are active but you should ensure you have enough time to finish the cast inside the {{ site.data.spell.dre }} buff otherwise the cast will cancel.
 - It can be tempting to try and use every {{ site.data.spell.lvs }} proc during mass AoE but generally you're going to use them when you have to move when AoEing or when you'd have enough maelstrom to {{ site.data.spell.eq }} afterwards which benefits from {{ site.data.spell.mote }}. This strikes a better balance between fishing for {{ site.data.spell.dre }} procs and reliably good AoE damage. Feel free to prioritize {{ site.data.spell.lvs }} more if a priority target is up and needs to die fast!

### Opener
Follow the cast sequence below for your opener. A <span style="color:red">red arrow</span> indicates the time the boss is pulled. Please note that openers are a *very* minor and nit-picky increase (or sometimes decrease!), and adapting to the fight is much more important.

~3.5 seconds from boss pull
<div class="opener">
    <div class="skill fe"><span>FE</span></div>
    <div class="arrow"></div>
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow pull"></div>
    <div class="skill fs"><span>FS</span></div>
    <div class="arrow"></div>
    <div class="skill pw"><span>PW</span></div>
    <div class="arrow"></div>...
</div>

AoE openers are less rigid than boss openers. Keep in mind that these will change simply based by what cooldowns you have available on a pull-by-pull basis and you should aim to maximize the value from what is available at that time. Here are some general rules:
   - Pool maelstrom at the end of a current pull to have resources available at the start of the next pull, this dramatically improves the consistent performance from pull-to-pull and eases the feeling of 'ramp' time in the rotation.
   - Though spreading {{ site.data.spell.fs }} to multiple targets is good, it should not be viewed as a requirement to reach 6 before doing damage in all cases. In cases where you have {{ site.data.spell.lmt }} and {{ site.data.spell.totemic_recall }} available, this is quite achievable, in cases where you don't you should be prepared to trigger {{ site.data.spell.splinter }}'s effect with 4-5 targets. If you have maelstrom left from a previous pack (and you should!) this process becomes more fluid and you can spread {{ site.data.spell.fs }} whilst the tank is gathering mobs.
   - On pulls that include 6+ targets it is ideal to have {{ site.data.spell.sop }} active for both charges of {{ site.data.spell.sk }} and given the maelstrom generated you can cast {{ site.data.spell.eq }} twice between them, this means that if you do not have maelstrom from a previous pack you may need to hold {{ site.data.spell.sk }} until slightly later in the pull or simply forego this value in favor of using {{ site.data.spell.sk }} without {{ site.data.spell.sop }}.
   - Avoid placing {{ site.data.spell.lmt }} prematurely, if the tank does not have sufficient aggro then its possible for it to be killed directly by mobs which greatly reduces its value

### 1 Target Priority
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. {{ site.data.spell.sk }} if you have at least 83 maelstrom (without {{ site.data.spell.potm }} or 80 with {{ site.data.spell.potm }}). This ensures you can buff both charges.
 1. {{ site.data.spell.lb }} if both {{ site.data.spell.sk }} and {{ site.data.spell.sop }} buffs are active
 1. {{ site.data.spell.pw }} if it is available and no additional targets will be available soon
 1. {{ site.data.spell.lb }} if {{ site.data.spell.sop }} buff is active
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.frs }} if {{ site.data.spell.icefury }} buff is active and {{ site.data.spell.e_shocks }} debuff is not
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.dre }} proc is active. Note: if you have to move you will still cast {{ site.data.spell.es }} as below, and continue to follow the priorities above!
 1. {{ site.data.spell.es }} preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.if }}
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.lb }}
 1. Refresh {{ site.data.spell.fs }} or cast {{ site.data.spell.frs }} when moving

  Note: You do not play around {{ site.data.spell.potm }} procs in single target.

### 2 Targets Priority
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. Maintain {{ site.data.spell.fs }} on both targets at all times, don't forget {{ site.data.spell.pw }} applies one!
 1. {{ site.data.spell.sk }} if you have at least 83 maelstrom (without {{ site.data.spell.potm }} or 80 with {{ site.data.spell.potm }}. This ensures you can buff both charges.
 1. {{ site.data.spell.lb }} if both {{ site.data.spell.sk }} and {{ site.data.spell.sop }} buffs are active
 1. {{ site.data.spell.pw }} if it is available and no additional targets will be available soon
 1. {{ site.data.spell.lb }} if {{ site.data.spell.sop }} buff is active
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.eq }} preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.frs }} if {{ site.data.spell.icefury }} buff is active and {{ site.data.spell.e_shocks }} debuff is not
 1. {{ site.data.spell.cl }} if {{ site.data.spell.potm }} buff is active
 1. {{ site.data.spell.if }}
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.cl }}

### 3-5 Targets Priority
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. Maintain {{ site.data.spell.fs }} on all targets at all times, don't forget {{ site.data.spell.pw }} applies one!
 1. {{ site.data.spell.sk }} if it is available and there is no reason to hold its use
 1. {{ site.data.spell.cl }} if {{ site.data.spell.sk }} buff is active, preferably with {{ site.data.spell.mote }} buff active!
 1. {{ site.data.spell.pw }} if it is available
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.eq }} preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.cl }} if {{ site.data.spell.potm }} and {{ site.data.spell.mote }} buffs are active
 1. {{ site.data.spell.lvbm }} if {{ site.data.spell.mote }} buff is active and you will finish the cast
 1. {{ site.data.spell.frs }} if {{ site.data.spell.icefury }} buff is active and {{ site.data.spell.e_shocks }} debuff is not (Note: do not do this against 5 or more targets unless moving)
 1. {{ site.data.spell.if }} (Note: do not do this against 5 or more targets unless moving soon)
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.mote }} buff is not active
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.cl }}

### 6+ Targets Priority
 1. {{ site.data.spell.fe }} if it is available and there is no reason to hold its use.
 1. Maintain {{ site.data.spell.fs }} on all targets at all times, don't forget {{ site.data.spell.pw }} applies one!
 1. {{ site.data.spell.sk }} if it is available and you have at least enough maelstrom to cast {{ site.data.spell.eq }} after to {{ site.data.spell.sop }} buff the charges!
 1. {{ site.data.spell.cl }} or {{ site.data.spell.lvbm }} when {{ site.data.spell.sk }} buff is active, preferably with {{ site.data.spell.sop }} buff
 1. {{ site.data.spell.cl }} or {{ site.data.spell.lvbm }} if {{ site.data.spell.sop }} buff is active
 1. {{ site.data.spell.pw }} if it is available
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.lvs }} buff is active
 1. {{ site.data.spell.eq }} preferably with {{ site.data.spell.mote }} buff active
 1. {{ site.data.spell.cl }} if {{ site.data.spell.potm }} and {{ site.data.spell.mote }} buffs are active
 1. {{ site.data.spell.lvbm }} if {{ site.data.spell.mote }} buff is active and you will finish the cast
 1. {{ site.data.spell.lvb }} if {{ site.data.spell.mote }} buff is not active
 1. {{ site.data.spell.lvb }}
 1. {{ site.data.spell.cl }}

</div>
</div>
</div>
</div>

<hr>

# Mythic +

Exactly what it says on the tin, for the friends with a penchant for Lightning! Lightning offers a great way to cater to multiple damage profiles, rarely sacrificing single target for AoE. It also plays differently to the fire builds, placing much more emphasis on {{ site.data.spell.cl }} to generate quickly at high target counts.

<p align="center" style="color:red">Click on a build banner to expand it.</p>

<div class="accordion dungeon-accordion" id="accordion-lightning">
<div class="card">
<div class="card-header" id="liwlr">
<div data-toggle="collapse" data-target="#liwlr-collapse" aria-expanded="false" aria-controls="liwlr-collapse" class="builds-header liwlr"><h2>Lightning ST with Windspeakers</h2></div>
</div>
<div id="liwlr-collapse" class="collapse" aria-labelledby="liwlr" data-parent="#accordion-lightning">
<div class="card-body" markdown="1">

## What does this build do?

This build is a Single Target one that focuses on the power of {{ site.data.spell.lb }} and {{ site.data.spell.eb }}. It seeks to empower its core spells with supporting talents like {{ site.data.spell.e_shocks }}, {{ site.data.spell.se }}, {{ site.data.spell.sop }} and {{ site.data.spell.lr }}, but also use {{ site.data.spell.lvb }} as an enabler with {{ site.data.spell.wlr }}, {{ site.data.spell.mote }} and {{ site.data.spell.potm }}.

This build rotation is fairly strict, playing around the {{ site.data.spell.e_shocks }} debuff in mostly the same way each time.

## What does it look like?
### "Standard" Build
<div class="iframe-holder">
  <iframe src="https://www.raidbots.com/simbot/render/talents/BYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAoVSSLJUSSLRDRJQiEAAAAAgSCIlkgmkCSLJpFIIkAI?width=530&level=70" frameborder="0" width="530px" height="100%"></iframe>
</div>

### FoL Variant
- This variant drops {{ site.data.spell.eb }}, taking {{ site.data.spell.fol }} instead. The focus of the build being Single Target, having a higher density of {{ site.data.spell.sop }} due to {{ site.data.spell.es }} cost being lower can somewhat compete with the raw damage of {{ site.data.spell.eb }}.
- {{ site.data.spell.fol }} will have good defensive value, allowing you to cast {{ site.data.spell.as }} more often (see [this blogpost for a list of spells affected by {{ site.data.spell.fol }}]({{ site.baseurl }}{%link blog/_posts/2023-01-23-fol.md %})).
- If you decide to play this variant, simply change {{ site.data.spell.eb }} to {{ site.data.spell.es }} in the rest of this guide.

<div class="iframe-holder">
<iframe src="https://www.raidbots.com/simbot/render/talents/BYQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAoVSSLJRJSLRDRJQiEAAAAAgSCIlkgmkCSLJpFIIkAI?width=530&level=70" frameborder="0" width="530px" height="100%"></iframe>
</div>

<hr>

## Stats

### Always remember to sim your current options appropriately
 - [Raidbots](https://www.raidbots.com/simbot/topgear)
 - For more information [How Does Elemental Sim?]({{ site.baseurl }}{% link blog/_posts/2023-01-02-simming.md %})  

### Simplified
This is quick and dirty, your sims will take priority in your gearing process.
 - Haste / Crit > Mastery / Vers
 - Remember that generally Haste will make the rotation easier to execute and further improve your ability to adapt to movement so will always be a solid stat to go for, and more flexible than Mastery given Haste is also very good in all AoE-focused builds
- Having some amount of Vers is never bad as it will increase your passive survivability.

<hr>

## Rotation

### Key Notes
- You want to maximize the uptime of {{ site.data.spell.e_shocks }} on your target and use {{ site.data.spell.lvb }}, {{ site.data.spell.eb }} and {{ site.data.spell.lb }} in that order as much as possible during {{ site.data.spell.e_shocks }}.
- {{ site.data.spell.lvs }} gained from {{ site.data.spell.wlr }} should be held to empower your next spender (which can be in 5 to 8 seconds).
- If you are in combat with 2, 3 or more targets for an extended period of time, consider using the Lightning WLR with EoGS build just below as it's much better in cleave situations.
- Once you hit 3 targets, any sort of gaming the {{ site.data.spell.mote }} buff becomes extremely bad. In practice, this also makes the points spent in {{ site.data.spell.potm }} near worthless however they are also needed for {{ site.data.spell.echo_chamber }} and {{ site.data.spell.mwf }}.
- {{ site.data.spell.lr }} applies to your current target when it does not have an active buff. {{ site.data.spell.eq }} has *some* 'smart' applications to apply to off-targets but results can vary. It is suggested *when you are comfortable enough to do so* to incorporate target swapping after each spender to increase the value gained from {{ site.data.spell.lr }}. If done poorly (i.e. too early in the learning process) this can produce negative results, master the basics then add complexity!
- {{ site.data.spell.sop }} is there to amplify what you're already aiming to do at different target counts which can be quite handy:
  * 1-2 Targets = {{ site.data.spell.lb }}
  * 3-5 Targets = {{ site.data.spell.fs }} if and only if you need to move and {{ site.data.spell.sop }} buff happens to be up and no {{ site.data.spell.if }} buffs remain
  * 6+ Targets = {{ site.data.spell.cl }} whenever possible
  * {{ site.data.spell.sop }} will also make you want to delay casting {{ site.data.spell.sk }} on 1-2 targets or 6+ targets in order to benefit from their combined effects.

### Opener
Follow the cast sequence below for your opener. A <span style="color:red">red arrow</span> indicates the time the boss is pulled. Please note that openers are a *very* minor and nit-picky increase (or sometimes decrease!), and adapting to the fight is much more important.

~3.5 seconds from boss pull
<div class="opener">
    <div class="skill se"><span>SE</span></div>
    <div class="arrow"></div>
    <div class="skill if"><span>IF</span></div>
    <div class="arrow pull"></div>
    <div class="skill fs"><span>FS</span></div>
    <div class="arrow"></div>
    <div class="skill frs"><span>FrS</span></div>
    <div class="arrow"></div>
    <div class="text">Use {{ site.data.spell.lb }} up to 76 maelstrom and do a {{ site.data.spell.e_shocks }} with {{ site.data.spell.sk }} window (see below)</div>
</div>

<br>

### Spender Window

This cast-sequence will be your main way of dealing damage. You want:
- at least 63 maelstrom at the start to be able to cast {{ site.data.spell.eb }}.
- {{ site.data.spell.fs }} and {{ site.data.spell.e_shocks }} to both be active on your target for the next 5 seconds. Those 5 seconds ensure that all the overloads you generate will hit the target while {{ site.data.spell.e_shocks }} is active.

<div class="opener">
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow"></div>
    <div class="skill eb"><span>EB</span></div>
    <div class="arrow"></div>
    <div class="skill lb"><span>LB</span></div>
</div>

The idea is simple:
- Have {{ site.data.spell.e_shocks }} applied to the enemy.
- Use {{ site.data.spell.lvb }} (if possible with {{ site.data.spell.lvs }} from {{ site.data.spell.wlr }}) to gain {{ site.data.spell.mote }}.
- Use {{ site.data.spell.eb }} to gain {{ site.data.spell.sop }}
- Use {{ site.data.spell.lb }} to maximize the damage gain from {{ site.data.spell.sop }}, {{ site.data.spell.lr }} and {{ site.data.spell.e_shocks }} while generating Maelstrom to execute the window again.
- You want to use your CD and various enablers outside of this window.

<br>

### Stormkeeper Window

You want these pre-requisite before doing this cast-sequence:
- {{ site.data.spell.sk }} active
- {{ site.data.spell.fs }} will be active for the next 10 seconds.
- {{ site.data.spell.e_shocks }} to be active on your target for the next 5 seconds. Those 5 seconds ensure that all the overloads you generate will hit the target while {{ site.data.spell.e_shocks }} is active.
- You have at least 90 Maelstrom.
- if {{ site.data.spell.e_shocks }} is active and has more than 5 seconds remaining, you have {{ site.data.spell.if }} active with at least 1 charges and at least 5 seconds remaining.

*Note: You can refresh {{ site.data.spell.fs }} after the first {{ site.data.spell.lb }} if needed, but be careful not to let your other buffs expire.*

<div class="opener">
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow"></div>
    <div class="skill eb"><span>EB</span></div>
    <div class="arrow"></div>
    <div class="skill lb"><span>LB</span></div>
    <div class="arrow"></div>
    <div class="skill frs"><span>FrS</span></div>
    <div class="arrow"></div>
    <div class="skill lvb"><span>LvB</span></div>
    <div class="arrow"></div>
    <div class="skill eb"><span>EB</span></div>
    <div class="arrow"></div>
    <div class="skill lb"><span>LB</span></div>
</div>

<br>

### 1 Target Priority
1. {{ site.data.spell.se }} if it is available and there is no reason to hold its use.
1. Outside or near the end of {{ site.data.spell.e_shocks }}, refresh {{ site.data.spell.fs }} when it's faded or will in ~5 seconds.
1. {{ site.data.spell.fs }} if {{ site.data.spell.e_shocks }} debuff is not active or will fade and {{ site.data.spell.fs }} has faded or will in ~8 seconds.
1. {{ site.data.spell.sk }} if you are able to fully execute the [Stormkeeper Window](https://stormearthandlava.com/guide/general/builds.html#stormkeeper-window) described above.
1. {{ site.data.spell.lb }} if {{ site.data.spell.sop }} buff is active.
1. {{ site.data.spell.frs }} if {{ site.data.spell.if }} buff is up and either.
  * {{ site.data.spell.e_shocks }} debuff is not active or will fade before next cast.
  * {{ site.data.spell.sk }} buff is active and {{ site.data.spell.e_shocks }} has less than 5 seconds remaining.
1. {{ site.data.spell.lvb }} if you are able to fully execute the [Spender Window](https://stormearthandlava.com/guide/general/builds.html#spender-window) described above.
1. {{ site.data.spell.eb }} with {{ site.data.spell.e_shocks }} and {{ site.data.spell.mote }}.
1. {{ site.data.spell.if }}.
1. {{ site.data.spell.lb }}.

*Note: To put it simply, use {{ site.data.spell.lb }} to generate maelstrom then execute as many spender Window and {{ site.data.spell.sk }} Window as possible (see above), all the while maintaining {{ site.data.spell.fs }} and {{ site.data.spell.e_shocks }} on your target.*

### 2 Targets Priority
1. {{ site.data.spell.se }} if it is available and there is no reason to hold its use.
1. Outside or near the end of {{ site.data.spell.e_shocks }}, refresh {{ site.data.spell.fs }} on your main target when it's faded or will in ~5 seconds.
1. {{ site.data.spell.fs }} if {{ site.data.spell.e_shocks }} debuff is not active or will fade and {{ site.data.spell.fs }} has faded or will in ~8 seconds.
1. {{ site.data.spell.sk }} if you are able to fully execute the [Stormkeeper Window](https://stormearthandlava.com/guide/general/builds.html#stormkeeper-window) described above.
1. {{ site.data.spell.lb }} if {{ site.data.spell.sop }} buff is active.
1. {{ site.data.spell.frs }} if {{ site.data.spell.if }} buff is up and either:
  * {{ site.data.spell.e_shocks }} debuff is not active or will fade before next cast.
  * {{ site.data.spell.sk }} buff is active and {{ site.data.spell.e_shocks }} has less than 5 seconds remaining.
1. {{ site.data.spell.lvb }} if you are able to fully execute the [Spender Window](https://stormearthandlava.com/guide/general/builds.html#spender-window) described above.
1. {{ site.data.spell.eb }} with {{ site.data.spell.e_shocks }} and {{ site.data.spell.mote }}.
1. {{ site.data.spell.if }}.
1. {{ site.data.spell.cl }}.

*Note: If you are in combat with 2 or 3 targets for an extended period of time, consider using the Lightning WLR with EoGS build just below as it's much better in cleave situation.*


### 3 Targets Priority
1. {{ site.data.spell.se }} if it is available and there is no reason to hold its use.
1. {{ site.data.spell.sk }} if it is available and there is no reason to hold its use.
1. {{ site.data.spell.frs }} if {{ site.data.spell.if }} buff is up and {{ site.data.spell.e_shocks }} debuff is not active or will fade before next cast.
1. {{ site.data.spell.eb }} with {{ site.data.spell.e_shocks }}.
1. {{ site.data.spell.if }}.
1. {{ site.data.spell.cl }}.

*Note: If you are in combat with 2 or 3 targets for an extended period of time, consider using the Lightning WLR with EoGS build just below as it's much better in cleave situation*


## 4-5 Targets Priority
1. {{ site.data.spell.se }} if it is available and there is no reason to hold its use.
1. {{ site.data.spell.sk }} if it is available and no additional targets soon.
1. {{ site.data.spell.eq }}
1. {{ site.data.spell.cl }}

*Note: This build becomes less than ideal compared to other lightning options at 4 and more targets.*

### 6+ Targets Priority
1. {{ site.data.spell.se }} if it is available and there is no reason to hold its use.
1. {{ site.data.spell.sk }} when buffed by {{ site.data.spell.sop }} if it is available and no additional targets soon.
1. {{ site.data.spell.cl }} if {{ site.data.spell.sop }} is active
1. {{ site.data.spell.eq }}
1. {{ site.data.spell.cl }}

</div>
</div>
</div>
</div>
