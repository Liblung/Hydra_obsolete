---
layout: post
title: "anon-hl2's Patch"
categories: CATEGORY-1 CATEGORY-2
permalink: /patch
---

![](Assets/Untitled.png)

What exactly did the first Anon-HL2 patch update? What can we infer from this, and what might have been replaced? 

In the patch are files that can replace, update or add files. We can't tell which - but we do still know what was worked on. 

The timestamps begin at 11 pm on September 23, 2003, and ends at 7 am on September 27, 2003. This is in contrast to the prior leak which ranges from September 10 at 10 pm to September 22 at 1 am.

Highlights: 
* HL2, Studiomdl, WC, HLMV and other /bin/ exes were replaced. Perhaps the model format was updated?
* A new set of perftest textures, a perftest skybox, a script for testing, and a new map called "perftestb" were added in.
* Some textures in Building_Template. 
* The poison headcrab has a new set of textures. Preexisting heightmaps in the Poison Zombie's folder imply these are updates.
* The poison zombie's sheet has a new texture. This may have replaced the one used in the prior render.
* The buggy now has textures for an ammo box. 
* Some textures in Concrete. Specifically, concretefloor019a and concretefloor028.
* "prop.vtf" was modified for the Combine Gunship. It's the propeller on the back. The E3 2003 version of it doesn't appear much different.
* 2 early infinite ammo crates were added for "bullets" and "rockets". 
* The placeholder texture for the "ammo" rebel citizens is added. The facemaps for Art and Eric were also updated, and their models were modified. 
* The skybox sky_c17_04 was updated, alongside sky_perf01. 

## Texture Additions
* Building_Template\Building_Skybridge_Template001[a-c].vtf
* Building_Template\Building_Template002k
* Building_Template\Building_Template004[a-i].vtf
* Building_Template\Building_Template005[a-i].vtf
* Building_Template\Building_Template007[a-n].vtf[^1]
* Building_Template\Building_Template008[a-i].vtf
* Building_Template\Building_Template018[a-k].vtf
* Building_Template\Building_Template019[a-i].vtf
* Building_Template\Building_Template020[a-i].vtf
* Building_Template\Building_Template021[a-k].vtf
* Building_Template\Building_Template022[a-k].vtf
* Concrete\concretefloor019a
* Concrete\concretefloor028[a] [c-f]
* Decals\decalstain015a
* Decals\rollermine_crater
* Decals\TrashDecal04a
* Decals\TrashDecal05a
* Decals\unburrow
* Effects\com_shield002a
* Overlays\macro01a
* Overlays\macro01b

[^1]: If we interpret the addition of .vmts as an indication of additions, then 007h - 019i and 021-022 were added.

## Model Additions
* alyx.mdl
* buggy.mdl
* Combine_Soldier.mdl
* Combot.mdl
* dog.mdl
* error.mdl
* gunship.mdl
* headcrabclassic.mdl
* monk.mdl
* Odell.mdl
* Police.mdl
* Humans\Male_04.mdl
* Humans\Male_05.mdl
* Items\ammoCrate_Bullets.mdl
* Items\ammoCrate_Rockets.mdl
* Items\battery.mdl
* Items\HealthKit.mdl
* Items\ML_Grenade.mdl
* props_c17\fountain_01.mdl
* props_c17\FurnitureRadiator001a.mdl
* props_c17\oildrum001.mdl
* props_c17\oildrum001_explosive.mdl
* props_c17\truck01.mdl
* props_junk\wood_crate001a.phy
* props_junk\TrashDumpster02b.mdl
* props_junk\TrashDumpster02.mdl
* ShaderTest\envballs.mdl
## Misc Additions

```
hl2\scenes\npc\citizen
hl2\scenes\npc\citizen\abouttime01.vcd
hl2\scenes\npc\citizen\abouttime02.vcd
hl2\scenes\npc\citizen\com_movingout.vcd

hl2\scripts\game_sounds_npc_rollermine.txt
hl2\scripts\weapon_alyxgun.txt
hl2\scripts\weapon_rpg.txt
hl2\scripts\vehicles\jeep_test.txt
XSI\Models
XSI\Models\CharacterStudioGuide_Sym.emdl
```

## Chapter Additions

### Trainstation

```
hl2\maps\d1_trainstation_05.bsp

hl2\scenes\k_lab\alyx_drink03.vcd
hl2\scenes\k_lab\teleport01a.vcd
hl2\scenes\k_lab\teleport01b.vcd
hl2\scenes\k_lab\teleport02a.vcd
```

### Canals

```
hl2\maps\d1_canals_01.bsp
hl2\maps\d1_canals_02.bsp
```

### Eli Lab

```
hl2\maps\eli_lab.bsp
hl2\maps\d3_lab_01.bsp

hl2\sound\vo\eli_lab\al_autocycle.wav
hl2\sound\vo\eli_lab\al_bethere01.wav
hl2\sound\vo\eli_lab\al_bethere02.wav
hl2\sound\vo\eli_lab\al_bethere03.wav
hl2\sound\vo\eli_lab\al_canthiswait.wav
hl2\sound\vo\eli_lab\al_comedog01.wav
hl2\sound\vo\eli_lab\al_comedog02.wav
hl2\sound\vo\eli_lab\al_conduct01.wav
hl2\sound\vo\eli_lab\al_conduct02.wav
hl2\sound\vo\eli_lab\al_dad_ques01.wav
hl2\sound\vo\eli_lab\al_dad_scared01.wav
hl2\sound\vo\eli_lab\al_dad_scared02.wav
hl2\sound\vo\eli_lab\al_dogairlock01.wav
hl2\sound\vo\eli_lab\al_dogairlock02.wav
hl2\sound\vo\eli_lab\al_doyouread.wav
hl2\sound\vo\eli_lab\al_fatherwhere.wav
hl2\sound\vo\eli_lab\al_fullwave.wav
hl2\sound\vo\eli_lab\al_getitopen01.wav
hl2\sound\vo\eli_lab\al_getitopen02.wav
hl2\sound\vo\eli_lab\al_goafter01.wav
hl2\sound\vo\eli_lab\al_goafter02.wav
hl2\sound\vo\eli_lab\al_hidad.wav
hl2\sound\vo\eli_lab\al_honest01.wav
hl2\sound\vo\eli_lab\al_honest02.wav
hl2\sound\vo\eli_lab\al_illdothat.wav
hl2\sound\vo\eli_lab\al_joking01.wav
hl2\sound\vo\eli_lab\al_joking02.wav
hl2\sound\vo\eli_lab\al_joking03.wav
hl2\sound\vo\eli_lab\al_keepwatch01.wav
hl2\sound\vo\eli_lab\al_keepwatch02.wav
hl2\sound\vo\eli_lab\al_keepwatch03.wav
hl2\sound\vo\eli_lab\al_lefthand.wav
hl2\sound\vo\eli_lab\al_notgoing.wav
hl2\sound\vo\eli_lab\al_olddays01.wav
hl2\sound\vo\eli_lab\al_olddays02.wav
hl2\sound\vo\eli_lab\al_olddays03.wav
hl2\sound\vo\eli_lab\al_olddays04.wav
hl2\sound\vo\eli_lab\al_oldrecord01.wav
hl2\sound\vo\eli_lab\al_oldrecord02.wav
hl2\sound\vo\eli_lab\al_oldrecord03.wav
hl2\sound\vo\eli_lab\al_omgno.wav
hl2\sound\vo\eli_lab\al_omgscanners01.wav
hl2\sound\vo\eli_lab\al_omgscanners02.wav
hl2\sound\vo\eli_lab\al_omgscanners03.wav
hl2\sound\vo\eli_lab\al_onepiece.wav
hl2\sound\vo\eli_lab\al_riled01.wav
hl2\sound\vo\eli_lab\al_riled02.wav
hl2\sound\vo\eli_lab\al_scouts01.wav
hl2\sound\vo\eli_lab\al_scouts02.wav
hl2\sound\vo\eli_lab\al_south01.wav
hl2\sound\vo\eli_lab\al_south02.wav
hl2\sound\vo\eli_lab\al_stirredup01.wav
hl2\sound\vo\eli_lab\al_stirredup02.wav
hl2\sound\vo\eli_lab\al_stirredup03.wav
hl2\sound\vo\eli_lab\al_theyknow01.wav
hl2\sound\vo\eli_lab\al_theyknow02.wav
hl2\sound\vo\eli_lab\al_thisisdog01.wav
hl2\sound\vo\eli_lab\al_thisisdog02.wav
hl2\sound\vo\eli_lab\al_thisisdog03.wav
hl2\sound\vo\eli_lab\al_thisisdog04.wav
hl2\sound\vo\eli_lab\al_thisisdog05.wav
hl2\sound\vo\eli_lab\al_thisisdog06.wav
hl2\sound\vo\eli_lab\al_thisway.wav
hl2\sound\vo\eli_lab\al_tour01.wav
hl2\sound\vo\eli_lab\al_tour02.wav
hl2\sound\vo\eli_lab\al_trackthem.wav
hl2\sound\vo\eli_lab\al_yes.wav
hl2\sound\vo\eli_lab\eli_2mode.wav
hl2\sound\vo\eli_lab\eli_alyxsweet.wav
hl2\sound\vo\eli_lab\eli_askhim01.wav
hl2\sound\vo\eli_lab\eli_askhim02.wav
hl2\sound\vo\eli_lab\eli_askhim03.wav
hl2\sound\vo\eli_lab\eli_basehouse01.wav
hl2\sound\vo\eli_lab\eli_basehouse02.wav
hl2\sound\vo\eli_lab\eli_basehouse03.wav
hl2\sound\vo\eli_lab\eli_basehouse04.wav
hl2\sound\vo\eli_lab\eli_basehouse05.wav
hl2\sound\vo\eli_lab\eli_basehouse06.wav
hl2\sound\vo\eli_lab\eli_basehouse07.wav
hl2\sound\vo\eli_lab\eli_basehouse08.wav
hl2\sound\vo\eli_lab\eli_comeout.wav
hl2\sound\vo\eli_lab\eli_evac01.wav
hl2\sound\vo\eli_lab\eli_evac02.wav
hl2\sound\vo\eli_lab\eli_evac03.wav
hl2\sound\vo\eli_lab\eli_evac04.wav
hl2\sound\vo\eli_lab\eli_fineidea01.wav
hl2\sound\vo\eli_lab\eli_fineidea02.wav
hl2\sound\vo\eli_lab\eli_fineidea03.wav
hl2\sound\vo\eli_lab\eli_granddaddy01.wav
hl2\sound\vo\eli_lab\eli_granddaddy02.wav
hl2\sound\vo\eli_lab\eli_impressed01.wav
hl2\sound\vo\eli_lab\eli_impressed02.wav
hl2\sound\vo\eli_lab\eli_impressed03.wav
hl2\sound\vo\eli_lab\eli_impressed04.wav
hl2\sound\vo\eli_lab\eli_impressed05.wav
hl2\sound\vo\eli_lab\eli_impressed06.wav
hl2\sound\vo\eli_lab\eli_impressed07.wav
hl2\sound\vo\eli_lab\eli_impressed08.wav
hl2\sound\vo\eli_lab\eli_letmethink01.wav
hl2\sound\vo\eli_lab\eli_letmethink02.wav
hl2\sound\vo\eli_lab\eli_letmethink03.wav
hl2\sound\vo\eli_lab\eli_micro01.wav
hl2\sound\vo\eli_lab\eli_micro02.wav
hl2\sound\vo\eli_lab\eli_micro03.wav
hl2\sound\vo\eli_lab\eli_mockup01.wav
hl2\sound\vo\eli_lab\eli_mockup02.wav
hl2\sound\vo\eli_lab\eli_mockup03.wav
hl2\sound\vo\eli_lab\eli_myself.wav
hl2\sound\vo\eli_lab\eli_natural01.wav
hl2\sound\vo\eli_lab\eli_natural02.wav
hl2\sound\vo\eli_lab\eli_north.wav
hl2\sound\vo\eli_lab\eli_nownow.wav
hl2\sound\vo\eli_lab\eli_pickedup01.wav
hl2\sound\vo\eli_lab\eli_pickedup02.wav
hl2\sound\vo\eli_lab\eli_pickedup03.wav
hl2\sound\vo\eli_lab\eli_realcore01.wav
hl2\sound\vo\eli_lab\eli_realcore02.wav
hl2\sound\vo\eli_lab\eli_righthand01.wav
hl2\sound\vo\eli_lab\eli_righthand02.wav
hl2\sound\vo\eli_lab\eli_techlib01.wav
hl2\sound\vo\eli_lab\eli_techlib02.wav
hl2\sound\vo\eli_lab\eli_techlib03.wav
hl2\sound\vo\eli_lab\eli_techlib04.wav
hl2\sound\vo\eli_lab\eli_techlib05.wav
hl2\sound\vo\eli_lab\eli_tryit.wav
hl2\sound\vo\eli_lab\eli_verygood.wav
hl2\sound\vo\eli_lab\eli_whereyou.wav
hl2\sound\vo\eli_lab\eli_whoa01.wav
hl2\sound\vo\eli_lab\eli_whoa02.wav
hl2\sound\vo\eli_lab\eli_withme.wav
hl2\sound\vo\eli_lab\eli_youwerethere01.wav
hl2\sound\vo\eli_lab\eli_youwerethere02.wav
hl2\sound\vo\eli_lab\eli_youwerethere03.wav
hl2\sound\vo\eli_lab\mo_excuseus01.wav
hl2\sound\vo\eli_lab\mo_excuseus02.wav
hl2\sound\vo\eli_lab\mo_goodpoint.wav
hl2\sound\vo\eli_lab\mo_important.wav
hl2\sound\vo\eli_lab\mo_outthere.wav
hl2\sound\vo\eli_lab\mo_youropinion.wav
hl2\sound\vo\eli_lab\vort_deadsea.wav
hl2\sound\vo\eli_lab\vort_taken.wav
```

### Coast

