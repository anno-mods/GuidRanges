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

There are certain unused vanilla FreeAreaType enums available in certain sessions. Test empty Citrus, Coconut and Camphor Treeconfigs before you use them in Arctic/Enbesa!

Enum | Region | Author | Building (Mod)
--- | --- | --- | ---
None | Moderate | vanilla | Orchard Blank
None | New World | vanilla | Orchard Blank
Lumberjack | all | vanilla | Lumberjack Huts
Hunter | Moderate | vanilla | Hunting Cabin
Hunter | New World | Taludas | Cinnamon Orchard (Campher and Cinnamon use different trees)
Hunter | Arctic | vanilla | Caribou Hunter
Hunter | Arctic | vanilla | Prime Hunting Cabin
Hunter | Enbesa | Kurila | Cinnamon Orchard
Hunter2 | Moderate | Taludas | Apple Orchard (Noblesse Oblige)
Hunter2 | New World |  | 
Hunter2 | Arctic | vanilla | Bear Hunter
Hunter2 | Enbesa |  | 
Citrus | Moderate | vanilla | Jam Orchard
Citrus | New World | vanilla | Citrus Orchard
Citrus | Arctic |  |
Citrus | Enbesa | Kurila | Citrus Orchard
Coconut | Moderate | vanilla | Resin Orchard
Coconut | New World | vanilla | Coconut Oil Orchard, Industrial Oil Press
Coconut | Arctic |  |
Coconut | Enbesa | Kurila | Coconut Orchard
Camphor | Moderate | vanilla | Cherry Wood Orchard
Camphor | New World | vanilla | Cinnamon Orchard, Camphor Wax Orchard
Camphor | Arctic |  |
Camphor | Enbesa | Kurila | Camphor Wax Orchard
FirTrees | Enbesa | Kurila | Palm Oil Orchard




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
Mod6 | Taubenangriff / Hier0nimus | Diplomacy Flags
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

There are certain unused vanilla ItemAllocation enums available in certain sessions.

Enum | Author | Session | Mod
--- | --- | --- | ---
None | vanilla | everywhere | default property
RadiusBuilding | vanilla | everywhere | all Radius Buildings
Guildhouse | vanilla | everywhere | Guildhouse
Townhall | vanilla | everywhere | Townhall
HarborOffice | vanilla | everywhere | Harbor Office
Headquarter | Tisogno | everywhere | Headquarters
Culture | vanilla | everywhere | Itemfilter
Zoo | vanilla | everywhere | all Zoos
BotanicGarden | vanilla | everywhere | all BotanicGardens
Museum | vanilla | everywhere | all Museums
Ship | vanilla | everywhere | all Ships
SailShip | vanilla | everywhere | all SailShips
SteamShip | vanilla | everywhere | all SteamShips
Expedition | vanilla | everywhere | Itemfilter
Warship | vanilla | everywhere | all Warships
Tradeship | vanilla | everywhere | all Tradeships
DivingVessel | vanilla | everywhere | Diving Vessel
Pavilion | vanilla | everywhere | all Music Pavilions
AirShip | vanilla | everywhere | all AirShips
Lodge | vanilla | Arctic | Lodge
BuildPermit | vanilla | everywhere | Itemfilter
Dockland | vanilla | Moderate | Docklands
AarhantShip | vanilla | New World | Hidden Quest: Aarhant Ship

## ParticipantID

Enum | Author | Mod
--- | --- | ---
Mod1 | Taubenangriff | New Horizons |
Mod2 | Taubenangriff | New Horizons |
Mod3 | Taubenangriff | New Horizons |
Mod4 | Taubenangriff | New Horizons |
Mod5 | Taludas | Noblesse Oblige |
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
Mod11 | Hier0nimus | Navy Recruitment Office - Military Attention |
Mod12 | Hier0nimus | Sanitation Facility - Military Attention |
Mod13 | Hier0nimus | Clean Water Pump - Military Attention |
Mod14 |
Mod15 | Tisogno | Garbage Collection |
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

There are certain unused vanilla SocketScopeRadiusOverlapCategory enums available in certain sessions.

Enum | Author | Session | Mod
--- | --- | --- | ---
None | vanilla | everywhere | default property
Guildhouse | vanilla | everywhere | Guildhouse
Townhall | vanilla | Moderate, New World, Enbesa | Townhall
HarborOffice | vanilla | everywhere | Harbor Office
Postbox | vanilla | Moderate, New World, Arctic | Postboxes, Post Offices
Postbox | Hackner | Enbesa | Hackner's Enbesa Mail Integration
PassengerKiosk | Tisogno | Moderate | Garbage Collection 
PassengerKiosk |  | New World | 
PassengerKiosk |  | Arctic | 
PassengerKiosk | Tisogno | Enbesa | Watering Enbesa

## UniqueType

