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
Mod6 |
Mod7 |
Mod8 |
Mod9 |
Mod10 |
Mod11 |
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
Mod12 |
Mod13 |
Mod14 |
Mod15 | Tisogno | Garbage Collection |
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

## UniqueType

Consider using "BuildPermit" instead, if you want to limit it globally or per region to a max amount of X.
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
Mod10 |
Mod11 |
Mod12 |
Mod13 |
Mod14 |
Mod15 | Tisogno | Maya Treasure
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |
