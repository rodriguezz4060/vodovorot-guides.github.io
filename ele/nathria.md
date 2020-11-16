---
layout: page
title: "Castle Nathria Guide"
last_update: 2020-11-17 00:00:00
game_version: 9.0.1 Shadowlands
author: Altenna
---
# Introduction
This guide was made possible by:

- Altenna (Discord: JudgeJames#0001 \| [Twitch](https://www.twitch.tv/judgejames) \| [Twitter](https://twitter.com/_judgejames_))
- Amani (Discord: Amani#0001 \| [Discord Server](https://discordapp.com/invite/zTQhBn8) \| [YouTube](https://www.youtube.com/channel/UC5IikzgR1TeED-DxPLqISHg))
- Cayna (Discord: cayna#0103 \| [Twitch](https://www.twitch.tv/cayna))
- HawkCorrigan (Discord: HawkCorrigan#1811)
- Sheffy (Discord: Sheffy#4928 \| [Twitch](https://www.twitch.tv/sheffywow) \| [Twitter](https://twitter.com/SheffyWoW))

Information on this page is written with the assumption that you understand the new priority list, talents, and legendary items introduced in Shadowlands. If you have not done so, we highly recommend reading our other resources to learn about them!

The tips and recommendations listed here are based on educated opinions from beta testing as well as reviewing logs and videos, so strategies can change as we develop a better understanding of each fight or as the spec and bosses are tuned. If you have any disagreements, feedback, or questions, please feel welcome to reach out to the team.
# Bosses

<p style="color:red">Click/tap on a dungeon's header image to expand it.</p>

<hr>
<div class="dungeon-accordion">
  <div id="accordion">
    <div class="card">
        <div class="card-header" id="ataldazar">
            <div data-toggle="collapse" data-target="#shriekwing-collapse" aria-expanded="true" aria-controls="shriekwing-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
        </div>
        <div id="shriekwing-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
          <div class="card-body" markdown="1">   

## Shriekwing

**Boss Fight Profile:** Single-Target

**Talents:**
* **15**: {{ site.datat.talent.echo_of_the_elements }}
* **30**: {{ site.data.talent.echoing_shock }} or {{ site.data.talent.elemental_blast }}
* **45**: {{ site.data.talent.spirit_wolf }} OR {{ site.data.talent.earth_shield }}
* **60**: {{ site.data.talent.master_of_the_elements }}
* **75**: {{ site.data.talent.wind_rush_totem }}
* **90**: {{ site.data.talent.icefury }}
* **100**: {{ site.data.talent.stormkeeper }}

**Potential Legendaries:**
- Windspeaker's Lava Resurgence
- Elemental Equilibrium

**Damage:**
- Utilize Spiritwalker's Grace or instant casts if targeted with Echolocation.
- If possible, pool Maelstrom on Shriekwing during Phase 2, but do not be reckless for it.

**Defensives:**
- Use {{ site.data.spell.astral_shift }} for Bloodcurdling Shriek and Reverberating Scream as needed.
- {{ site.data.talent.spirit_wolf }} can help your survivability during intermission. {{ site.data.talent.earth_shield }} can offer HPS against the constant damage from Reverberating Scream.

**Healing:**
- Phase 2 is a great opportunity to support your raid with off-healing through Healing Stream Totem, Chain Heal, and Healing Surge as needed.

**Utilities:**
- If talented, use {{ site.data.talent.wind_rush_totem }} as needed to help raid members with Echolocation, Echoing Shreek, or throughout Phase 2.

**Notes:**
- The damage patterns for this fight are either small trickles or very lethal. As such, {{ site.data.talent.natures_guardian }} may not prove useful, and {{ site.data.talent.wind_rush_totem }} will offer better survivability for you and your raid.
- Because Sonar Shriek is a Horrify and not a Fear, you cannot use {{ site.data.spell.tremor_totem }} to dispel players.
        
</div>
</div>
</div>

<div class="card">
<div class="card-header" id="ataldazar">
<div data-toggle="collapse" data-target="#altimor-collapse" aria-expanded="true" aria-controls="altimor-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
</div>
<div id="altimor-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
<div class="card-body" markdown="1"> 

## Huntsman Altimor

**Boss Fight Profile:** Cleave / Spread Cleave

**Talents:**
* **15**: {{ site.datat.talent.echo_of_the_elements }}
* **30**: {{ site.data.talent.echoing_shock }}
- 1 - SW
- 1 - MotE
- 1 - NG
- 2 - PE
- 2 - SK

**Potential Legendaries:**
- Skybreaker's Fiery Demise
- Echoes of Great Sundering
- Elemental Equilibrium

**Damage:**
- Maintain {{ site.data.spell.flame_shock }} on the boss and the active pet.
- Use {{ site.data.spell.earthquake}} when the boss and active pet are stacked together.
- Utilize Spiritwalker's Grace or instant casts for Vicious Lunge and Petrifying Howl, as well as for Sinseeker and Shatter Shot on Mythic difficulty.

**Defensives:**
- Use {{ site.data.spell.astral_shift }} and {{ site.data.spell.harden_skin }} (if PE talented) for Vicious Lunge and Shattering Stone as needed.

- If talented, {{ site.data.talent.spirit_wolf }} can help your survivability against Sinseeker as needed as well as navigating Petrifying Howl.

**Healing:**
- On Mythic difficulty, utilize your healing abilities as needed to keep yourself and nearby members healthy for the impending Pierced Soul adds when soaking Sinseeker during Bargast.

**Utilities:**
- Use {{ site.data.spell.hex }} on Shades of Bargast as assigned.

**Notes:**
- From beta testing, Shades of Bargast gained additional Destabilize stacks for each unique crowd control effect on them. If intended, then use {{ site.data.spell.capacitor_totem }} on them as well.

</div>
</div>
</div>

<div class="card">
<div class="card-header" id="ataldazar">
<div data-toggle="collapse" data-target="#salvation-collapse" aria-expanded="true" aria-controls="salvation-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
</div>
<div id="salvation-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
<div class="card-body" markdown="1"> 

## Sun King's Salvation

**Boss Fight Profile:** AoE / Cleave

**Talents:**
* **15**: {{ site.data.talent.echo_of_the_elements }}
* **30**: {{ site.data.talent.echoing_shock }}
* **45**: {{ site.data.talent.spirit_wolf }}
- 1/2 - MotE/SE
- 1/3 - NG/WRT
- 2 - PE
- 2 - SK

**Potential Legendaries:**
- Skybreaker's Fiery Demise
- Echoes of Great Sundering

**Damage:**
- Maintain {{ site.data.spell.flame_shock }} on priority targets.
- Use {{ site.data.spell.earthquake }} when 2+ targets are together. Use {{ site.data.spell.chain_lightning }} when 3+ targets are together.
- Utilize Spiritwalker's Grace or instant casts for Ember Blast.
- If talented, hold Primal Storm Elemental for incoming add waves.

**Defensives:**
- Use {{ site.data.spell.astral_shift }} and {{ site.data.spell.harden_skin }} (if PE talented) for Crimson Flurry (from Bleakwing Assassins) and Ember Blast (from Shade of Kael'thas) as needed.
- If talented, {{ site.data.talent.spirit_wolf }} allows you to mitigate damage from Soul Pedestals.

**Healing:**
- If there is any downtime between add phases, support your raid with off-healing through Healing Stream Totem, Chain Heal, and Healing Surge.
- If talented, you can use {{ site.data.talent.earth_shield }} on Kael'thas for additional healing.
- On Mythic difficulty, support healing through Cloak of Absorption with Healing Surge as needed.

**Utilities:**
- Interrupt Vulgar Brand and Scornful Blast from Vile Occultists as assigned.
- Use {{ site.data.spell.earthbind_totem }} and {{ site.data.spell.thunderstorm }} on Reborn Phoenixes as needed.
- Use {{ site.data.spell.earthbind_totem }} and {{ site.data.spell.capacitor_totem }} on Soul Infusers as needed.
- If talented, use {{ site.data.talent.wind_rush_totem }} as needed to help kite away from Reborn Phoenixes.

**Notes:**
- This encounter has various phases of priority and AoE damage, with priority damage even moreso on Mythic difficulty. Determine how you need to prioritize your damage to serve your raid team.
- If using Primal Earth Elemental for {{ site.data.spell.harden_skin }}, make sure it is not picking up adds and interfering with your tanks.

</div>
</div>
</div>

<div class="card">
<div class="card-header" id="ataldazar">
<div data-toggle="collapse" data-target="#artificer-collapse" aria-expanded="true" aria-controls="artificer-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
</div>
<div id="artificer-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
<div class="card-body" markdown="1"> 

## Artificer Xy'mox

**Boss Fight Profile:** Single-Target / Spread Cleave

**Talents:**
* **15**: {{ site.data.talent.echo_of_the_elements }}
* **30**: {{ site.data.talent.echoing_shock }}
* **45**: {{ site.data.talent.spirit_wolf }}/ES
* 1 - MotE
* 3 - WRT
* 3 - IF
* 2 - SK

**Potential Legendaries:**
- Windspeaker's Lava Resurgence
- Elemental Equilibrium

**Damage:**
- This is a very movement heavy fight, so be proactive with your instant casts and use Spiritwalker's Grace liberally.

**Defensives:**
- Use {{ site.data.spell.astral_shift }} as needed for Glyph of Destruction and Seed of Extinction.
- {{ site.data.talent.spirit_wolf }} allows you to better navigate the mechanics from each relic. {{ site.data.talent.earth_shield }} can offer HPS against constant damage (i.e. Hyperlight Spark, Glyph of Destruction, Withering Touch, and Aura of Dread).

**Utilities:**
- If talented, use {{ site.data.talent.wind_rush_totem }} as needed to help raid members place Dimensional Tears, move Seeds of Extinction, and avoid Edge of Annihilation.

**Notes:**
- Because the Possession from Fleeting Spirits is a mind control and not a Charm, you cannot use {{ site.data.spell.tremor_totem }} to dispel players.

## Hungering Destroyer

**Boss Fight Profile:** Single-Target

**Talents:**
* **15**: {{ site.data.talent.echo_of_the_elements }}
* **30**: {{ site.data.talent.echoing_shock }} OR EB
* **45**: {{ site.data.talent.spirit_wolf }}
* 1 - MotE
* 1/3 - NG/WRT
* 3 - IF
* 2 - SK

**Potential Legendaries:**
- Windspeaker's Lava Resurgence
- Elemental Equilibrium

**Damage:**
- Utilize Spiritwalker's Grace or instant casts when spreading for Volatile Ejection and running from Consume.

**Defensives:**
- Use {{ site.data.spell.astral_shift }} as needed for any overlapping mechanics between Gluttonous Miasma, Expunge, and Desolate.
- If talented, {{ site.data.talent.spirit_wolf }} can be used to mitigate Consume when you are out of range of the boss, and the increased movement speed will improve your Expunge placements.

**Healing:**
- Make sure you are healthy before Expunge is cast. Support your raid members with off-healing if any are dangerously low.

**Utilities:**
- If talented, use {{ site.data.talent.wind_rush_totem }} as needed to help raid members position Volatile Ejection or run away from Consume.

**Notes:**
- Remember that when you are affected by Gluttonous Miasma, {{ site.data.talent.earth_shield }} and {{ site.data.talent.natures_guardian }} will not be useful if talented.

</div>
</div>
</div>

<div class="card">
<div class="card-header" id="ataldazar">
<div data-toggle="collapse" data-target="#darkvein-collapse" aria-expanded="true" aria-controls="darkvein-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
</div>
<div id="darkvein-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
<div class="card-body" markdown="1"> 

## Lady Inerva Darkvein

**Boss Fight Profile:** Single-Target / AoE / Funnel

**Talents:**
* **15**: {{ site.datat.talent.echo_of_the_elements }}
* 2 - EcS
* **45**: {{ site.data.talent.spirit_wolf }}/ES
* 1 - MotE
* 1 - NG
* 2 - PE
* 2 - SK

**Potential Legendaries:**
- Windspeaker's Lava Resurgence
- Echoes of Great Sundering

**Damage:**
- Maintain {{ site.data.spell.flame_shock }} on the boss and the Harnessed Specter add.
- Use {{ site.data.spell.earthquake }} when 2+ targets are together. Use {{ site.data.spell.chain_lightning }} when 3+ targets are together.
- Pool Maelstrom for incoming add spawns. If Echoes of Great Sundering is equipped, hold a proc for an incoming add spawn as well.
- Utilize Spiritwalker's Grace or instant casts as needed when targeted with Shared Suffering.

**Defensives:**
- Use {{ site.data.spell.astral_shift }} as needed for Change of Heart and Bottled Anima vials.
- {{ site.data.talent.spirit_wolf }} can be used to mitigate damage from Loose Anima (if channeling) or to run out and soak far away Bottled Anima vials. {{ site.data.talent.earth_shield }} can offer you HPS because of the constant damage from Loose Anima.

**Utilities:**
- Interrupt Condemn as assigned.

**Notes:**
- Because Shaman have the lowest CD interrupt, two Shaman and a tank make an ideal interrupt rotation for a Conjured Manifestation add.
- If using Primal Earth Elemental for {{ site.data.spell.harden_skin }}, make sure it is not picking up adds and interfering with your tanks.

</div>
</div>
</div>

<div class="card">
<div class="card-header" id="ataldazar">
<div data-toggle="collapse" data-target="#council-collapse" aria-expanded="true" aria-controls="council-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
</div>
<div id="council-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
<div class="card-body" markdown="1"> 


## The Council of Blood

**Boss Fight Profile:** Single-Target / Funnel

**Talents:**
* **15**: {{ site.datat.talent.echo_of_the_elements }}
* 2 - EcS
* **45**: {{ site.data.talent.spirit_wolf }}/ES
* 1 - MotE
* 1/3 - NG/WRT
* 2 - PE
* 2 - SK

**Potential Legendaries:**
- Skybreaker's Fiery Demise
- Windspeaker's Lava Resurgence

**Damage:**
- Maintain {{ site.data.spell.flame_shock }} on as many targets as possible.
- During the Danse Macabre, the bosses are still targetable even with 99% damage reduction. Continue maintaining {{ site.data.spell.flame_shock }}. If Skybreaker's Fiery Demise is equipped, this will especially be a major boon.
- Utilize Spiritwalker's Grace or instant casts as needed for Anima Fountain, Waltz of Blood, Dark Recital, and Dancing Fever (on Mythic difficulty).

**Defensives:**
- Use {{ site.data.spell.astral_shift }} as needed for Dark Recital or as mechanics become overwhelming with increasing damage from Oppressive Atmosphere.
- {{ site.data.talent.spirit_wolf }} can help you move quickly or mitigate damage from Scarlet Letter, Unstoppable Charge, Castellan's Cadre, and Dancing Fools. {{ site.data.talent.earth_shield }} can offer you HPS against the constant damage from Oppressive Atmosphere alone.

**Utilities:**
- Interrupt Bolt of Power from Baroness Frieda as assigned.

- If talented, use {{ site.data.talent.wind_rush_totem }} as needed to help raid members position for Danse Macabre, Anima Fountain, Waltz of Blood.

## Sludgefist

**Boss Fight Profile:** Single-Target

**Talents:**
* **15**: {{ site.datat.talent.echo_of_the_elements }}
* 2 - EcS
* **45**: {{ site.data.talent.spirit_wolf }}/ES
* 1 - MotE
* 1/3 - NG/WRT
* 3 - IF
* 2 - SK

**Potential Legendaries:**
- Windspeaker's Lava Resurgence
- Elemental Equilibrium

**Damage:**
- Destructive Impact occurs nearly every minute. If Stormkeeper is talented, it is a good idea to line up the cast with each Destructive Impact.
- Utilize Spiritwalker's Grace or instant casts as needed for Destructive Stomp, Falling Rubble, Chain Slam, and Seismic Shift (on Mythic difficulty).

**Defensives:**
- Use {{ site.data.spell.astral_shift }} as needed for Colossal Roar and Destructive Impact.
- Because you will take constant damage from Chain Link and Collapsing Foundation, {{ site.data.talent.earth_shield }} is a good talent option for HPS.

**Utilities:**
- If talented, use {{ site.data.talent.wind_rush_totem }} as needed to help raid members position out of Destructive Stomp or Falling Rubble.

**Notes:**
- Because of the Chain Link mechanic, be careful about your time spent in {{ site.data.spell.ghost_wolf }}, especially if you are paired with a player less mobile.

</div>
</div>
</div>

<div class="card">
<div class="card-header" id="ataldazar">
<div data-toggle="collapse" data-target="#generals-collapse" aria-expanded="true" aria-controls="generals-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
</div>
<div id="generals-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
<div class="card-body" markdown="1"> 


## Stone Legion Generals

**Boss Fight Profile:** AoE / Cleave

**Talents:**
* **15**: {{ site.datat.talent.echo_of_the_elements }}
* 2 - EcS
* **45**: {{ site.data.talent.spirit_wolf }}/ES
* **60**: {{ site.data.talent.master_of_the_elements }}
* 1/3 - NG/WRT
* 2 - PE
* 2 - SK

**Potential Legendaries:**
- Echoes of Great Sundering
- Skybreaker's Fiery Demise

**Damage:**
- Maintain {{ site.data.spell.flame_shock }} on as many targets as possible.
- Use {{ site.data.spell.earthquake }} when 2+ targets are together. Use {{ site.data.spell.chain_lightning }} when 3+ targets are together.
- If Echoes of Great Sundering is equipped, prepare a proc for incoming waves of adds.
- Utilize Spiritwalker's Grace or instant casts as needed when targeted by Wicked Blade, Seismic Upheaval, and Reverberating Eruption.

**Defensives:**
- Use {{ site.data.spell.astral_shift }} and {{ site.data.spell.harden_skin }} (if PE talented) as needed for Pulverizing Meteor and Heart Hemorrhage.
- Because you may take constant damage from Wicked Laceration and Heart Rend, {{ site.data.talent.earth_shield }} is a good talent option for HPS.

**Utilities:**
- If talented, use {{ site.data.talent.wind_rush_totem }} as needed to help raid members running for Stonegale Effigy or Shattering Blast.

**Notes:**
- If using Primal Earth Elemental for {{ site.data.spell.harden_skin }}, make sure it is not picking up adds and interfering with your tanks.

</div>
</div>
</div>

<div class="card">
<div class="card-header" id="ataldazar">
<div data-toggle="collapse" data-target="#denathrius-collapse" aria-expanded="true" aria-controls="denathrius-collapse" class="dungeon-header ataldazar"><h2>Atal'Dazar</h2></div>
</div>
<div id="denathrius-collapse" class="collapse" aria-labelledby="ataldazar" data-parent="#accordion">
<div class="card-body" markdown="1"> 


## Sire Denathrius

**Boss Fight Profile:** ST / Cleave / Spread Cleave

**Talents:**
* **15**: {{ site.datat.talent.echo_of_the_elements }}
* 2 - EcS
* **45**: {{ site.data.talent.spirit_wolf }}/ES
* **60**: {{ site.data.talent.master_of_the_elements }}
* 3 - WRT
* 1/2 - IF/PE
* 2 - SK

**Potential Legendaries:**
- Skybreaker's Fiery Demise
- Echoes of Great Sundering

**Damage:**
Phase 1:
- Pool Maelstrom for Echo of Sin adds. If talented, hold Stormkeeper for them as well.
- Use Spiritwalker's Grace or instant casts as needed when targeted by Feeding Time (Night Hunter on Heroic/Mythic).

Phase 2:
- Maintain {{ site.data.spell.flame_shock }} on Sire Denathrius, Remornia, and any additional adds as you can.
- Use {{ site.data.spell.earthquake }} when 2+ targets are together. Use {{ site.data.spell.chain_lightning }} when 3+ targets are together.
- Depending on timings, you may pool Maelstrom and hold CDs to optimize the Wracking Pain debuff on enemies.

Phase 3:
- Use Spiritwalker's Grace or instant casts as needed when targeted by Fatal Finesse and soaking Smoldering Ire.

**Defensives:**
Phase 1:
- Use {{ site.data.spell.astral_shift }} and {{ site.data.spell.harden_skin }} (if PE talented) as needed for Feeding Time (Night Hunter on Heroic/Mythic), Blood Price, or Cleansing Pain.

Phase 2:
- Use {{ site.data.spell.astral_shift }} and {{ site.data.spell.harden_skin }} (if PE talented) as needed for Impale or increasing Crimson Chorus stacks.

Phase 3:
- Use {{ site.data.spell.astral_shift }} and {{ site.data.spell.harden_skin }} (if PE talented) as needed for Fatal Finesse or Smoldering Ire.

\---
- This encounter is very movement demanding, so the additional movement from {{ site.data.talent.spirit_wolf }} can be beneficial in each phase. Burden of Sin, Carnage, Crimson Chorus, and Fatal Finesse are all constant sources of damage that can allow HPS from {{ site.data.talent.earth_shield }}.

**Healing:**
Intermission:
- As you will likely make it ahead of your raid during March of the Penitent, it is a good opportunity to briefly off-heal your fellow raid members after your Burden of Sin stacks drop.

**Utilities:**
Phase 1:
- Use {{ site.data.talent.wind_rush_totem }} as needed to help your raid position out of Ravage.

Phase 2:
- Use {{ site.data.talent.wind_rush_totem }} as needed to help your raid avoid Massacre and Hand of Destruction.

Phase 3:
- Use {{ site.data.talent.wind_rush_totem }} as needed to help your raid members navigate Shattering Pain, Hand of Destruction, Ravage, and Massacre.

**Notes:**
- Because of {{ site.data.spell.ghost_wolf }}, you will not be slowed during March of the Penitent in Phase 1, but you must be in {{ site.data.spell.ghost_wolf }} form before the phase begins. Consider not clearing any Burden of Sin stacks during this phase.
- If using Primal Earth Elemental for {{ site.data.spell.harden_skin }}, make sure it is not picking up adds and interfering with your tanks.

# Miscellaneous Tips
- GCDs spent on healing and utilities are GCDs not spent on damage, but both are necessary to down a raid boss. Find the balance to optimize your contributions to your raid team.

- Time spent in {{ site.data.spell.ghost_wolf }} is time spent not doing damage. Practice proactive movement and utilizing Spiritwalker's Grace and instant casts as much as you can for movement heavy encounters.

- When talenting Primal Elementalist, always remember you have an additional defensive ({{ site.data.spell.harden_skin }}) and single target stun (Pulverize) through Earth Elemental.

- Recall that Stampeding Roar is now a baseline Druid ability. Depending on your raid comp, it may not be necessary to talent {{ site.data.talent.wind_rush_totem }}.

- As kill times become faster on farm, Ancestral Reminder may be a competitive legendary to use for some bosses.

</div>
</div>
</div>
</div>
</div>