```
hl2\maps\d2_coast_01.bsp
hl2\maps\d2_coast_02.bsp
hl2\maps\d2_coast_04.bsp
hl2\maps\d2_coast_05.bsp
hl2\maps\d2_coast_07.bsp
hl2\maps\d2_coast_08.bsp

hl2\sound\vo\coast\cr_antlions.wav
hl2\sound\vo\coast\cr_bigbarr.wav
hl2\sound\vo\coast\cr_driveforfeel.wav
hl2\sound\vo\coast\cr_excellent.wav
hl2\sound\vo\coast\cr_gravgun.wav
hl2\sound\vo\coast\cr_magfail.wav
hl2\sound\vo\coast\cr_pier01.wav
hl2\sound\vo\coast\cr_pier02.wav
hl2\sound\vo\coast\cr_pier03.wav
hl2\sound\vo\coast\cr_playerincar.wav
hl2\sound\vo\coast\cr_ramp.wav
hl2\sound\vo\coast\cr_rockslide.wav
hl2\sound\vo\coast\cr_smallbarr.wav
hl2\sound\vo\coast\cr_sorry.wav
hl2\sound\vo\coast\cr_steep.wav
hl2\sound\vo\coast\cr_surfaces.wav
hl2\sound\vo\coast\cr_turbojump.wav
hl2\sound\vo\coast\cubbage01.wav
hl2\sound\vo\coast\cubbage02.wav
hl2\sound\vo\coast\cubbage03.wav
hl2\sound\vo\coast\rpgguy_doasisay.wav
hl2\sound\vo\coast\rpgguy_greet.wav
hl2\sound\vo\coast\rpgguy_outsmart.wav
hl2\sound\vo\coast\rpgguy_showyou.wav
hl2\sound\vo\coast\rpgguy_watchthis.wav

hl2\scripts\game_sounds_coast.txt
hl2\scripts\game_sounds_eli_lab.txt
```
### Nova Prospekt

```
hl2\scenes\novaprospekt\conference01.vcd
```

### C17

```
hl2\maps\d3_c17_04.bsp
hl2\maps\d3_c17_05.bsp
hl2\maps\d3_c17_09.bsp
hl2\maps\d3_c17_10a.bsp

hl2\materials\Models\props_buildings\DestroyedBuillding01a.vmt
hl2\materials\Models\props_buildings\DestroyedBuillding01a.vtf
hl2\materials\Models\props_buildings\DestroyedBuilldingWall01a.vmt
hl2\materials\Models\props_buildings\DestroyedBuilldingWall01a.vtf

hl2\materials\Models\props_c17\awning001d.vtf
hl2\materials\Models\props_c17\fountain.vmt
hl2\materials\Models\props_c17\fountain.vtf
hl2\materials\Models\props_c17\fountain_normal.vtf
hl2\materials\Models\props_c17\overpass_001b.vmt
hl2\materials\Models\props_c17\overpass_001b.vtf

hl2\materials\Models\props_combine\combine_gate_vehicle01a.vmt
hl2\materials\Models\props_combine\combine_gate_vehicle01a.vtf
hl2\materials\Models\props_combine\com_shield001a.vmt
hl2\materials\Models\props_combine\com_shield001a.vtf
hl2\materials\Models\props_combine\com_shield001a_dudv.vtf

hl2\models\props_c17\artpedestal01.jpg
hl2\models\props_c17\barrel09a.jpg
hl2\models\props_c17\BriefCase001a.jpg
hl2\models\props_c17\canisterchunk01e.dx7_2bone.vtx
hl2\models\props_c17\canisterchunk01e.dx80.vtx
hl2\models\props_c17\canisterchunk01e.mdl
hl2\models\props_c17\canisterchunk01e.phy
hl2\models\props_c17\canister_propanechunk02a.jpg
hl2\models\props_c17\chimney01.jpg
hl2\models\props_c17\fountain_01.dx7_2bone.vtx
hl2\models\props_c17\fountain_01.dx80.vtx
hl2\models\props_c17\fountain_01.jpg
hl2\models\props_c17\fountain_01.mdl
hl2\models\props_c17\fountain_01.phy
hl2\models\props_c17\frame01.jpg
hl2\models\props_c17\FurnitureDrawer001a.jpg
hl2\models\props_c17\FurnitureMattress001a.jpg
hl2\models\props_c17\FurnitureRadiator001a.dx7_2bone.vtx
hl2\models\props_c17\FurnitureRadiator001a.dx80.vtx
hl2\models\props_c17\FurnitureRadiator001a.mdl
hl2\models\props_c17\FurnitureRadiator001a.phy
hl2\models\props_c17\FurnitureShelf001b.jpg
hl2\models\props_c17\FurnitureWashingmachine001a.jpg
hl2\models\props_c17\Gasmeter001a.dx7_2bone.vtx
hl2\models\props_c17\Gasmeter001a.dx80.vtx
hl2\models\props_c17\Gasmeter001a.mdl
hl2\models\props_c17\Gasmeter001a.phy
hl2\models\props_c17\Gasmeter002a.dx7_2bone.vtx
hl2\models\props_c17\Gasmeter002a.dx80.vtx
hl2\models\props_c17\Gasmeter002a.jpg
hl2\models\props_c17\Gasmeter002a.mdl
hl2\models\props_c17\Gasmeter002a.phy
hl2\models\props_c17\Gasmeter003a.dx7_2bone.vtx
hl2\models\props_c17\Gasmeter003a.dx80.vtx
hl2\models\props_c17\Gasmeter003a.mdl
hl2\models\props_c17\Gasmeter003a.phy
hl2\models\props_c17\Handrail01_corner.jpg
hl2\models\props_c17\Handrail04_brokenCorner.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_brokenCorner.dx80.vtx
hl2\models\props_c17\Handrail04_brokenCorner.mdl
hl2\models\props_c17\Handrail04_brokenCorner.phy
hl2\models\props_c17\Handrail04_brokenLong.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_brokenLong.dx80.vtx
hl2\models\props_c17\Handrail04_brokenLong.mdl
hl2\models\props_c17\Handrail04_brokenLong.phy
hl2\models\props_c17\Handrail04_brokenSingleRise.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_brokenSingleRise.dx80.vtx
hl2\models\props_c17\Handrail04_brokenSingleRise.mdl
hl2\models\props_c17\Handrail04_brokenSingleRise.phy
hl2\models\props_c17\Handrail04_corner.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_corner.dx80.vtx
hl2\models\props_c17\Handrail04_corner.mdl
hl2\models\props_c17\Handrail04_corner.phy
hl2\models\props_c17\Handrail04_DoubleRise.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_DoubleRise.dx80.vtx
hl2\models\props_c17\Handrail04_DoubleRise.mdl
hl2\models\props_c17\Handrail04_DoubleRise.phy
hl2\models\props_c17\Handrail04_long.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_long.dx80.vtx
hl2\models\props_c17\Handrail04_long.mdl
hl2\models\props_c17\Handrail04_long.phy
hl2\models\props_c17\Handrail04_Medium.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_Medium.dx80.vtx
hl2\models\props_c17\Handrail04_Medium.mdl
hl2\models\props_c17\Handrail04_Medium.phy
hl2\models\props_c17\Handrail04_SingleRise.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_SingleRise.dx80.vtx
hl2\models\props_c17\Handrail04_SingleRise.mdl
hl2\models\props_c17\Handrail04_SingleRise.phy
hl2\models\props_c17\light_domelight02_on.jpg
hl2\models\props_c17\light_globelight01_off.jpg
hl2\models\props_c17\light_lightbare01_off.jpg
hl2\models\props_c17\lockerdoor003a.jpg
hl2\models\props_c17\oildrum001.dx7_2bone.vtx
hl2\models\props_c17\oildrum001.dx80.vtx
hl2\models\props_c17\oildrum001.mdl
hl2\models\props_c17\oildrum001.phy
hl2\models\props_c17\oildrum001_explosive.dx7_2bone.vtx
hl2\models\props_c17\oildrum001_explosive.dx80.vtx
hl2\models\props_c17\oildrum001_explosive.jpg
hl2\models\props_c17\oildrum001_explosive.mdl
hl2\models\props_c17\oildrum001_explosive.phy
hl2\models\props_c17\oildrumchunk01a.jpg
hl2\models\props_c17\oildrumchunk01b.jpg
hl2\models\props_c17\oildrumchunk01c.jpg
hl2\models\props_c17\oildrumchunk01d.jpg
hl2\models\props_c17\oildrumchunk01e.jpg
hl2\models\props_c17\oildrumchunk01f.jpg
hl2\models\props_c17\oildrumchunk01g.jpg
hl2\models\props_c17\oildrumchunk01h.jpg
hl2\models\props_c17\oildrumchunk01i.jpg
hl2\models\props_c17\oildrumchunk01j.jpg
hl2\models\props_c17\oildrumchunk01k.jpg
hl2\models\props_c17\oil_drumchunk001a.jpg
hl2\models\props_c17\oil_drumchunk001b.jpg
hl2\models\props_c17\oil_drumchunk001c.jpg
hl2\models\props_c17\oil_drumchunk001d.jpg
hl2\models\props_c17\overpass_001a.dx7_2bone.vtx
hl2\models\props_c17\overpass_001a.dx80.vtx
hl2\models\props_c17\overpass_001a.jpg
hl2\models\props_c17\overpass_001a.mdl
hl2\models\props_c17\overpass_001a.phy
hl2\models\props_c17\overpass_001b.dx7_2bone.vtx
hl2\models\props_c17\overpass_001b.dx80.vtx
hl2\models\props_c17\overpass_001b.jpg
hl2\models\props_c17\overpass_001b.mdl
hl2\models\props_c17\overpass_001b.phy
hl2\models\props_c17\pipe01_connector01.jpg
hl2\models\props_c17\pipe02_lcurve02_long.jpg
hl2\models\props_c17\pulleywheels_small01.jpg
hl2\models\props_c17\streetsign001c.jpg
hl2\models\props_c17\tank_cooling01a.jpg
hl2\models\props_c17\Trap_Scythe01a.jpg
hl2\models\props_c17\truck01.dx7_2bone.vtx
hl2\models\props_c17\truck01.dx80.vtx
hl2\models\props_c17\truck01.mdl
hl2\models\props_c17\truck01.phy
hl2\models\props_c17\truss01.jpg
hl2\models\props_c17\truss02f.mdl
hl2\models\props_c17\truss02f.phy
hl2\models\props_c17\utilityconnecter006.jpg
hl2\models\props_c17\utilityconnecter006d.jpg

hl2\scenes\npc\citizen
hl2\scenes\npc\citizen\abouttime01.vcd
hl2\scenes\npc\citizen\abouttime02.vcd
hl2\scenes\npc\citizen\com_movingout.vcd

hl2\scripts\game_sounds_citizen.txt
hl2\scripts\game_sounds_streetwar.txt
```

## Original Change List (trimmed)

```
hl2.dat
hl2.exe
bin\base.fgd
bin\bsppack.dll
bin\bspzip.exe
bin\bugreporter.dll
bin\buildalltextures.pl
bin\checktextures.bat
bin\difftextures.pl
bin\engine.dll
bin\FileSystem_Stdio.dll
bin\FileSystem_Steam.dll
bin\halflife2.fgd
bin\height2normal.exe
bin\hlds.exe
bin\hlfaceposer.exe
bin\hlmv.exe
bin\launcher.dll
bin\MaterialSystem.dll
bin\newdat.exe
bin\phonemeextractors
bin\playback.exe
bin\scenemanager.exe
bin\shaderapidx9.dll
bin\shaderapiempty.dll
bin\shader_nvfx.dll
bin\shader_nvfx_ps20.dll
bin\stdshader_dbg.dll
bin\stdshader_dx6.dll
bin\stdshader_dx7.dll
bin\stdshader_dx8.dll
bin\stdshader_dx9.dll
bin\stdshader_hdr_dx9.dll
bin\studiomdl.exe
bin\StudioRender.dll
bin\tier0.dll
bin\unitlib.dll
bin\vaudio_miles.dll
bin\vbsp.exe
bin\vbspinfo.exe
bin\vgui2.dll
bin\vguimatsurface.dll
bin\vphysics.dll
bin\vrad.dll
bin\vrad.exe
bin\vstdlib.dll
bin\vtex.dll
bin\vtex.exe
bin\vtf2tga.exe
bin\vvis.dll
bin\vvis.exe
bin\wc.exe
bin\phonemeextractors\phonemeextractor.dll
bin\phonemeextractors\phonemeextractor_ims.dll

hl2\bin\client.dll
hl2\bin\GameUI.dll
hl2\bin\server.dll

hl2\maps\d1_canals_01.bsp
hl2\maps\d1_canals_02.bsp
hl2\maps\d1_trainstation_05.bsp
hl2\maps\d2_coast_01.bsp
hl2\maps\d2_coast_02.bsp
hl2\maps\d2_coast_04.bsp
hl2\maps\d2_coast_05.bsp
hl2\maps\d2_coast_07.bsp
hl2\maps\d2_coast_08.bsp
hl2\maps\d3_c17_04.bsp
hl2\maps\d3_c17_05.bsp
hl2\maps\d3_c17_09.bsp
hl2\maps\d3_c17_10a.bsp
hl2\maps\d3_lab_01.bsp
hl2\maps\eli_lab.bsp
hl2\maps\perftestb.bsp

hl2\materials\Building_Template\Building_Skybridge_Template001a.vtf
hl2\materials\Building_Template\Building_Skybridge_Template001b.vtf
hl2\materials\Building_Template\Building_Skybridge_Template001c.vtf
hl2\materials\Building_Template\Building_Template002k.vtf
hl2\materials\Building_Template\Building_Template004a.vtf
hl2\materials\Building_Template\Building_Template004b.vtf
hl2\materials\Building_Template\Building_Template004c.vtf
hl2\materials\Building_Template\Building_Template004d.vtf
hl2\materials\Building_Template\Building_Template004e.vtf
hl2\materials\Building_Template\Building_Template004f.vtf
hl2\materials\Building_Template\Building_Template004g.vtf
hl2\materials\Building_Template\Building_Template004h.vtf
hl2\materials\Building_Template\Building_Template004i.vtf
hl2\materials\Building_Template\Building_Template005a.vtf
hl2\materials\Building_Template\Building_Template005b.vtf
hl2\materials\Building_Template\Building_Template005c.vtf
hl2\materials\Building_Template\Building_Template005d.vtf
hl2\materials\Building_Template\Building_Template005e.vtf
hl2\materials\Building_Template\Building_Template005f.vtf
hl2\materials\Building_Template\Building_Template005g.vtf
hl2\materials\Building_Template\Building_Template005h.vtf
hl2\materials\Building_Template\Building_Template005i.vtf
hl2\materials\Building_Template\Building_Template007a.vtf
hl2\materials\Building_Template\Building_Template007b.vtf
hl2\materials\Building_Template\Building_Template007c.vtf
hl2\materials\Building_Template\Building_Template007d.vtf
hl2\materials\Building_Template\Building_Template007e.vtf
hl2\materials\Building_Template\Building_Template007f.vtf
hl2\materials\Building_Template\Building_Template007g.vtf
hl2\materials\Building_Template\Building_Template007h.vmt
hl2\materials\Building_Template\Building_Template007h.vtf
hl2\materials\Building_Template\Building_Template007i.vmt
hl2\materials\Building_Template\Building_Template007i.vtf
hl2\materials\Building_Template\Building_Template007j.vmt
hl2\materials\Building_Template\Building_Template007j.vtf
hl2\materials\Building_Template\Building_Template007k.vmt
hl2\materials\Building_Template\Building_Template007k.vtf
hl2\materials\Building_Template\Building_Template007l.vmt
hl2\materials\Building_Template\Building_Template007l.vtf
hl2\materials\Building_Template\Building_Template007m.vmt
hl2\materials\Building_Template\Building_Template007m.vtf
hl2\materials\Building_Template\Building_Template007n.vmt
hl2\materials\Building_Template\Building_Template007n.vtf
hl2\materials\Building_Template\Building_Template008a.vtf
hl2\materials\Building_Template\Building_Template008b.vtf
hl2\materials\Building_Template\Building_Template008c.vtf
hl2\materials\Building_Template\Building_Template008d.vmt
hl2\materials\Building_Template\Building_Template008d.vtf
hl2\materials\Building_Template\Building_Template008e.vmt
hl2\materials\Building_Template\Building_Template008e.vtf
hl2\materials\Building_Template\Building_Template008f.vmt
hl2\materials\Building_Template\Building_Template008f.vtf
hl2\materials\Building_Template\Building_Template008g.vmt
hl2\materials\Building_Template\Building_Template008g.vtf
hl2\materials\Building_Template\Building_Template008h.vmt
hl2\materials\Building_Template\Building_Template008h.vtf
hl2\materials\Building_Template\Building_Template008i.vmt
hl2\materials\Building_Template\Building_Template008i.vtf
hl2\materials\Building_Template\Building_Template018a.vmt
hl2\materials\Building_Template\Building_Template018a.vtf
hl2\materials\Building_Template\Building_Template018b.vmt
hl2\materials\Building_Template\Building_Template018b.vtf
hl2\materials\Building_Template\Building_Template018c.vmt
hl2\materials\Building_Template\Building_Template018c.vtf
hl2\materials\Building_Template\Building_Template018d.vmt
hl2\materials\Building_Template\Building_Template018d.vtf
hl2\materials\Building_Template\Building_Template018e.vmt
hl2\materials\Building_Template\Building_Template018e.vtf
hl2\materials\Building_Template\Building_Template018f.vmt
hl2\materials\Building_Template\Building_Template018f.vtf
hl2\materials\Building_Template\Building_Template018g.vmt
hl2\materials\Building_Template\Building_Template018g.vtf
hl2\materials\Building_Template\Building_Template018h.vmt
hl2\materials\Building_Template\Building_Template018h.vtf
hl2\materials\Building_Template\Building_Template018i.vmt
hl2\materials\Building_Template\Building_Template018i.vtf
hl2\materials\Building_Template\Building_Template018j.vmt
hl2\materials\Building_Template\Building_Template018j.vtf
hl2\materials\Building_Template\Building_Template018k.vmt
hl2\materials\Building_Template\Building_Template018k.vtf
hl2\materials\Building_Template\Building_Template019a.vmt
hl2\materials\Building_Template\Building_Template019a.vtf
hl2\materials\Building_Template\Building_Template019b.vmt
hl2\materials\Building_Template\Building_Template019b.vtf
hl2\materials\Building_Template\Building_Template019c.vmt
hl2\materials\Building_Template\Building_Template019c.vtf
hl2\materials\Building_Template\Building_Template019d.vmt
hl2\materials\Building_Template\Building_Template019d.vtf
hl2\materials\Building_Template\Building_Template019e.vmt
hl2\materials\Building_Template\Building_Template019e.vtf
hl2\materials\Building_Template\Building_Template019f.vmt
hl2\materials\Building_Template\Building_Template019f.vtf
hl2\materials\Building_Template\Building_Template019g.vmt
hl2\materials\Building_Template\Building_Template019g.vtf
hl2\materials\Building_Template\Building_Template019h.vmt
hl2\materials\Building_Template\Building_Template019h.vtf
hl2\materials\Building_Template\Building_Template019i.vmt
hl2\materials\Building_Template\Building_Template019i.vtf
hl2\materials\Building_Template\Building_Template020a.vtf
hl2\materials\Building_Template\Building_Template020b.vtf
hl2\materials\Building_Template\Building_Template020c.vtf
hl2\materials\Building_Template\Building_Template020d.vtf
hl2\materials\Building_Template\Building_Template020e.vtf
hl2\materials\Building_Template\Building_Template020f.vtf
hl2\materials\Building_Template\Building_Template020g.vtf
hl2\materials\Building_Template\Building_Template020h.vtf
hl2\materials\Building_Template\Building_Template020i.vtf
hl2\materials\Building_Template\Building_Template021a.vmt
hl2\materials\Building_Template\Building_Template021a.vtf
hl2\materials\Building_Template\Building_Template021b.vmt
hl2\materials\Building_Template\Building_Template021b.vtf
hl2\materials\Building_Template\Building_Template021c.vmt
hl2\materials\Building_Template\Building_Template021c.vtf
hl2\materials\Building_Template\Building_Template021d.vmt
hl2\materials\Building_Template\Building_Template021d.vtf
hl2\materials\Building_Template\Building_Template021e.vmt
hl2\materials\Building_Template\Building_Template021e.vtf
hl2\materials\Building_Template\Building_Template021f.vmt
hl2\materials\Building_Template\Building_Template021f.vtf
hl2\materials\Building_Template\Building_Template021g.vmt
hl2\materials\Building_Template\Building_Template021g.vtf
hl2\materials\Building_Template\Building_Template021h.vmt
hl2\materials\Building_Template\Building_Template021h.vtf
hl2\materials\Building_Template\Building_Template021i.vmt
hl2\materials\Building_Template\Building_Template021i.vtf
hl2\materials\Building_Template\Building_Template021j.vtf
hl2\materials\Building_Template\Building_Template021k.vtf
hl2\materials\Building_Template\Building_Template022a.vmt
hl2\materials\Building_Template\Building_Template022a.vtf
hl2\materials\Building_Template\Building_Template022b.vmt
hl2\materials\Building_Template\Building_Template022b.vtf
hl2\materials\Building_Template\Building_Template022c.vmt
hl2\materials\Building_Template\Building_Template022c.vtf
hl2\materials\Building_Template\Building_Template022d.vmt
hl2\materials\Building_Template\Building_Template022d.vtf
hl2\materials\Building_Template\Building_Template022e.vmt
hl2\materials\Building_Template\Building_Template022e.vtf
hl2\materials\Building_Template\Building_Template022f.vmt
hl2\materials\Building_Template\Building_Template022f.vtf
hl2\materials\Building_Template\Building_Template022g.vmt
hl2\materials\Building_Template\Building_Template022g.vtf
hl2\materials\Building_Template\Building_Template022h.vmt
hl2\materials\Building_Template\Building_Template022h.vtf
hl2\materials\Building_Template\Building_Template022i.vmt
hl2\materials\Building_Template\Building_Template022i.vtf
hl2\materials\Building_Template\Building_Template022j.vmt
hl2\materials\Building_Template\Building_Template022j.vtf
hl2\materials\Building_Template\Building_Template022k.vmt
hl2\materials\Building_Template\Building_Template022k.vtf

hl2\materials\Concrete\concretefloor019a.vmt
hl2\materials\Concrete\concretefloor019a.vtf
hl2\materials\Concrete\concretefloor019a_height.vtf
hl2\materials\Concrete\concretefloor019a_normal.vtf
hl2\materials\Concrete\concretefloor028a.vtf
hl2\materials\Concrete\concretefloor028c.vmt
hl2\materials\Concrete\concretefloor028c.vtf
hl2\materials\Concrete\concretefloor028c_height.vtf
hl2\materials\Concrete\concretefloor028c_normal.vtf
hl2\materials\Concrete\concretefloor028d.vtf
hl2\materials\Concrete\concretefloor028e.vmt
hl2\materials\Concrete\concretefloor028e.vtf
hl2\materials\Concrete\concretefloor028f.vmt
hl2\materials\Concrete\concretefloor028f.vtf
hl2\materials\Concrete\concretewall019a.vtf

hl2\materials\Decals\decalstain015a.vmt
hl2\materials\Decals\decalstain015a.vtf
hl2\materials\Decals\rollermine_crater.vmt
hl2\materials\Decals\rollermine_crater.vtf
hl2\materials\Decals\Rubble01a.vmt
hl2\materials\Decals\Rubble01a.vtf
hl2\materials\Decals\TrashDecal04a.vmt
hl2\materials\Decals\TrashDecal04a.vtf
hl2\materials\Decals\TrashDecal05a.vmt
hl2\materials\Decals\TrashDecal05a.vtf
hl2\materials\Decals\unburrow.vmt
hl2\materials\Decals\unburrow.vtf

hl2\materials\Editor\Air_node.vmt
hl2\materials\Editor\Air_node.vtf
hl2\materials\Editor\Air_node_hint.vmt
hl2\materials\Editor\Air_node_hint.vtf
hl2\materials\Editor\Ground_node_hint.vtf

hl2\materials\Effects\com_shield002a.vmt
hl2\materials\Effects\com_shield002a.vtf

hl2\materials\Glass\glasswindow002e.vmt
hl2\materials\Glass\glasswindow002e.vtf

hl2\materials\Models\Buggy\ammo_box.vmt
hl2\materials\Models\Buggy\ammo_box.vtf

hl2\materials\Models\Effects\com_shield001a.vmt
hl2\materials\Models\Effects\com_shield001a.vtf
hl2\materials\Models\Effects\com_shield001a_dudv.vtf

hl2\materials\Models\Gibs\woodgibs\wood_gib01a.vmt
hl2\materials\Models\Gibs\woodgibs\wood_gib01a.vtf
hl2\materials\Models\Gibs\woodgibs\wood_gib02a.vmt
hl2\materials\Models\Gibs\woodgibs\wood_gib02a.vtf

hl2\materials\Models\Gunship\prop.vmt

hl2\materials\Models\HEADCRAB_BLACK\body.vmt
hl2\materials\Models\HEADCRAB_BLACK\body.vtf
hl2\materials\Models\HEADCRAB_BLACK\body_normal.vtf
hl2\materials\Models\HEADCRAB_BLACK\front_legs.vmt
hl2\materials\Models\HEADCRAB_BLACK\front_legs.vtf
hl2\materials\Models\HEADCRAB_BLACK\front_legs_normal.vtf
hl2\materials\Models\HEADCRAB_BLACK\mouth.vmt
hl2\materials\Models\HEADCRAB_BLACK\mouth.vtf
hl2\materials\Models\HEADCRAB_BLACK\mouth_normal.vtf
hl2\materials\Models\HEADCRAB_BLACK\rear_legs.vmt
hl2\materials\Models\HEADCRAB_BLACK\rear_legs.vtf
hl2\materials\Models\HEADCRAB_BLACK\rear_legs_normal.vtf

hl2\materials\Models\Humans\Male\ammo_sheet.vmt
hl2\materials\Models\Humans\Male\ammo_sheet.vtf
hl2\materials\Models\Humans\Male\art_facemap.vtf
hl2\materials\Models\Humans\Male\eric_facemap.vmt
hl2\materials\Models\Humans\Male\eric_facemap.vtf

hl2\materials\Models\Items\ammoCrate_Bullets.vmt
hl2\materials\Models\Items\ammocrate_bullets.vtf
hl2\materials\Models\Items\ammoCrate_Rockets.vmt
hl2\materials\Models\Items\ammocrate_rockets.vtf

hl2\materials\Models\props_buildings\DestroyedBuillding01a.vmt
hl2\materials\Models\props_buildings\DestroyedBuillding01a.vtf
hl2\materials\Models\props_buildings\DestroyedBuilldingWall01a.vmt
hl2\materials\Models\props_buildings\DestroyedBuilldingWall01a.vtf

hl2\materials\Models\props_c17\awning001d.vtf
hl2\materials\Models\props_c17\fountain.vmt
hl2\materials\Models\props_c17\fountain.vtf
hl2\materials\Models\props_c17\fountain_normal.vtf
hl2\materials\Models\props_c17\overpass_001b.vmt
hl2\materials\Models\props_c17\overpass_001b.vtf

hl2\materials\Models\props_combine\combine_gate_vehicle01a.vmt
hl2\materials\Models\props_combine\combine_gate_vehicle01a.vtf
hl2\materials\Models\props_combine\com_shield001a.vmt
hl2\materials\Models\props_combine\com_shield001a.vtf
hl2\materials\Models\props_combine\com_shield001a_dudv.vtf

hl2\materials\Models\props_rooftop\RoofTop_Set01a.vtf

hl2\materials\Models\props_vehicles\tanker001a_01.vmt
hl2\materials\Models\props_vehicles\tanker001a_01.vtf
hl2\materials\Models\props_vehicles\truck002a_01.vmt
hl2\materials\Models\props_vehicles\truck002a_01.vtf

hl2\materials\Models\props_wasteland\antlionhill_sheet.vmt
hl2\materials\Models\props_wasteland\antlionhill_sheet.vtf
hl2\materials\Models\props_wasteland\rockcliff01a.vmt
hl2\materials\Models\props_wasteland\rockcliff02a.vmt
hl2\materials\Models\props_wasteland\rockcliff02b.vmt
hl2\materials\Models\props_wasteland\rockcliff02c.vmt
hl2\materials\Models\props_wasteland\rockcliff03a.vmt
hl2\materials\Models\props_wasteland\rockcliff04a.vmt
hl2\materials\Models\props_wasteland\rockgranite01a.vmt
hl2\materials\Models\props_wasteland\rockgranite02a.vmt
hl2\materials\Models\props_wasteland\rockgranite03a.vmt
hl2\materials\Models\props_wasteland\rockwall001a.vmt
hl2\materials\Models\props_wasteland\rockwall004a.vmt
hl2\materials\Models\props_wasteland\rockwall004a.vtf
hl2\materials\Models\props_wasteland\rock_wasteland01a.vmt

hl2\materials\Models\Zombie_Poison\body.vmt
hl2\materials\Models\Zombie_Poison\body.vtf
hl2\materials\Models\Zombie_Poison\body_normal.vtf
hl2\materials\Models\Zombie_Poison\front_legs.vmt
hl2\materials\Models\Zombie_Poison\front_legs.vtf
hl2\materials\Models\Zombie_Poison\front_legs_normal.vtf
hl2\materials\Models\Zombie_Poison\mouth.vmt
hl2\materials\Models\Zombie_Poison\mouth.vtf
hl2\materials\Models\Zombie_Poison\mouth_normal.vtf
hl2\materials\Models\Zombie_Poison\PoisonZombie_sheet.vmt
hl2\materials\Models\Zombie_Poison\PoisonZombie_sheet.vtf
hl2\materials\Models\Zombie_Poison\rear_legs.vmt
hl2\materials\Models\Zombie_Poison\rear_legs.vtf
hl2\materials\Models\Zombie_Poison\rear_legs_normal.vtf

hl2\materials\Nature\blenddirtgrass008a.vmt
hl2\materials\Nature\blenddirtgrass008b.vmt
hl2\materials\Nature\blenddirtgrass008b_lowfriction.vmt
hl2\materials\Nature\blenddirtmud005a.vmt
hl2\materials\Nature\blenddirtmud008a.vmt
hl2\materials\Nature\blendrockdirt008a.vmt
hl2\materials\Nature\blendrockdirt008c.vmt
hl2\materials\Nature\blendrockdirt008d.vmt
hl2\materials\Nature\blendrockdirt008d_tooltexture.vtf
hl2\materials\Nature\blendsandgrass008a.vmt
hl2\materials\Nature\blendsandsand008a.vmt
hl2\materials\Nature\blendsandsand008b.vmt
hl2\materials\Nature\dirtfloor006d.vtf
hl2\materials\Nature\dirtfloor012b.vtf

hl2\materials\Overlays\macro01a.vtf
hl2\materials\Overlays\macro01a_rev.vtf
hl2\materials\Overlays\macro01b.vtf
hl2\materials\Overlays\macro01b_rev.vtf
hl2\materials\Overlays\macro01c.vtf

hl2\materials\PerfTest\babtech_bordl9.vmt
hl2\materials\PerfTest\babtech_bordl9.vtf
hl2\materials\PerfTest\blendrockdirt001a.vmt
hl2\materials\PerfTest\c2a4e_w1.vmt
hl2\materials\PerfTest\c2a4e_w1.vtf
hl2\materials\PerfTest\con1_bord04.vmt
hl2\materials\PerfTest\con1_bord04.vtf
hl2\materials\PerfTest\dev_combinemonitor_1.vmt
hl2\materials\PerfTest\dev_combinemonitor_2.vmt
hl2\materials\PerfTest\dev_combinemonitor_3.vmt
hl2\materials\PerfTest\dev_combinemonitor_4.vmt
hl2\materials\PerfTest\dev_combinemonitor_5.vmt
hl2\materials\PerfTest\dev_combinemonitor_b.vmt
hl2\materials\PerfTest\dev_combinemonitor_g.vmt
hl2\materials\PerfTest\dev_combinemonitor_r.vmt
hl2\materials\PerfTest\dev_combinescanline.vtf
hl2\materials\PerfTest\dev_scanline.vtf
hl2\materials\PerfTest\dev_tvmonitor1a.vmt
hl2\materials\PerfTest\dev_tvmonitornonoise.vmt
hl2\materials\PerfTest\dirtfloor006a.vmt
hl2\materials\PerfTest\dirtfloor006a.vtf
hl2\materials\PerfTest\fifties_dr4.vmt
hl2\materials\PerfTest\fifties_dr4.vtf
hl2\materials\PerfTest\fifties_dr5d.vmt
hl2\materials\PerfTest\fifties_dr5d.vtf
hl2\materials\PerfTest\fifties_dr6.vmt
hl2\materials\PerfTest\fifties_dr6.vtf
hl2\materials\PerfTest\generic031c.vmt
hl2\materials\PerfTest\generic031c.vtf
hl2\materials\PerfTest\gman
hl2\materials\PerfTest\loader
hl2\materials\PerfTest\out_grvl2b.vmt
hl2\materials\PerfTest\out_grvl2b.vtf
hl2\materials\PerfTest\rockcliff02b.vmt
hl2\materials\PerfTest\rockcliff02b.vtf
hl2\materials\PerfTest\rockground03a.vmt
hl2\materials\PerfTest\rockground03a.vtf
hl2\materials\PerfTest\rockwall002a.vmt
hl2\materials\PerfTest\rockwall002a.vtf
hl2\materials\PerfTest\rock_wasteland01a.vmt
hl2\materials\PerfTest\rock_wasteland01a.vtf
hl2\materials\PerfTest\water_pretty1.vmt
hl2\materials\PerfTest\water_pretty1_beneath.vmt
hl2\materials\PerfTest\gman\GMan_Arm-L1.vmt
hl2\materials\PerfTest\gman\GMan_Arm-L1.vtf
hl2\materials\PerfTest\gman\GMan_Arm-R1.vmt
hl2\materials\PerfTest\gman\GMan_Arm-R1.vtf
hl2\materials\PerfTest\gman\GMan_Back2.vmt
hl2\materials\PerfTest\gman\GMan_Back2.vtf
hl2\materials\PerfTest\gman\GMan_BArm-1.vmt
hl2\materials\PerfTest\gman\GMan_BArm-1.vtf
hl2\materials\PerfTest\gman\GMan_Case1.vmt
hl2\materials\PerfTest\gman\GMan_Case1.vtf
hl2\materials\PerfTest\gman\GMan_Cheek1.vmt
hl2\materials\PerfTest\gman\GMan_Cheek1.vtf
hl2\materials\PerfTest\gman\GMan_Collar1.vmt
hl2\materials\PerfTest\gman\GMan_Collar1.vtf
hl2\materials\PerfTest\gman\GMan_Face1.vmt
hl2\materials\PerfTest\gman\GMan_Face1.vtf
hl2\materials\PerfTest\gman\GMAN_Face2.vmt
hl2\materials\PerfTest\gman\GMAN_Face2.vtf
hl2\materials\PerfTest\gman\GMan_FootBtm1.vmt
hl2\materials\PerfTest\gman\GMan_FootBtm1.vtf
hl2\materials\PerfTest\gman\GMan_Hair1.vmt
hl2\materials\PerfTest\gman\GMan_Hair1.vtf
hl2\materials\PerfTest\gman\GMan_Hand-Btm1.vmt
hl2\materials\PerfTest\gman\GMan_Hand-Btm1.vtf
hl2\materials\PerfTest\gman\GMan_Hand-Top1.vmt
hl2\materials\PerfTest\gman\GMan_Hand-Top1.vtf
hl2\materials\PerfTest\gman\GMan_Mouth1.vmt
hl2\materials\PerfTest\gman\GMan_Mouth1.vtf
hl2\materials\PerfTest\gman\GMan_Pants1.vmt
hl2\materials\PerfTest\gman\GMan_Pants1.vtf
hl2\materials\PerfTest\gman\GMan_PantsBck1.vmt
hl2\materials\PerfTest\gman\GMan_PantsBck1.vtf
hl2\materials\PerfTest\gman\GMan_PantsBtm1.vmt
hl2\materials\PerfTest\gman\GMan_PantsBtm1.vtf
hl2\materials\PerfTest\gman\GMan_Pelvis1.vmt
hl2\materials\PerfTest\gman\GMan_Pelvis1.vtf
hl2\materials\PerfTest\gman\GMan_Shin1.vmt
hl2\materials\PerfTest\gman\GMan_Shin1.vtf
hl2\materials\PerfTest\gman\GMan_Shoe1.vmt
hl2\materials\PerfTest\gman\GMan_Shoe1.vtf
hl2\materials\PerfTest\gman\GMan_SlvTip1.vmt
hl2\materials\PerfTest\gman\GMan_SlvTip1.vtf
hl2\materials\PerfTest\gman\GMan_SuitTop1.vmt
hl2\materials\PerfTest\gman\GMan_SuitTop1.vtf
hl2\materials\PerfTest\gman\GMan_SuitTop2.vmt
hl2\materials\PerfTest\gman\GMan_SuitTop2.vtf
hl2\materials\PerfTest\gman\GMan_SuitTopBk1.vmt
hl2\materials\PerfTest\gman\GMan_SuitTopBk1.vtf
hl2\materials\PerfTest\gman\GMan_Teeth1.vmt
hl2\materials\PerfTest\gman\GMan_Teeth1.vtf
hl2\materials\PerfTest\gman\inside_1.vmt
hl2\materials\PerfTest\gman\inside_1.vtf
hl2\materials\PerfTest\gman\inside_2.vmt
hl2\materials\PerfTest\gman\inside_2.vtf
hl2\materials\PerfTest\loader\bicep_side.vmt
hl2\materials\PerfTest\loader\bicep_side.vtf
hl2\materials\PerfTest\loader\claw_outside.vmt
hl2\materials\PerfTest\loader\claw_outside.vtf
hl2\materials\PerfTest\loader\claw_top.vmt
hl2\materials\PerfTest\loader\claw_top.vtf
hl2\materials\PerfTest\loader\cockpit_side.vmt
hl2\materials\PerfTest\loader\cockpit_side.vtf
hl2\materials\PerfTest\loader\crate02.vmt
hl2\materials\PerfTest\loader\crate02.vtf
hl2\materials\PerfTest\loader\crate02b.vmt
hl2\materials\PerfTest\loader\crate02b.vtf
hl2\materials\PerfTest\loader\foot_side_bmp.vmt
hl2\materials\PerfTest\loader\foot_side_bmp.vtf
hl2\materials\PerfTest\loader\foot_top.vmt
hl2\materials\PerfTest\loader\foot_top.vtf
hl2\materials\PerfTest\loader\forearm_side.vmt
hl2\materials\PerfTest\loader\forearm_side.vtf
hl2\materials\PerfTest\loader\forearm_top.vmt
hl2\materials\PerfTest\loader\forearm_top.vtf
hl2\materials\PerfTest\loader\loaderCHROME.vmt
hl2\materials\PerfTest\loader\loaderCHROME.vtf
hl2\materials\PerfTest\loader\loader_base.vmt
hl2\materials\PerfTest\loader\loader_base.vtf
hl2\materials\PerfTest\loader\loader_base_panels.vmt
hl2\materials\PerfTest\loader\loader_base_panels.vtf
hl2\materials\PerfTest\loader\loader_base_sides.vmt
hl2\materials\PerfTest\loader\loader_base_sides.vtf
hl2\materials\PerfTest\loader\loader_body_hatch.vmt
hl2\materials\PerfTest\loader\loader_body_hatch.vtf
hl2\materials\PerfTest\loader\loader_body_side.vmt
hl2\materials\PerfTest\loader\loader_body_side.vtf
hl2\materials\PerfTest\loader\loader_darkCHROME.vmt
hl2\materials\PerfTest\loader\loader_darkCHROME.vtf
hl2\materials\PerfTest\loader\loader_head.vmt
hl2\materials\PerfTest\loader\loader_head.vtf
hl2\materials\PerfTest\loader\loader_leg_hydro.vmt
hl2\materials\PerfTest\loader\loader_leg_hydro.vtf
hl2\materials\PerfTest\loader\loader_leg_hydro_cut.vmt
hl2\materials\PerfTest\loader\loader_leg_hydro_cut.vtf
hl2\materials\PerfTest\loader\loader_leg_side1.vmt
hl2\materials\PerfTest\loader\loader_leg_side1.vtf
hl2\materials\PerfTest\loader\loader_steelchrome1.vmt
hl2\materials\PerfTest\loader\loader_steelchrome1.vtf
hl2\materials\PerfTest\loader\med_generic_inside.vmt
hl2\materials\PerfTest\loader\med_generic_inside.vtf
hl2\materials\PerfTest\loader\null.vmt
hl2\materials\PerfTest\loader\null.vtf
hl2\materials\PerfTest\loader\radiator.vmt
hl2\materials\PerfTest\loader\radiator.vtf
hl2\materials\PerfTest\loader\rubbersleeve.vmt
hl2\materials\PerfTest\loader\rubbersleeve.vtf
hl2\materials\PerfTest\loader\small_generic_outside.vmt
hl2\materials\PerfTest\loader\small_generic_outside.vtf

hl2\materials\skybox\sky_c17_04bk.vtf
hl2\materials\skybox\sky_c17_04dn.vtf
hl2\materials\skybox\sky_c17_04ft.vtf
hl2\materials\skybox\sky_c17_04lf.vtf
hl2\materials\skybox\sky_c17_04rt.vtf
hl2\materials\skybox\sky_c17_04up.vtf
hl2\materials\skybox\sky_perf01hdrbk.vmt
hl2\materials\skybox\sky_perf01hdrbk.vtf
hl2\materials\skybox\sky_perf01hdrdn.vmt
hl2\materials\skybox\sky_perf01hdrdn.vtf
hl2\materials\skybox\sky_perf01hdrft.vmt
hl2\materials\skybox\sky_perf01hdrft.vtf
hl2\materials\skybox\sky_perf01hdrlf.vmt
hl2\materials\skybox\sky_perf01hdrlf.vtf
hl2\materials\skybox\sky_perf01hdrrt.vmt
hl2\materials\skybox\sky_perf01hdrrt.vtf
hl2\materials\skybox\sky_perf01hdrup.vmt
hl2\materials\skybox\sky_perf01hdrup.vtf

hl2\models\alyx.dx7_2bone.vtx
hl2\models\alyx.dx80.vtx
hl2\models\alyx.jpg
hl2\models\alyx.mdl
hl2\models\alyx.phy

hl2\models\buggy.dx7_2bone.vtx
hl2\models\buggy.dx80.vtx
hl2\models\buggy.mdl
hl2\models\buggy.phy

hl2\models\Combine_Guard.jpg

hl2\models\Combine_Soldier.dx7_2bone.vtx
hl2\models\Combine_Soldier.dx80.vtx
hl2\models\Combine_Soldier.mdl
hl2\models\Combine_Soldier.phy

hl2\models\Combot.dx7_2bone.vtx
hl2\models\Combot.dx80.vtx
hl2\models\Combot.mdl

hl2\models\cremator_body.jpg

hl2\models\dog.dx7_2bone.vtx
hl2\models\dog.dx80.vtx
hl2\models\dog.jpg
hl2\models\dog.mdl
hl2\models\dog.phy

hl2\models\E3hydra.jpg

hl2\models\error.dx7_2bone.vtx
hl2\models\error.dx80.vtx
hl2\models\error.mdl

hl2\models\fassassin.jpg

hl2\models\gunship.dx7_2bone.vtx
hl2\models\gunship.dx80.vtx
hl2\models\gunship.mdl
hl2\models\gunship.phy

hl2\models\headcrab.jpg

hl2\models\headcrabclassic.dx7_2bone.vtx
hl2\models\headcrabclassic.dx80.vtx
hl2\models\headcrabclassic.mdl
hl2\models\headcrabclassic.phy

hl2\models\monk.dx7_2bone.vtx
hl2\models\monk.dx80.vtx
hl2\models\monk.mdl
hl2\models\monk.phy

hl2\models\odell.dx7_2bone.vtx
hl2\models\odell.dx80.vtx
hl2\models\Odell.mdl
hl2\models\odell.phy

hl2\models\Police.dx7_2bone.vtx
hl2\models\Police.dx80.vtx
hl2\models\Police.mdl
hl2\models\Police.phy
hl2\models\Police_Cheaple.jpg

hl2\models\stalker.jpg

hl2\models\Combine_Room\combine_panel001temp.jpg
hl2\models\Combine_turrets\Floor_turret.jpg
hl2\models\Cranes\crane_docks.dx7_2bone.vtx
hl2\models\Cranes\crane_docks.dx80.vtx
hl2\models\Cranes\crane_docks.mdl
hl2\models\Cranes\crane_docks.phy

hl2\models\editor\Air_node.dx7_2bone.vtx
hl2\models\editor\Air_node.dx80.vtx
hl2\models\editor\Air_node.mdl
hl2\models\editor\Air_node_hint.dx7_2bone.vtx
hl2\models\editor\Air_node_hint.dx80.vtx
hl2\models\editor\Air_node_hint.mdl

hl2\models\Fire_equipment\W_WeldTank2.jpg

hl2\models\Gibs\wood_gib01a.dx7_2bone.vtx
hl2\models\Gibs\wood_gib01a.dx80.vtx
hl2\models\Gibs\wood_gib01a.mdl
hl2\models\Gibs\wood_gib01a.phy
hl2\models\Gibs\wood_gib01b.dx7_2bone.vtx
hl2\models\Gibs\wood_gib01b.dx80.vtx
hl2\models\Gibs\wood_gib01b.mdl
hl2\models\Gibs\wood_gib01b.phy
hl2\models\Gibs\wood_gib01c.dx7_2bone.vtx
hl2\models\Gibs\wood_gib01c.dx80.vtx
hl2\models\Gibs\wood_gib01c.mdl
hl2\models\Gibs\wood_gib01c.phy
hl2\models\Gibs\wood_gib01d.dx7_2bone.vtx
hl2\models\Gibs\wood_gib01d.dx80.vtx
hl2\models\Gibs\wood_gib01d.mdl
hl2\models\Gibs\wood_gib01d.phy
hl2\models\Gibs\wood_gib01e.dx7_2bone.vtx
hl2\models\Gibs\wood_gib01e.dx80.vtx
hl2\models\Gibs\wood_gib01e.mdl
hl2\models\Gibs\wood_gib01e.phy

hl2\models\Humans\Male_04.dx7_2bone.vtx
hl2\models\Humans\Male_04.dx80.vtx
hl2\models\Humans\Male_04.mdl
hl2\models\Humans\Male_04.phy
hl2\models\Humans\Male_05.dx7_2bone.vtx
hl2\models\Humans\Male_05.dx80.vtx
hl2\models\Humans\Male_05.mdl
hl2\models\Humans\Male_05.phy

hl2\models\Humans\male_08.jpg

hl2\models\Items\ammoCrate_Bullets.dx7_2bone.vtx
hl2\models\Items\ammoCrate_Bullets.dx80.vtx
hl2\models\Items\ammoCrate_Bullets.mdl
hl2\models\Items\ammoCrate_Bullets.phy
hl2\models\Items\ammoCrate_Rockets.dx7_2bone.vtx
hl2\models\Items\ammoCrate_Rockets.dx80.vtx
hl2\models\Items\ammoCrate_Rockets.mdl
hl2\models\Items\ammoCrate_Rockets.phy

hl2\models\Items\battery.dx7_2bone.vtx
hl2\models\Items\battery.dx80.vtx
hl2\models\Items\battery.mdl
hl2\models\Items\battery.phy

hl2\models\Items\HealthKit.dx7_2bone.vtx
hl2\models\Items\HealthKit.dx80.vtx
hl2\models\Items\HealthKit.mdl
hl2\models\Items\healthKit.phy

hl2\models\Items\ML_Grenade.dx7_2bone.vtx
hl2\models\Items\ML_Grenade.dx80.vtx
hl2\models\Items\ML_Grenade.mdl
hl2\models\Items\ml_grenade.phy

hl2\models\PerfTest\gman.dx7_2bone.vtx
hl2\models\PerfTest\gman.dx80.vtx
hl2\models\PerfTest\gman.mdl

hl2\models\PerfTest\Grass_tuft_001.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_001.dx80.vtx
hl2\models\PerfTest\Grass_tuft_001.jpg
hl2\models\PerfTest\Grass_tuft_001.mdl
hl2\models\PerfTest\Grass_tuft_001a.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_001a.dx80.vtx
hl2\models\PerfTest\Grass_tuft_001a.jpg
hl2\models\PerfTest\Grass_tuft_001a.mdl
hl2\models\PerfTest\Grass_tuft_001b.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_001b.dx80.vtx
hl2\models\PerfTest\Grass_tuft_001b.jpg
hl2\models\PerfTest\Grass_tuft_001b.mdl
hl2\models\PerfTest\Grass_tuft_003a.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_003a.dx80.vtx
hl2\models\PerfTest\Grass_tuft_003a.jpg
hl2\models\PerfTest\Grass_tuft_003a.mdl
hl2\models\PerfTest\Grass_tuft_004a.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_004a.dx80.vtx
hl2\models\PerfTest\Grass_tuft_004a.jpg
hl2\models\PerfTest\Grass_tuft_004a.mdl
hl2\models\PerfTest\Grass_tuft_004b.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_004b.dx80.vtx
hl2\models\PerfTest\Grass_tuft_004b.jpg
hl2\models\PerfTest\Grass_tuft_004b.mdl
hl2\models\PerfTest\Grass_tuft_004c.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_004c.dx80.vtx
hl2\models\PerfTest\Grass_tuft_004c.jpg
hl2\models\PerfTest\Grass_tuft_004c.mdl
hl2\models\PerfTest\Grass_tuft_004d.dx7_2bone.vtx
hl2\models\PerfTest\Grass_tuft_004d.dx80.vtx
hl2\models\PerfTest\Grass_tuft_004d.jpg
hl2\models\PerfTest\Grass_tuft_004d.mdl
hl2\models\PerfTest\loader.dx7_2bone.vtx
hl2\models\PerfTest\loader.dx80.vtx
hl2\models\PerfTest\loader.mdl
hl2\models\PerfTest\loader_Static.dx7_2bone.vtx
hl2\models\PerfTest\loader_Static.dx80.vtx
hl2\models\PerfTest\loader_Static.mdl
hl2\models\PerfTest\rocksground01a.dx7_2bone.vtx
hl2\models\PerfTest\rocksground01a.dx80.vtx
hl2\models\PerfTest\rocksground01a.jpg
hl2\models\PerfTest\rocksground01a.mdl
hl2\models\PerfTest\rocksground01a.phy
hl2\models\PerfTest\rocksground01b.dx7_2bone.vtx
hl2\models\PerfTest\rocksground01b.dx80.vtx
hl2\models\PerfTest\rocksground01b.jpg
hl2\models\PerfTest\rocksground01b.mdl
hl2\models\PerfTest\rocksground01b.phy
hl2\models\PerfTest\rocksground01c.dx7_2bone.vtx
hl2\models\PerfTest\rocksground01c.dx80.vtx
hl2\models\PerfTest\rocksground01c.mdl
hl2\models\PerfTest\rocksground01d.dx7_2bone.vtx
hl2\models\PerfTest\rocksground01d.dx80.vtx
hl2\models\PerfTest\rocksground01d.mdl
hl2\models\PerfTest\rocksground01e.dx7_2bone.vtx
hl2\models\PerfTest\rocksground01e.dx80.vtx
hl2\models\PerfTest\rocksground01e.mdl
hl2\models\PerfTest\rocksground02a.dx7_2bone.vtx
hl2\models\PerfTest\rocksground02a.dx80.vtx
hl2\models\PerfTest\rocksground02a.jpg
hl2\models\PerfTest\rocksground02a.mdl
hl2\models\PerfTest\rocksground02b.dx7_2bone.vtx
hl2\models\PerfTest\rocksground02b.dx80.vtx
hl2\models\PerfTest\rocksground02b.jpg
hl2\models\PerfTest\rocksground02b.mdl
hl2\models\PerfTest\rocksground02c.dx7_2bone.vtx
hl2\models\PerfTest\rocksground02c.dx80.vtx
hl2\models\PerfTest\rocksground02c.jpg
hl2\models\PerfTest\rocksground02c.mdl

hl2\models\props_borealis\engine_fan001.jpg
hl2\models\props_borealis\handrail02_long_end01.jpg
hl2\models\props_borealis\Icebergs01c.jpg
hl2\models\props_borealis\panel02.jpg
hl2\models\props_borealis\pipe01_yjoint02.jpg
hl2\models\props_borealis\pipe02_lcurve01_short.jpg
hl2\models\props_borealis\pipe03_yjoint01.jpg
hl2\models\props_borealis\smokestack01.jpg

hl2\models\props_buildings\CollapsedBuilding01a.dx7_2bone.vtx
hl2\models\props_buildings\CollapsedBuilding01a.dx80.vtx
hl2\models\props_buildings\CollapsedBuilding01a.mdl
hl2\models\props_buildings\CollapsedBuilding01a.phy
hl2\models\props_buildings\CollapsedBuilding01aWall.dx7_2bone.vtx
hl2\models\props_buildings\CollapsedBuilding01aWall.dx80.vtx
hl2\models\props_buildings\CollapsedBuilding01aWall.mdl
hl2\models\props_buildings\CollapsedBuilding01aWall.phy
hl2\models\props_buildings\watertower_002a.dx7_2bone.vtx
hl2\models\props_buildings\watertower_002a.dx80.vtx
hl2\models\props_buildings\watertower_002a.mdl
hl2\models\props_buildings\watertower_002a.phy

hl2\models\props_c17\artpedestal01.jpg
hl2\models\props_c17\barrel09a.jpg
hl2\models\props_c17\BriefCase001a.jpg
hl2\models\props_c17\canisterchunk01e.dx7_2bone.vtx
hl2\models\props_c17\canisterchunk01e.dx80.vtx
hl2\models\props_c17\canisterchunk01e.mdl
hl2\models\props_c17\canisterchunk01e.phy
hl2\models\props_c17\canister_propanechunk02a.jpg
hl2\models\props_c17\chimney01.jpg
hl2\models\props_c17\fountain_01.dx7_2bone.vtx
hl2\models\props_c17\fountain_01.dx80.vtx
hl2\models\props_c17\fountain_01.jpg
hl2\models\props_c17\fountain_01.mdl
hl2\models\props_c17\fountain_01.phy
hl2\models\props_c17\frame01.jpg
hl2\models\props_c17\FurnitureDrawer001a.jpg
hl2\models\props_c17\FurnitureMattress001a.jpg
hl2\models\props_c17\FurnitureRadiator001a.dx7_2bone.vtx
hl2\models\props_c17\FurnitureRadiator001a.dx80.vtx
hl2\models\props_c17\FurnitureRadiator001a.mdl
hl2\models\props_c17\FurnitureRadiator001a.phy
hl2\models\props_c17\FurnitureShelf001b.jpg
hl2\models\props_c17\FurnitureWashingmachine001a.jpg
hl2\models\props_c17\Gasmeter001a.dx7_2bone.vtx
hl2\models\props_c17\Gasmeter001a.dx80.vtx
hl2\models\props_c17\Gasmeter001a.mdl
hl2\models\props_c17\Gasmeter001a.phy
hl2\models\props_c17\Gasmeter002a.dx7_2bone.vtx
hl2\models\props_c17\Gasmeter002a.dx80.vtx
hl2\models\props_c17\Gasmeter002a.jpg
hl2\models\props_c17\Gasmeter002a.mdl
hl2\models\props_c17\Gasmeter002a.phy
hl2\models\props_c17\Gasmeter003a.dx7_2bone.vtx
hl2\models\props_c17\Gasmeter003a.dx80.vtx
hl2\models\props_c17\Gasmeter003a.mdl
hl2\models\props_c17\Gasmeter003a.phy
hl2\models\props_c17\Handrail01_corner.jpg
hl2\models\props_c17\Handrail04_brokenCorner.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_brokenCorner.dx80.vtx
hl2\models\props_c17\Handrail04_brokenCorner.mdl
hl2\models\props_c17\Handrail04_brokenCorner.phy
hl2\models\props_c17\Handrail04_brokenLong.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_brokenLong.dx80.vtx
hl2\models\props_c17\Handrail04_brokenLong.mdl
hl2\models\props_c17\Handrail04_brokenLong.phy
hl2\models\props_c17\Handrail04_brokenSingleRise.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_brokenSingleRise.dx80.vtx
hl2\models\props_c17\Handrail04_brokenSingleRise.mdl
hl2\models\props_c17\Handrail04_brokenSingleRise.phy
hl2\models\props_c17\Handrail04_corner.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_corner.dx80.vtx
hl2\models\props_c17\Handrail04_corner.mdl
hl2\models\props_c17\Handrail04_corner.phy
hl2\models\props_c17\Handrail04_DoubleRise.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_DoubleRise.dx80.vtx
hl2\models\props_c17\Handrail04_DoubleRise.mdl
hl2\models\props_c17\Handrail04_DoubleRise.phy
hl2\models\props_c17\Handrail04_long.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_long.dx80.vtx
hl2\models\props_c17\Handrail04_long.mdl
hl2\models\props_c17\Handrail04_long.phy
hl2\models\props_c17\Handrail04_Medium.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_Medium.dx80.vtx
hl2\models\props_c17\Handrail04_Medium.mdl
hl2\models\props_c17\Handrail04_Medium.phy
hl2\models\props_c17\Handrail04_SingleRise.dx7_2bone.vtx
hl2\models\props_c17\Handrail04_SingleRise.dx80.vtx
hl2\models\props_c17\Handrail04_SingleRise.mdl
hl2\models\props_c17\Handrail04_SingleRise.phy
hl2\models\props_c17\light_domelight02_on.jpg
hl2\models\props_c17\light_globelight01_off.jpg
hl2\models\props_c17\light_lightbare01_off.jpg
hl2\models\props_c17\lockerdoor003a.jpg
hl2\models\props_c17\oildrum001.dx7_2bone.vtx
hl2\models\props_c17\oildrum001.dx80.vtx
hl2\models\props_c17\oildrum001.mdl
hl2\models\props_c17\oildrum001.phy
hl2\models\props_c17\oildrum001_explosive.dx7_2bone.vtx
hl2\models\props_c17\oildrum001_explosive.dx80.vtx
hl2\models\props_c17\oildrum001_explosive.jpg
hl2\models\props_c17\oildrum001_explosive.mdl
hl2\models\props_c17\oildrum001_explosive.phy
hl2\models\props_c17\oildrumchunk01a.jpg
hl2\models\props_c17\oildrumchunk01b.jpg
hl2\models\props_c17\oildrumchunk01c.jpg
hl2\models\props_c17\oildrumchunk01d.jpg
hl2\models\props_c17\oildrumchunk01e.jpg
hl2\models\props_c17\oildrumchunk01f.jpg
hl2\models\props_c17\oildrumchunk01g.jpg
hl2\models\props_c17\oildrumchunk01h.jpg
hl2\models\props_c17\oildrumchunk01i.jpg
hl2\models\props_c17\oildrumchunk01j.jpg
hl2\models\props_c17\oildrumchunk01k.jpg
hl2\models\props_c17\oil_drumchunk001a.jpg
hl2\models\props_c17\oil_drumchunk001b.jpg
hl2\models\props_c17\oil_drumchunk001c.jpg
hl2\models\props_c17\oil_drumchunk001d.jpg
hl2\models\props_c17\overpass_001a.dx7_2bone.vtx
hl2\models\props_c17\overpass_001a.dx80.vtx
hl2\models\props_c17\overpass_001a.jpg
hl2\models\props_c17\overpass_001a.mdl
hl2\models\props_c17\overpass_001a.phy
hl2\models\props_c17\overpass_001b.dx7_2bone.vtx
hl2\models\props_c17\overpass_001b.dx80.vtx
hl2\models\props_c17\overpass_001b.jpg
hl2\models\props_c17\overpass_001b.mdl
hl2\models\props_c17\overpass_001b.phy
hl2\models\props_c17\pipe01_connector01.jpg
hl2\models\props_c17\pipe02_lcurve02_long.jpg
hl2\models\props_c17\pulleywheels_small01.jpg
hl2\models\props_c17\streetsign001c.jpg
hl2\models\props_c17\tank_cooling01a.jpg
hl2\models\props_c17\Trap_Scythe01a.jpg
hl2\models\props_c17\truck01.dx7_2bone.vtx
hl2\models\props_c17\truck01.dx80.vtx
hl2\models\props_c17\truck01.mdl
hl2\models\props_c17\truck01.phy
hl2\models\props_c17\truss01.jpg
hl2\models\props_c17\truss02f.mdl
hl2\models\props_c17\truss02f.phy
hl2\models\props_c17\utilityconnecter006.jpg
hl2\models\props_c17\utilityconnecter006d.jpg

hl2\models\props_citizen_tech\claw001_joint02.jpg

hl2\models\props_combine\combineconnector003.jpg
hl2\models\props_combine\CombineGate001a.jpg
hl2\models\props_combine\CombineInnerwallCluster1024_001b.jpg
hl2\models\props_combine\CombineInnerwallCluster1024_002b.jpg
hl2\models\props_combine\CombineInnerwallCluster1024_003b.jpg
hl2\models\props_combine\combine_barricade_bracket01a.jpg
hl2\models\props_combine\combine_barricade_bracket01b.jpg
hl2\models\props_combine\combine_barricade_bracket02a.jpg
hl2\models\props_combine\combine_barricade_bracket02b.jpg
hl2\models\props_combine\combine_barricade_med01a.jpg
hl2\models\props_combine\combine_barricade_med01b.jpg
hl2\models\props_combine\combine_barricade_med02a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_med02a.dx80.vtx
hl2\models\props_combine\combine_barricade_med02a.jpg
hl2\models\props_combine\combine_barricade_med02a.mdl
hl2\models\props_combine\combine_barricade_med02a.phy
hl2\models\props_combine\combine_barricade_med02b.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_med02b.dx80.vtx
hl2\models\props_combine\combine_barricade_med02b.jpg
hl2\models\props_combine\combine_barricade_med02b.mdl
hl2\models\props_combine\combine_barricade_med02b.phy
hl2\models\props_combine\combine_barricade_med03a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_med03a.dx80.vtx
hl2\models\props_combine\combine_barricade_med03a.jpg
hl2\models\props_combine\combine_barricade_med03a.mdl
hl2\models\props_combine\combine_barricade_med03a.phy
hl2\models\props_combine\combine_barricade_med03b.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_med03b.dx80.vtx
hl2\models\props_combine\combine_barricade_med03b.jpg
hl2\models\props_combine\combine_barricade_med03b.mdl
hl2\models\props_combine\combine_barricade_med03b.phy
hl2\models\props_combine\combine_barricade_med04a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_med04a.dx80.vtx
hl2\models\props_combine\combine_barricade_med04a.jpg
hl2\models\props_combine\combine_barricade_med04a.mdl
hl2\models\props_combine\combine_barricade_med04a.phy
hl2\models\props_combine\combine_barricade_med04b.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_med04b.dx80.vtx
hl2\models\props_combine\combine_barricade_med04b.jpg
hl2\models\props_combine\combine_barricade_med04b.mdl
hl2\models\props_combine\combine_barricade_med04b.phy
hl2\models\props_combine\combine_barricade_short01a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_short01a.dx80.vtx
hl2\models\props_combine\combine_barricade_short01a.jpg
hl2\models\props_combine\combine_barricade_short01a.mdl
hl2\models\props_combine\combine_barricade_short01a.phy
hl2\models\props_combine\combine_barricade_short02a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_short02a.dx80.vtx
hl2\models\props_combine\combine_barricade_short02a.jpg
hl2\models\props_combine\combine_barricade_short02a.mdl
hl2\models\props_combine\combine_barricade_short02a.phy
hl2\models\props_combine\combine_barricade_short03a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_short03a.dx80.vtx
hl2\models\props_combine\combine_barricade_short03a.jpg
hl2\models\props_combine\combine_barricade_short03a.mdl
hl2\models\props_combine\combine_barricade_short03a.phy
hl2\models\props_combine\combine_barricade_tall01a.jpg
hl2\models\props_combine\combine_barricade_tall01b.jpg
hl2\models\props_combine\combine_barricade_tall02a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_tall02a.dx80.vtx
hl2\models\props_combine\combine_barricade_tall02a.jpg
hl2\models\props_combine\combine_barricade_tall02a.mdl
hl2\models\props_combine\combine_barricade_tall02a.phy
hl2\models\props_combine\combine_barricade_tall02b.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_tall02b.dx80.vtx
hl2\models\props_combine\combine_barricade_tall02b.jpg
hl2\models\props_combine\combine_barricade_tall02b.mdl
hl2\models\props_combine\combine_barricade_tall02b.phy
hl2\models\props_combine\combine_barricade_tall03a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_tall03a.dx80.vtx
hl2\models\props_combine\combine_barricade_tall03a.jpg
hl2\models\props_combine\combine_barricade_tall03a.mdl
hl2\models\props_combine\combine_barricade_tall03a.phy
hl2\models\props_combine\combine_barricade_tall03b.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_tall03b.dx80.vtx
hl2\models\props_combine\combine_barricade_tall03b.jpg
hl2\models\props_combine\combine_barricade_tall03b.mdl
hl2\models\props_combine\combine_barricade_tall03b.phy
hl2\models\props_combine\combine_barricade_tall04a.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_tall04a.dx80.vtx
hl2\models\props_combine\combine_barricade_tall04a.jpg
hl2\models\props_combine\combine_barricade_tall04a.mdl
hl2\models\props_combine\combine_barricade_tall04a.phy
hl2\models\props_combine\combine_barricade_tall04b.dx7_2bone.vtx
hl2\models\props_combine\combine_barricade_tall04b.dx80.vtx
hl2\models\props_combine\combine_barricade_tall04b.jpg
hl2\models\props_combine\combine_barricade_tall04b.mdl
hl2\models\props_combine\combine_barricade_tall04b.phy
hl2\models\props_combine\combine_booth_med01a.dx7_2bone.vtx
hl2\models\props_combine\combine_booth_med01a.dx80.vtx
hl2\models\props_combine\combine_booth_med01a.jpg
hl2\models\props_combine\combine_booth_med01a.mdl
hl2\models\props_combine\combine_booth_med01a.phy
hl2\models\props_combine\combine_booth_short01a.jpg
hl2\models\props_combine\combine_booth_tall01a.dx7_2bone.vtx
hl2\models\props_combine\combine_booth_tall01a.dx80.vtx
hl2\models\props_combine\combine_booth_tall01a.jpg
hl2\models\props_combine\combine_booth_tall01a.mdl
hl2\models\props_combine\combine_booth_tall01a.phy
hl2\models\props_combine\combine_fence01a.dx80.vtx
hl2\models\props_combine\combine_fence01a.jpg
hl2\models\props_combine\combine_fence01a.mdl
hl2\models\props_combine\combine_fence01a.phy
hl2\models\props_combine\combine_fence01b.dx7_2bone.vtx
hl2\models\props_combine\combine_fence01b.dx80.vtx
hl2\models\props_combine\combine_fence01b.jpg
hl2\models\props_combine\combine_fence01b.mdl
hl2\models\props_combine\combine_fence01b.phy
hl2\models\props_combine\combine_gate_citizen01a.dx7_2bone.vtx
hl2\models\props_combine\combine_gate_citizen01a.dx80.vtx
hl2\models\props_combine\combine_gate_citizen01a.jpg
hl2\models\props_combine\combine_gate_citizen01a.mdl
hl2\models\props_combine\combine_gate_citizen01a.phy
hl2\models\props_combine\combine_gate_vehicle01a.jpg
hl2\models\props_debris\barricade_short01a.dx7_2bone.vtx
hl2\models\props_debris\barricade_short01a.dx80.vtx
hl2\models\props_debris\barricade_short01a.mdl
hl2\models\props_debris\barricade_short01a.phy
hl2\models\props_debris\barricade_short02a.dx7_2bone.vtx
hl2\models\props_debris\barricade_short02a.dx80.vtx
hl2\models\props_debris\barricade_short02a.mdl
hl2\models\props_debris\barricade_short02a.phy
hl2\models\props_debris\barricade_short03a.dx7_2bone.vtx
hl2\models\props_debris\barricade_short03a.dx80.vtx
hl2\models\props_debris\barricade_short03a.mdl
hl2\models\props_debris\barricade_short03a.phy
hl2\models\props_debris\barricade_short04a.dx7_2bone.vtx
hl2\models\props_debris\barricade_short04a.dx80.vtx
hl2\models\props_debris\barricade_short04a.mdl
hl2\models\props_debris\barricade_short04a.phy
hl2\models\props_debris\barricade_tall01a.dx7_2bone.vtx
hl2\models\props_debris\barricade_tall01a.dx80.vtx
hl2\models\props_debris\barricade_tall01a.mdl
hl2\models\props_debris\barricade_tall01a.phy
hl2\models\props_debris\barricade_tall02a.dx7_2bone.vtx
hl2\models\props_debris\barricade_tall02a.dx80.vtx
hl2\models\props_debris\barricade_tall02a.mdl
hl2\models\props_debris\barricade_tall02a.phy
hl2\models\props_debris\barricade_tall03a.dx7_2bone.vtx
hl2\models\props_debris\barricade_tall03a.dx80.vtx
hl2\models\props_debris\barricade_tall03a.mdl
hl2\models\props_debris\barricade_tall03a.phy
hl2\models\props_debris\barricade_tall04a.dx7_2bone.vtx
hl2\models\props_debris\barricade_tall04a.dx80.vtx
hl2\models\props_debris\barricade_tall04a.mdl
hl2\models\props_debris\barricade_tall04a.phy

hl2\models\props_debris\concrete_debris128Pile001a.dx7_2bone.vtx
hl2\models\props_debris\concrete_debris128Pile001a.dx80.vtx
hl2\models\props_debris\concrete_debris128Pile001a.mdl
hl2\models\props_debris\concrete_debris128Pile001a.phy
hl2\models\props_debris\concrete_debris128Pile001b.dx7_2bone.vtx
hl2\models\props_debris\concrete_debris128Pile001b.dx80.vtx
hl2\models\props_debris\concrete_debris128Pile001b.mdl
hl2\models\props_debris\concrete_debris128Pile001b.phy
hl2\models\props_debris\concrete_debris256Pile001a.dx7_2bone.vtx
hl2\models\props_debris\concrete_debris256Pile001a.dx80.vtx
hl2\models\props_debris\concrete_debris256Pile001a.mdl
hl2\models\props_debris\concrete_debris256Pile001a.phy

hl2\models\props_docks\dock01_cleat01a.dx7_2bone.vtx
hl2\models\props_docks\dock01_cleat01a.dx80.vtx
hl2\models\props_docks\dock01_cleat01a.mdl
hl2\models\props_docks\dock01_cleat01a.phy
hl2\models\props_docks\dock02_polecluster01a.dx7_2bone.vtx
hl2\models\props_docks\dock02_polecluster01a.dx80.vtx
hl2\models\props_docks\dock02_polecluster01a.mdl
hl2\models\props_docks\dock02_polecluster01a.phy
hl2\models\props_docks\dock02_polecluster01a_256.dx7_2bone.vtx
hl2\models\props_docks\dock02_polecluster01a_256.dx80.vtx
hl2\models\props_docks\dock02_polecluster01a_256.mdl
hl2\models\props_docks\dock02_polecluster01a_256.phy
hl2\models\props_docks\prefab_piling01a.jpg

hl2\models\props_foliage\driftwood_03a.jpg
hl2\models\props_foliage\treepine01c.jpg

hl2\models\props_junk\TrashDumpster02.dx7_2bone.vtx
hl2\models\props_junk\TrashDumpster02.dx80.vtx
hl2\models\props_junk\TrashDumpster02.mdl
hl2\models\props_junk\TrashDumpster02.phy
hl2\models\props_junk\TrashDumpster02b.dx7_2bone.vtx
hl2\models\props_junk\TrashDumpster02b.dx80.vtx
hl2\models\props_junk\TrashDumpster02b.mdl
hl2\models\props_junk\TrashDumpster02b.phy
hl2\models\props_junk\wood_crate001a.dx7_2bone.vtx
hl2\models\props_junk\wood_crate001a.dx80.vtx
hl2\models\props_junk\wood_crate001a.mdl
hl2\models\props_junk\wood_crate001a.phy

hl2\models\props_pipes\Gutter_576_001a.dx7_2bone.vtx
hl2\models\props_pipes\Gutter_576_001a.dx80.vtx
hl2\models\props_pipes\Gutter_576_001a.mdl
hl2\models\props_pipes\Gutter_576_001a.phy
hl2\models\props_pipes\Gutter_704_001a.dx7_2bone.vtx
hl2\models\props_pipes\Gutter_704_001a.dx80.vtx
hl2\models\props_pipes\Gutter_704_001a.mdl
hl2\models\props_pipes\Gutter_704_001a.phy
hl2\models\props_pipes\PipeSet02d_64_001a.jpg
hl2\models\props_pipes\PipeSet08d_256_001a.jpg
hl2\models\props_pipes\PipeSet32d_50_001a.jpg

hl2\models\props_rooftop\AntennaClusters01a.dx7_2bone.vtx
hl2\models\props_rooftop\AntennaClusters01a.dx80.vtx
hl2\models\props_rooftop\AntennaClusters01a.mdl
hl2\models\props_rooftop\AntennaClusters01a.phy
hl2\models\props_rooftop\chimneypipe01c.jpg
hl2\models\props_rooftop\railing01a.jpg
hl2\models\props_rooftop\RooftopCluser06a.jpg
hl2\models\props_rooftop\RooftopCluser07a.dx7_2bone.vtx
hl2\models\props_rooftop\RooftopCluser07a.dx80.vtx
hl2\models\props_rooftop\RooftopCluser07a.jpg
hl2\models\props_rooftop\RooftopCluser07a.mdl
hl2\models\props_rooftop\RooftopCluser07a.phy
hl2\models\props_rooftop\RooftopCluser08a.dx7_2bone.vtx
hl2\models\props_rooftop\RooftopCluser08a.dx80.vtx
hl2\models\props_rooftop\RooftopCluser08a.mdl
hl2\models\props_rooftop\RooftopCluser09a.dx7_2bone.vtx
hl2\models\props_rooftop\RooftopCluser09a.dx80.vtx
hl2\models\props_rooftop\RooftopCluser09a.mdl
hl2\models\props_rooftop\roof_vent001.dx7_2bone.vtx
hl2\models\props_rooftop\roof_vent001.dx80.vtx
hl2\models\props_rooftop\roof_vent001.mdl
hl2\models\props_rooftop\roof_vent001.phy
hl2\models\props_rooftop\roof_vent002.dx7_2bone.vtx
hl2\models\props_rooftop\roof_vent002.dx80.vtx
hl2\models\props_rooftop\roof_vent002.mdl
hl2\models\props_rooftop\roof_vent002.phy
hl2\models\props_rooftop\roof_vent003.dx7_2bone.vtx
hl2\models\props_rooftop\roof_vent003.dx80.vtx
hl2\models\props_rooftop\roof_vent003.mdl
hl2\models\props_rooftop\roof_vent003.phy
hl2\models\props_rooftop\roof_vent004.dx7_2bone.vtx
hl2\models\props_rooftop\roof_vent004.dx80.vtx
hl2\models\props_rooftop\roof_vent004.mdl
hl2\models\props_rooftop\roof_vent004.phy

hl2\models\props_skybox\coast01.dx7_2bone.vtx
hl2\models\props_skybox\coast01.dx80.vtx
hl2\models\props_skybox\coast01.mdl

hl2\models\props_trainstation\TrackSign07.jpg

hl2\models\props_vehicles\car001a_hatchback.dx7_2bone.vtx
hl2\models\props_vehicles\car001a_hatchback.dx80.vtx
hl2\models\props_vehicles\car001a_hatchback.jpg
hl2\models\props_vehicles\car001a_hatchback.mdl
hl2\models\props_vehicles\car001a_hatchback.phy
hl2\models\props_vehicles\car001a_phy.dx7_2bone.vtx
hl2\models\props_vehicles\car001a_phy.dx80.vtx
hl2\models\props_vehicles\car001a_phy.mdl
hl2\models\props_vehicles\car001a_phy.phy
hl2\models\props_vehicles\car001b_hatchback.dx7_2bone.vtx
hl2\models\props_vehicles\car001b_hatchback.dx80.vtx
hl2\models\props_vehicles\car001b_hatchback.mdl
hl2\models\props_vehicles\car001b_hatchback.phy
hl2\models\props_vehicles\car001b_phy.dx7_2bone.vtx
hl2\models\props_vehicles\car001b_phy.dx80.vtx
hl2\models\props_vehicles\car001b_phy.mdl
hl2\models\props_vehicles\car001b_phy.phy
hl2\models\props_vehicles\tanker001a.dx7_2bone.vtx
hl2\models\props_vehicles\tanker001a.dx80.vtx
hl2\models\props_vehicles\tanker001a.mdl
hl2\models\props_vehicles\tanker001a.phy
hl2\models\props_vehicles\truck001a_cab_phy.jpg
hl2\models\props_vehicles\truck002a_cab.dx7_2bone.vtx
hl2\models\props_vehicles\truck002a_cab.dx80.vtx
hl2\models\props_vehicles\truck002a_cab.mdl
hl2\models\props_vehicles\truck002a_cab.phy

hl2\models\props_wasteland\antlionhill.dx7_2bone.vtx
hl2\models\props_wasteland\antlionhill.dx80.vtx
hl2\models\props_wasteland\antlionhill.mdl
hl2\models\props_wasteland\antlionhill.phy
hl2\models\props_wasteland\boat_fishing02a.jpg
hl2\models\props_wasteland\bridge_internals03.jpg
hl2\models\props_wasteland\controlroom_monitor001b.dx7_2bone.vtx
hl2\models\props_wasteland\controlroom_monitor001b.dx80.vtx
hl2\models\props_wasteland\controlroom_monitor001b.mdl
hl2\models\props_wasteland\controlroom_monitor001b.phy
hl2\models\props_wasteland\controlroom_phone001a.dx7_2bone.vtx
hl2\models\props_wasteland\controlroom_phone001a.dx80.vtx
hl2\models\props_wasteland\controlroom_phone001a.mdl
hl2\models\props_wasteland\controlroom_phone001a.phy
hl2\models\props_wasteland\controlroom_phone001b.dx7_2bone.vtx
hl2\models\props_wasteland\controlroom_phone001b.dx80.vtx
hl2\models\props_wasteland\controlroom_phone001b.mdl
hl2\models\props_wasteland\controlroom_phone001b.phy
hl2\models\props_wasteland\controlroom_storagecloset001a.dx7_2bone.vtx
hl2\models\props_wasteland\controlroom_storagecloset001a.dx80.vtx
hl2\models\props_wasteland\controlroom_storagecloset001a.mdl
hl2\models\props_wasteland\controlroom_storagecloset001a.phy
hl2\models\props_wasteland\kitchen_shelf001a.jpg
hl2\models\props_wasteland\kitchen_shelf002a.jpg
hl2\models\props_wasteland\lighthouse_fresnel_light.jpg
hl2\models\props_wasteland\lighthouse_stairs.jpg
hl2\models\props_wasteland\Plaster_Wall029c_Window.dx7_2bone.vtx
hl2\models\props_wasteland\Plaster_Wall029c_Window.dx80.vtx
hl2\models\props_wasteland\Plaster_Wall029c_Window.jpg
hl2\models\props_wasteland\Plaster_Wall029c_Window.mdl
hl2\models\props_wasteland\Plaster_Wall029c_Window.phy
hl2\models\props_wasteland\rockcliff_cluster01a.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster01a.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster01a.mdl
hl2\models\props_wasteland\rockcliff_cluster01a.phy
hl2\models\props_wasteland\rockcliff_cluster01b.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster01b.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster01b.mdl
hl2\models\props_wasteland\rockcliff_cluster01b.phy
hl2\models\props_wasteland\rockcliff_cluster02a.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster02a.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster02a.mdl
hl2\models\props_wasteland\rockcliff_cluster02a.phy
hl2\models\props_wasteland\rockcliff_cluster02b.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster02b.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster02b.mdl
hl2\models\props_wasteland\rockcliff_cluster02b.phy
hl2\models\props_wasteland\rockcliff_cluster02c.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster02c.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster02c.mdl
hl2\models\props_wasteland\rockcliff_cluster02c.phy
hl2\models\props_wasteland\rockcliff_cluster03a.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster03a.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster03a.mdl
hl2\models\props_wasteland\rockcliff_cluster03a.phy
hl2\models\props_wasteland\rockcliff_cluster03b.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster03b.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster03b.mdl
hl2\models\props_wasteland\rockcliff_cluster03b.phy
hl2\models\props_wasteland\rockcliff_cluster03c.dx7_2bone.vtx
hl2\models\props_wasteland\rockcliff_cluster03c.dx80.vtx
hl2\models\props_wasteland\rockcliff_cluster03c.mdl
hl2\models\props_wasteland\rockcliff_cluster03c.phy
hl2\models\props_wasteland\RockCluster01a.dx7_2bone.vtx
hl2\models\props_wasteland\RockCluster01a.dx80.vtx
hl2\models\props_wasteland\RockCluster01a.mdl
hl2\models\props_wasteland\RockCluster01a.phy
hl2\models\props_wasteland\RockCluster02a.dx7_2bone.vtx
hl2\models\props_wasteland\RockCluster02a.dx80.vtx
hl2\models\props_wasteland\RockCluster02a.mdl
hl2\models\props_wasteland\RockCluster02a.phy
hl2\models\props_wasteland\rocksground01a.dx7_2bone.vtx
hl2\models\props_wasteland\rocksground01a.dx80.vtx
hl2\models\props_wasteland\rocksground01a.mdl
hl2\models\props_wasteland\rocksground01a.phy
hl2\models\props_wasteland\rocksground01b.dx7_2bone.vtx
hl2\models\props_wasteland\rocksground01b.dx80.vtx
hl2\models\props_wasteland\rocksground01b.mdl
hl2\models\props_wasteland\rocksground01b.phy

hl2\models\ShaderTest\envballs.dx7_2bone.vtx
hl2\models\ShaderTest\envballs.dx80.vtx
hl2\models\ShaderTest\envballs.mdl

hl2\models\Weapons\flare.dx7_2bone.vtx
hl2\models\Weapons\flare.dx80.vtx
hl2\models\Weapons\flare.mdl
hl2\models\Weapons\rifleshell.dx7_2bone.vtx
hl2\models\Weapons\rifleshell.dx80.vtx
hl2\models\Weapons\rifleshell.mdl
hl2\models\Weapons\shell.dx7_2bone.vtx
hl2\models\Weapons\shell.dx80.vtx
hl2\models\Weapons\shell.mdl
hl2\models\Weapons\Shotgun_shell.dx7_2bone.vtx
hl2\models\Weapons\Shotgun_shell.dx80.vtx
hl2\models\Weapons\Shotgun_shell.mdl
hl2\models\Weapons\v_ar2.jpg
hl2\models\Weapons\v_Grenade.jpg
hl2\models\Weapons\v_Pistol.jpg
hl2\models\Weapons\w_IRifle.jpg
hl2\models\Weapons\w_rocket_launcher.dx7_2bone.vtx
hl2\models\Weapons\w_rocket_launcher.dx80.vtx
hl2\models\Weapons\w_rocket_launcher.mdl
hl2\models\Weapons\w_rocket_launcher.phy
hl2\models\Weapons\w_shotgun.dx7_2bone.vtx
hl2\models\Weapons\w_shotgun.dx80.vtx
hl2\models\Weapons\w_shotgun.mdl
hl2\models\Weapons\w_stunbaton.jpg

hl2\models\Zombie\Classic_legs.dx7_2bone.vtx
hl2\models\Zombie\Classic_legs.dx80.vtx
hl2\models\Zombie\Classic_legs.jpg
hl2\models\Zombie\Classic_legs.mdl
hl2\models\Zombie\Classic_legs.phy

hl2\models\Zombie\Classic_torso.dx7_2bone.vtx
hl2\models\Zombie\Classic_torso.dx80.vtx
hl2\models\Zombie\Classic_torso.mdl
hl2\models\Zombie\Classic_torso.phy

hl2\models\Zombie\Poison.dx7_2bone.vtx
hl2\models\Zombie\Poison.dx80.vtx
hl2\models\Zombie\Poison.mdl
hl2\models\Zombie\Poison.phy

hl2\scenes\coast\cubbage01.vcd
hl2\scenes\coast\cubbage02.vcd
hl2\scenes\coast\cubbage03.vcd

hl2\scenes\eli_lab\e_lab01.vcd
hl2\scenes\eli_lab\e_lab03.vcd
hl2\scenes\eli_lab\e_lab04.vcd
hl2\scenes\eli_lab\e_lab06.vcd
hl2\scenes\eli_lab\e_lab07.vcd
hl2\scenes\eli_lab\e_lab08.vcd
hl2\scenes\eli_lab\e_lab09.vcd
hl2\scenes\eli_lab\e_lab10.vcd
hl2\scenes\eli_lab\e_lab11.vcd
hl2\scenes\eli_lab\e_lab12.vcd
hl2\scenes\eli_lab\e_lab13.vcd
hl2\scenes\eli_lab\e_lab14.vcd
hl2\scenes\eli_lab\e_lab15.vcd
hl2\scenes\eli_lab\e_lab16.vcd
hl2\scenes\eli_lab\e_lab17.vcd
hl2\scenes\eli_lab\e_lab18.vcd
hl2\scenes\eli_lab\e_lab19.vcd
hl2\scenes\eli_lab\e_lab20.vcd
hl2\scenes\eli_lab\e_lab21.vcd

hl2\scenes\k_lab\alyx_drink03.vcd
hl2\scenes\k_lab\teleport01a.vcd
hl2\scenes\k_lab\teleport01b.vcd
hl2\scenes\k_lab\teleport02a.vcd

hl2\scenes\novaprospekt\conference01.vcd

hl2\scenes\npc\citizen
hl2\scenes\npc\citizen\abouttime01.vcd
hl2\scenes\npc\citizen\abouttime02.vcd
hl2\scenes\npc\citizen\com_movingout.vcd

hl2\scripts\game_sounds.txt
hl2\scripts\game_sounds_citizen.txt
hl2\scripts\game_sounds_coast.txt
hl2\scripts\game_sounds_eli_lab.txt
hl2\scripts\game_sounds_npc_rollermine.txt
hl2\scripts\game_sounds_streetwar.txt

hl2\scripts\kb_act.lst
hl2\scripts\kb_def.lst
hl2\scripts\propdata.txt
hl2\scripts\soundscapes.txt
hl2\scripts\surfaceproperties.txt

hl2\scripts\weapon_alyxgun.txt
hl2\scripts\weapon_rpg.txt

hl2\scripts\talker\npc_citizen.txt
hl2\scripts\talker\response_rules.txt
hl2\scripts\vehicles\jeep_test.txt

hl2\sound\items\ammocrate_close.wav
hl2\sound\items\ammocrate_open.wav

hl2\sound\npc\citizen\abouttime01.wav
hl2\sound\npc\citizen\abouttime02.wav
hl2\sound\npc\citizen\com_movingout.wav

hl2\sound\vehicles\atv_ammo_close.wav
hl2\sound\vehicles\atv_ammo_open.wav

hl2\sound\vo\coast\cr_antlions.wav
hl2\sound\vo\coast\cr_bigbarr.wav
hl2\sound\vo\coast\cr_driveforfeel.wav
hl2\sound\vo\coast\cr_excellent.wav
hl2\sound\vo\coast\cr_gravgun.wav
hl2\sound\vo\coast\cr_magfail.wav
hl2\sound\vo\coast\cr_pier01.wav
hl2\sound\vo\coast\cr_pier02.wav
hl2\sound\vo\coast\cr_pier03.wav
hl2\sound\vo\coast\cr_playerincar.wav
hl2\sound\vo\coast\cr_ramp.wav
hl2\sound\vo\coast\cr_rockslide.wav
hl2\sound\vo\coast\cr_smallbarr.wav
hl2\sound\vo\coast\cr_sorry.wav
hl2\sound\vo\coast\cr_steep.wav
hl2\sound\vo\coast\cr_surfaces.wav
hl2\sound\vo\coast\cr_turbojump.wav
hl2\sound\vo\coast\cubbage01.wav
hl2\sound\vo\coast\cubbage02.wav
hl2\sound\vo\coast\cubbage03.wav
hl2\sound\vo\coast\rpgguy_doasisay.wav
hl2\sound\vo\coast\rpgguy_greet.wav
hl2\sound\vo\coast\rpgguy_outsmart.wav
hl2\sound\vo\coast\rpgguy_showyou.wav
hl2\sound\vo\coast\rpgguy_watchthis.wav

hl2\sound\vo\eli_lab\al_autocycle.wav
hl2\sound\vo\eli_lab\al_bethere01.wav
hl2\sound\vo\eli_lab\al_bethere02.wav
hl2\sound\vo\eli_lab\al_bethere03.wav
hl2\sound\vo\eli_lab\al_canthiswait.wav
hl2\sound\vo\eli_lab\al_comedog01.wav
hl2\sound\vo\eli_lab\al_comedog02.wav
hl2\sound\vo\eli_lab\al_conduct01.wav
hl2\sound\vo\eli_lab\al_conduct02.wav
hl2\sound\vo\eli_lab\al_dad_ques01.wav
hl2\sound\vo\eli_lab\al_dad_scared01.wav
hl2\sound\vo\eli_lab\al_dad_scared02.wav
hl2\sound\vo\eli_lab\al_dogairlock01.wav
hl2\sound\vo\eli_lab\al_dogairlock02.wav
hl2\sound\vo\eli_lab\al_doyouread.wav
hl2\sound\vo\eli_lab\al_fatherwhere.wav
hl2\sound\vo\eli_lab\al_fullwave.wav
hl2\sound\vo\eli_lab\al_getitopen01.wav
hl2\sound\vo\eli_lab\al_getitopen02.wav
hl2\sound\vo\eli_lab\al_goafter01.wav
hl2\sound\vo\eli_lab\al_goafter02.wav
hl2\sound\vo\eli_lab\al_hidad.wav
hl2\sound\vo\eli_lab\al_honest01.wav
hl2\sound\vo\eli_lab\al_honest02.wav
hl2\sound\vo\eli_lab\al_illdothat.wav
hl2\sound\vo\eli_lab\al_joking01.wav
hl2\sound\vo\eli_lab\al_joking02.wav
hl2\sound\vo\eli_lab\al_joking03.wav
hl2\sound\vo\eli_lab\al_keepwatch01.wav
hl2\sound\vo\eli_lab\al_keepwatch02.wav
hl2\sound\vo\eli_lab\al_keepwatch03.wav
hl2\sound\vo\eli_lab\al_lefthand.wav
hl2\sound\vo\eli_lab\al_notgoing.wav
hl2\sound\vo\eli_lab\al_olddays01.wav
hl2\sound\vo\eli_lab\al_olddays02.wav
hl2\sound\vo\eli_lab\al_olddays03.wav
hl2\sound\vo\eli_lab\al_olddays04.wav
hl2\sound\vo\eli_lab\al_oldrecord01.wav
hl2\sound\vo\eli_lab\al_oldrecord02.wav
hl2\sound\vo\eli_lab\al_oldrecord03.wav
hl2\sound\vo\eli_lab\al_omgno.wav
hl2\sound\vo\eli_lab\al_omgscanners01.wav
hl2\sound\vo\eli_lab\al_omgscanners02.wav
hl2\sound\vo\eli_lab\al_omgscanners03.wav
hl2\sound\vo\eli_lab\al_onepiece.wav
hl2\sound\vo\eli_lab\al_riled01.wav
hl2\sound\vo\eli_lab\al_riled02.wav
hl2\sound\vo\eli_lab\al_scouts01.wav
hl2\sound\vo\eli_lab\al_scouts02.wav
hl2\sound\vo\eli_lab\al_south01.wav
hl2\sound\vo\eli_lab\al_south02.wav
hl2\sound\vo\eli_lab\al_stirredup01.wav
hl2\sound\vo\eli_lab\al_stirredup02.wav
hl2\sound\vo\eli_lab\al_stirredup03.wav
hl2\sound\vo\eli_lab\al_theyknow01.wav
hl2\sound\vo\eli_lab\al_theyknow02.wav
hl2\sound\vo\eli_lab\al_thisisdog01.wav
hl2\sound\vo\eli_lab\al_thisisdog02.wav
hl2\sound\vo\eli_lab\al_thisisdog03.wav
hl2\sound\vo\eli_lab\al_thisisdog04.wav
hl2\sound\vo\eli_lab\al_thisisdog05.wav
hl2\sound\vo\eli_lab\al_thisisdog06.wav
hl2\sound\vo\eli_lab\al_thisway.wav
hl2\sound\vo\eli_lab\al_tour01.wav
hl2\sound\vo\eli_lab\al_tour02.wav
hl2\sound\vo\eli_lab\al_trackthem.wav
hl2\sound\vo\eli_lab\al_yes.wav
hl2\sound\vo\eli_lab\eli_2mode.wav
hl2\sound\vo\eli_lab\eli_alyxsweet.wav
hl2\sound\vo\eli_lab\eli_askhim01.wav
hl2\sound\vo\eli_lab\eli_askhim02.wav
hl2\sound\vo\eli_lab\eli_askhim03.wav
hl2\sound\vo\eli_lab\eli_basehouse01.wav
hl2\sound\vo\eli_lab\eli_basehouse02.wav
hl2\sound\vo\eli_lab\eli_basehouse03.wav
hl2\sound\vo\eli_lab\eli_basehouse04.wav
hl2\sound\vo\eli_lab\eli_basehouse05.wav
hl2\sound\vo\eli_lab\eli_basehouse06.wav
hl2\sound\vo\eli_lab\eli_basehouse07.wav
hl2\sound\vo\eli_lab\eli_basehouse08.wav
hl2\sound\vo\eli_lab\eli_comeout.wav
hl2\sound\vo\eli_lab\eli_evac01.wav
hl2\sound\vo\eli_lab\eli_evac02.wav
hl2\sound\vo\eli_lab\eli_evac03.wav
hl2\sound\vo\eli_lab\eli_evac04.wav
hl2\sound\vo\eli_lab\eli_fineidea01.wav
hl2\sound\vo\eli_lab\eli_fineidea02.wav
hl2\sound\vo\eli_lab\eli_fineidea03.wav
hl2\sound\vo\eli_lab\eli_granddaddy01.wav
hl2\sound\vo\eli_lab\eli_granddaddy02.wav
hl2\sound\vo\eli_lab\eli_impressed01.wav
hl2\sound\vo\eli_lab\eli_impressed02.wav
hl2\sound\vo\eli_lab\eli_impressed03.wav
hl2\sound\vo\eli_lab\eli_impressed04.wav
hl2\sound\vo\eli_lab\eli_impressed05.wav
hl2\sound\vo\eli_lab\eli_impressed06.wav
hl2\sound\vo\eli_lab\eli_impressed07.wav
hl2\sound\vo\eli_lab\eli_impressed08.wav
hl2\sound\vo\eli_lab\eli_letmethink01.wav
hl2\sound\vo\eli_lab\eli_letmethink02.wav
hl2\sound\vo\eli_lab\eli_letmethink03.wav
hl2\sound\vo\eli_lab\eli_micro01.wav
hl2\sound\vo\eli_lab\eli_micro02.wav
hl2\sound\vo\eli_lab\eli_micro03.wav
hl2\sound\vo\eli_lab\eli_mockup01.wav
hl2\sound\vo\eli_lab\eli_mockup02.wav
hl2\sound\vo\eli_lab\eli_mockup03.wav
hl2\sound\vo\eli_lab\eli_myself.wav
hl2\sound\vo\eli_lab\eli_natural01.wav
hl2\sound\vo\eli_lab\eli_natural02.wav
hl2\sound\vo\eli_lab\eli_north.wav
hl2\sound\vo\eli_lab\eli_nownow.wav
hl2\sound\vo\eli_lab\eli_pickedup01.wav
hl2\sound\vo\eli_lab\eli_pickedup02.wav
hl2\sound\vo\eli_lab\eli_pickedup03.wav
hl2\sound\vo\eli_lab\eli_realcore01.wav
hl2\sound\vo\eli_lab\eli_realcore02.wav
hl2\sound\vo\eli_lab\eli_righthand01.wav
hl2\sound\vo\eli_lab\eli_righthand02.wav
hl2\sound\vo\eli_lab\eli_techlib01.wav
hl2\sound\vo\eli_lab\eli_techlib02.wav
hl2\sound\vo\eli_lab\eli_techlib03.wav
hl2\sound\vo\eli_lab\eli_techlib04.wav
hl2\sound\vo\eli_lab\eli_techlib05.wav
hl2\sound\vo\eli_lab\eli_tryit.wav
hl2\sound\vo\eli_lab\eli_verygood.wav
hl2\sound\vo\eli_lab\eli_whereyou.wav
hl2\sound\vo\eli_lab\eli_whoa01.wav
hl2\sound\vo\eli_lab\eli_whoa02.wav
hl2\sound\vo\eli_lab\eli_withme.wav
hl2\sound\vo\eli_lab\eli_youwerethere01.wav
hl2\sound\vo\eli_lab\eli_youwerethere02.wav
hl2\sound\vo\eli_lab\eli_youwerethere03.wav
hl2\sound\vo\eli_lab\mo_excuseus01.wav
hl2\sound\vo\eli_lab\mo_excuseus02.wav
hl2\sound\vo\eli_lab\mo_goodpoint.wav
hl2\sound\vo\eli_lab\mo_important.wav
hl2\sound\vo\eli_lab\mo_outthere.wav
hl2\sound\vo\eli_lab\mo_youropinion.wav
hl2\sound\vo\eli_lab\vort_deadsea.wav
hl2\sound\vo\eli_lab\vort_taken.wav
hl2\sound\vo\NovaProspekt\mo_asistated.wav

hl2\testscripts\perftests.vtest

XSI\Models
XSI\Models\CharacterStudioGuide_Sym.emdl
```