Consider using "BuildPermit" instead, if you want to limit it globally or per region to a max amount of X.  
If all Enums are already in use, you can also use this code to limit to "once per island": [OncePerIsland](https://github.com/Serpens66/Anno-1800-SharedMods-for-Modders-/blob/main/CodeSnippets.md#limit-a-building-to-once-per-island-without-uniquetype-property).  
Since there are alternatives for worldwide,region and island, the only needed usecase of these Enums is "once per Session".
(UniqueType is also used for "ModuleParentType" to tell the game that modules built from within the buildmenu belonging to this UniqueType. But there are reports that Mod-Enums are not working here for whatever reason and you don't need it for modules directly built from the UI of the main building)
Enum | Author | Mod
--- | --- | ---
Mod1 | Lion053 | Subway Network
Mod2 | Qurila | Job Advertisements
Mod3 | Drakkam/Taubenangriff/Taludas | Shared Foreign Trading Company
Mod4 |
Mod5 |
Mod6 |
Mod7 |
Mod8 |
Mod9 |
Mod10 | Khobs | New World Palace
Mod11 | Hier0nimus | Fort - Military Attention / Crafting Centre - White & Cold |
Mod12 | Hier0nimus | Military Headquarters - Military Attention / Coastal Centre - White & Cold |
Mod13 | Hier0nimus | Forest Centre - White & Cold |
Mod14 | Hier0nimus | Ice Harbour - White & Cold |
Mod15 | Tisogno | Maya Treasure
Mod16 |
Mod17 |
Mod18 |
Mod19 |
Mod20 |

There are certain unused vanilla UniqueType enums available in certain sessions.

Enum | Author | Session | Mod
--- | --- | --- | ---
None | vanilla | everywhere | default property
VisitorHarbor | vanilla | Moderate, New World | all Visitor Piers
VisitorHarbor |  | Arctic | 
VisitorHarbor | Lion053 | Enbesa | Visitor Pier
Monument01 | vanilla | Moderate | World's Fair
Monument01 | vanilla | New World | Stadium
Monument01 | vanilla | Arctic | Airship Hangar
Monument01 | Lion053 | Enbesa | Tourism Authority
Headquarter | Tisogno | Global | Headquarters
CoalHarbor | Tisogno | Moderate | Garbage Collection
CoalHarbor | Tisogno | New World | Mayan Treasures
CoalHarbor |  | Arctic | 
CoalHarbor | Tisogno | Enbesa | Watering Enbesa
OilHarbor | vanilla | Moderate, New World, Enbesa | Oil Habors
OilHarbor | | Arctic | 
WorkforceConnector | vanilla | Moderate, New World | Commuter Pier, Workforce Module Airship Platform
WorkforceConnector | Taubenangriff | Enbesa | Enbesan Commuter Pier
WorkforceConnector | Taubenangriff | Arctic | Arctic Commuter Pier
Palace | vanilla | Global | Palace
PalaceMinistry | vanilla | Moderate | all Ministries
PalaceMinistry | Khobs | New World | New World Palace Ministry
PalaceMinistry | Tisogno | Enbesa | Watering Enbesa
PalaceMinistry | | Arctic | 
ResearchCenter | vanilla | Global | Research Center
Dockland | vanilla | Moderate | Docklands
Dockland | Kurila | New World | New World Docklands
Dockland | Kurila | Arctic | New World Docklands
Dockland | Kurila | Enbesa | New World Docklands
TourismMonument | vanilla | Moderate | Iron Tower
TourismMonument | Taubenangriff, Dalexy, Fam, Jakob | New World | New World Tourism
TourismMonument | | Arctic | 
TourismMonument | | Enbesa |
HighLifeMonument | vanilla | Moderate | Skyline Tower
HighLifeMonument | Tisogno | New World | Mayan Treasures
HighLifeMonument | | Arctic | 
HighLifeMonument | | Enbesa |
Hacienda | | Moderate | 
Hacienda | vanilla | New World | Hacienda
Hacienda | Tisogno | Arctic | Mayan Treasures
Hacienda | Tisogno | Enbesa | Mayan Treasures
AirshipPlatform | vanilla | Moderate, New World, Arctic | Airship Platforms
AirshipPlatform | Hackner | Enbesa | Hackner's Enbesan Mail Integration
AirshipPlatformItemTransferModule | vanilla | Moderate, New World, Arctic | Item Transfer Modules
AirshipPlatformItemTransferModule | Hackner | Enbesa | Hackner's Enbesan Mail Integration
AirshipPlatformWorkforceTransferModule | | Moderate | 
AirshipPlatformWorkforceTransferModule | vanilla | New World | Workforce Transfer Module
AirshipPlatformWorkforceTransferModule | | Arctic | 
AirshipPlatformWorkforceTransferModule | | Enbesa |


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
Stadium12 | Taludas | Noblesse Oblige |
Stadium13 | 
Stadium14 | 
Stadium15 | Tisogno | Mayan Treasures |

