# Mod Enums

Please always consider alternatives before taking one of the precious enum slots.

- [Mod Enums](#mod-enums)
  - [FreeAreaType](#freeareatype)
  - [ItemAllocation](#itemallocation)
  - [ParticipantID](#participantid)
  - [Region](#region)
  - [SocketExclusiveGroup](#socketexclusivegroup)
  - [SocketScopeRadiusOverlapCategory](#socketscoperadiusoverlapcategory)
  - [UniqueType](#uniquetype)  
  - [FestivalType](#festivaltype)

## FreeAreaType

Enum | Author | Mod
--- | --- | ---
Mod1 |
Mod2 |
Mod3 |
Mod4 |
Mod5 |
Mod6 |
Mod7 |
Mod8 |
Mod9 |
Mod10 |

## ItemAllocation

When using new ItemAllocations, make sure you use **compatible** code like this to change existing items/filters:

```xml
<ModOp Type="add" GUID="1010516" Path="/Values/ItemContainer/SocketAllocation">;Mod1</ModOp>
<ModOp Type="add" GUID="502015" Path="/Values/ItemFilter/ItemCategories/Item[CategoryAsset='18021']/ItemTypes">;Mod1</ModOp>
```

Enum | Author | Mod
--- | --- | ---
Mod1 | Qurila | Combinated Allocations |
Mod2 |
Mod3 |
Mod4 |
Mod5 |
Mod6 | Taubenangriff / Hier0nimus | Pirate Flags
Mod7 |
Mod8 |
Mod9 |
Mod10 | S1LV3R-p0tat0 / Hier0nimus | Torpedo Launcher
Mod11 | S1LV3R-p0tat0 | Kamikaze Plane
Mod12 |
Mod13 |
Mod14 |
Mod15 | Tisogno | Maya Treasures |
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

## ParticipantID

Enum | Author | Mod
--- | --- | ---
Mod1 | Taubenangriff | New Horizons |
Mod2 | Taubenangriff | New Horizons |
Mod3 | Taubenangriff | New Horizons |
Mod4 | Taubenangriff | New Horizons |
Mod5 |
Mod6 |
Mod7 |
Mod8 |
Mod9 |
Mod10 | Serp | shared Nature Participant (helper) |
Mod11 |
Mod12 |
Mod13 |
Mod14 |
Mod15 |
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

## Region

Enum | Author | Mod
--- | --- | ---
Mod1 |
Mod2 | Taubenangriff | New Horizons |
Mod3 |

## SocketExclusiveGroup

Enum | Author | Mod
--- | --- | ---
Mod1 |
Mod2 |
Mod3 |
Mod4 |
Mod5 |
Mod6 |
Mod7 |
Mod8 |
Mod9 |
Mod10 |
Mod11 |
Mod12 |
Mod13 |
Mod14 |
Mod15 |
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

## SocketScopeRadiusOverlapCategory

Enum | Author | Mod
--- | --- | ---
Mod1 |
Mod2 |
Mod3 |
Mod4 |
Mod5 |
Mod6 |
Mod7 |
Mod8 |
Mod9 |
Mod10 | Serp | Limited Defense |
Mod11 | Hier0nimus | Navy Recruitment Office - Military Attention Mod |
Mod12 | Hier0nimus | Sanitation Facility - Military Attention Mod |
Mod13 | Hier0nimus | Clean Water Pump - Military Attention Mod |
Mod14 |
Mod15 | Tisogno | Garbage Collection |
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

## UniqueType

Consider using "BuildPermit" instead, if you want to limit it globally or per region to a max amount of X.  
If all Enums are already in use, you can also use this code to limit to "once per island": [OncePerIsland](https://github.com/Serpens66/Anno-1800-SharedMods-for-Modders-/blob/main/CodeSnippets.md#limit-a-building-to-once-per-island-without-uniquetype-property).  
Since there are alternatives for worldwide,region and island, the only needed usecase of these Enums is "once per Session".
(UniqueType is also used for "ModuleParentType" to tell the game that modules built from within the buildmenu belonging to this UniqueType. But there are reports that Mod-Enums are not working here for whatever reason and you don't need it for modules directly built from the UI of the main building)
Enum | Author | Mod
--- | --- | ---
Mod1 | Lion053 | Subway Network
Mod2 | Qurila | Job Advertisements
Mod3 |
Mod4 |
Mod5 |
Mod6 |
Mod7 |
Mod8 |
Mod9 |
Mod10 | Khobs | New World Palace
Mod11 | Hier0nimus | Fort - Military Attention Mod |
Mod12 | Hier0nimus | Military Headquarters - Military Attention Mod |
Mod13 |
Mod14 |
Mod15 | Tisogno | Maya Treasure
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

## FestivalType

We got no ModX Enums for Festivals, but Taubenangriff figured out the vanilla Stadium Festivals also work fine with only 3 Enums (Stadium1,Stadium6 and Stadium11), instead of 15, so we can make use of the rest for modding.

Copy paste these 3 modops into your mod, to free up Stadium Enums.
```xml
  <ModOp  Type="replace" GUID="6499,6500,6501,6502" Path="/Values/Reward/RewardAssets/Item[2]/Reward">
    <Reward>6931</Reward>
  </ModOp>
  <ModOp  Type="replace" GUID="6948,6949,6950,6951" Path="/Values/Reward/RewardAssets/Item[2]/Reward">
    <Reward>6936</Reward>
  </ModOp>
  <ModOp  Type="replace" GUID="6503,6504,6505,6506" Path="/Values/Reward/RewardAssets/Item[2]/Reward">
    <Reward>6941</Reward>
  </ModOp>
```
Example how to continue after this, see eg. this mod: https://github.com/Pnski/Anno1800MoreFestivalTypes/tree/main
(replacing the content of GUID 141893 for your chosen Enum and adding tooltip support (infotips))
Or short tutorial here: https://a1800mod.github.io/#/en/tutorials/Festivals

Enum | Author | Mod
--- | --- | ---
Stadium2 | Taubenangriff | New Horizons |
Stadium3 | Taubenangriff | New Horizons |
Stadium4 | Taubenangriff | New Horizons |
Stadium5 | Taubenangriff | New Horizons |
Stadium7 | nyk/pnski | MoreFestivalTypes_Nyk |
Stadium8 | nyk/pnski | MoreFestivalTypes_Nyk |
Stadium9 | nyk/pnski | MoreFestivalTypes_Nyk |
Stadium10 | nyk/pnski | MoreFestivalTypes_Nyk |
Stadium12 | 
Stadium13 | 
Stadium14 | 
Stadium15 | Tisogno | Mayan Treasures

