# Rose Utilities
Adds a collection of items, structures, and features that enhance both vanilla and modded ARK experiences.

## GameUserSettings.ini Configuration
First close your game/server. Then in the GameUserSettings.ini file, find/add the [RoseUtilities] section below and change the settings you want changed and save the file. When you restart your game/server, the new settings should be applied.

The settings are as follows:
- SlaughterEnabled: Should the Slaughter MultiUse show for tamed dinos (True or False)
- SlaughterXPMultiplier: Multiplier for how much XP dinos give when Slaughtered (0 or higher)
- PacifyMinLevel: Minimum level dinos must be to be Pacified BEFORE multiplying by Difficulty (don't forget to account for taming effectiveness bonus levels) (0 - 999)
- GenomeHarvestMinLevel: Minimum level dinos must be to be Genome Harvested BEFORE multiplying by Difficulty (don't forget to account for taming effectiveness bonus levels) (0 - 999)
- GenomeHarvestAlwaysIncreaseStatAmount: Amount Food, Oxygen, and Speed should increase per Stat Mutating Genome use (0 - 254)
- GenomeHarvestRandomIncreaseStatAmount: Amount Weight or Stamina and Health or Melee should increase per Stat Mutating Genome use (0 - 254)
- TransferChuteMaxTransferRange: Max range in foundations inventories can be apart to transfer items with the Transfer Chute (0 - 60)
- ResourcesToTransfer: Comma separated list of items that count as resources which that a player has no reason to keep on them outside of resource collection
- InfiniteFoodBuffBlacklist: Comma separated list of creatures that cannot have infinite food items used on them
- ShockAbsorbersDamageCap: Max amount of fall damage taken when Shock Absorbers are applied (0 or higher)
- ShockAbsorbersDamagePercent: Max percent of fall damage taken when Shock Absorbers are applied (0 - 1)
- PlatformProtectorAllowPVPDamage: Should the Platform Protector allow PvP damage against protected dinos (True or False)
- HoneyBarrelAutoCollectStructureWhitelist: Comma separated list of structures Honey Barrel can pull honey from
- PackagerAutoCollectStructureWhitelist: Comma separated list of structures Packager can pull resources from
- CommunalNestIncubationRate: Rate at which the Communal Nest incubates fertilized eggs in its inventory (0 or higher)
- CommunalNestDisableMatingWhenFull: Should the Communal Nest disable mating for all dinos in range when full (True or False)
- SnailSanctuaryProductionPerMinute: How many Achatina Paste the Snail Sanctuary creates per minute (0 - 1000)
- DinoDaycareConsumptionRate: How many Rare Flowers per cycle should the Dino Daycare consume while Imprinting is enabled (0 or higher)
- DinoDaycareAllowAutoClaim: Should Dino Daycare be able to auto claim nearby baby dinos (True or False)
- DinoDaycareDisableMatingNearbyDinoAmount: Max number of dinos in range of Dino Daycare before disabling mating for all dinos in range; disabled if -1 (-1 - 999999)
- HoneyBarrelAutoCollectRange: Max range in foundations (0 - 50)
- PackagerAutoCollectRange: Max range in foundations (0 - 50)
- IndustrialComposterRange: Max range in foundations (0 - 50)
- CropSiloAutoCollectRange: Max range in foundations (0 - 50)
- CommunalNestAutoCollectRange: Max range in foundations (0 - 50)
- DinoDaycareRange: Max range in foundations (0 - 30)

```
[RoseUtilities]
SlaughterEnabled=True
SlaughterXPMultiplier=1
PacifyMinLevel=25
GenomeHarvestMinLevel=40
GenomeHarvestAlwaysIncreaseStatAmount=1
GenomeHarvestRandomIncreaseStatAmount=2
TransferChuteMaxTransferRange=30
ResourcesToTransfer='/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_BlackPearl.PrimalItemResource_BlackPearl,/Game/Aberration/CoreBlueprints/Resources/PrimalItemResource_Gem_Base.PrimalItemResource_Gem_Base,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_ChitinPaste.PrimalItemResource_ChitinPaste,/Game/PrimalEarth/Dinos/Achatina/PrimalItemResource_SnailPaste.PrimalItemResource_SnailPaste,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Charcoal.PrimalItemResource_Charcoal,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Chitin.PrimalItemResource_Chitin,/Game/ScorchedEarth/CoreBlueprints/Resources/PrimalItemResource_Clay.PrimalItemResource_Clay,/Game/Extinction/CoreBlueprints/Resources/PrimalItemResource_CondensedGas.PrimalItemResource_CondensedGas,/Game/Aberration/CoreBlueprints/Resources/PrimalItemResource_Gas.PrimalItemResource_Gas,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Polymer.PrimalItemResource_Polymer,/Game/Extinction/CoreBlueprints/Resources/PrimalItemResource_CorruptedWood.PrimalItemResource_CorruptedWood,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Wood.PrimalItemResource_Wood,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Crystal.PrimalItemResource_Crystal,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Electronics.PrimalItemResource_Electronics,/Game/Aberration/CoreBlueprints/Resources/PrimalItemResource_ElementOre.PrimalItemResource_ElementOre,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Fibers.PrimalItemResource_Fibers,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Flint.PrimalItemResource_Flint,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Gunpowder.PrimalItemResource_Gunpowder,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Hide.PrimalItemResource_Hide,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Keratin.PrimalItemResource_Keratin,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_LeechBlood.PrimalItemResource_LeechBlood,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Metal.PrimalItemResource_Metal,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_MetalIngot.PrimalItemResource_MetalIngot,/Game/Genesis2/CoreBlueprints/Environment/Mutagen/PrimalItemConsumable_Mutagel.PrimalItemConsumable_Mutagel,/Game/Genesis2/CoreBlueprints/Environment/Mutagen/PrimalItemConsumable_Mutagen.PrimalItemConsumable_Mutagen,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Obsidian.PrimalItemResource_Obsidian,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Oil.PrimalItemResource_Oil,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_PeltOrHair.PrimalItemResource_PeltOrHair,/Game/ScorchedEarth/CoreBlueprints/Resources/PrimalItemResource_RawSalt.PrimalItemResource_RawSalt,/Game/ScorchedEarth/CoreBlueprints/Resources/PrimalItemResource_Sand.PrimalItemResource_Sand,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Sap.PrimalItemResource_Sap,/Game/Extinction/CoreBlueprints/Resources/PrimalItemResource_ScrapMetal.PrimalItemResource_ScrapMetal,/Game/Extinction/CoreBlueprints/Resources/PrimalItemResource_ScrapMetalIngot.PrimalItemResource_ScrapMetalIngot,/Game/Genesis/CoreBlueprints/Resources/PrimalItemResource_TurtleShell.PrimalItemResource_TurtleShell,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Silicon.PrimalItemResource_Silicon,/Game/ScorchedEarth/CoreBlueprints/Resources/PrimalItemResource_Silk.PrimalItemResource_Silk,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Sparkpowder.PrimalItemResource_Sparkpowder,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Stone.PrimalItemResource_Stone,/Game/ScorchedEarth/CoreBlueprints/Resources/PrimalItemResource_Sulfur.PrimalItemResource_Sulfur,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Thatch.PrimalItemResource_Thatch,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Wool.PrimalItemResource_Wool,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Base.PrimalItemResourcePallet_Base,/Game/PrimalEarth/CoreBlueprints/Items/Consumables/BaseBPs/PrimalItemConsumable_Berry_Base.PrimalItemConsumable_Berry_Base,/Game/PrimalEarth/CoreBlueprints/Items/Consumables/Seeds/PrimalItemConsumableSeed.PrimalItemConsumableSeed,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_RareMushroom.PrimalItemResource_RareMushroom,/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_RareFlower.PrimalItemResource_RareFlower,/Game/PrimalEarth/CoreBlueprints/Items/Consumables/BaseBPs/PrimalItemConsumable_Veggie_Base.PrimalItemConsumable_Veggie_Base,/Game/PrimalEarth/CoreBlueprints/Items/Consumables/BaseBPs/PrimalItemConsumablePoop.PrimalItemConsumablePoop,/Game/PrimalEarth/CoreBlueprints/Items/Consumables/PrimalItemConsumable_RawMeat.PrimalItemConsumable_RawMeat,/Game/PrimalEarth/CoreBlueprints/Items/Consumables/PrimalItemConsumable_RawPrimeMeat.PrimalItemConsumable_RawPrimeMeat,/Game/PrimalEarth/CoreBlueprints/Items/Consumables/PrimalItemConsumable_SpoiledMeat.PrimalItemConsumable_SpoiledMeat,/Game/Mods/RosesUtilities/Items/Resources/MutatingGenomes/PrimalItemResource_StatMutatingGenome.PrimalItemResource_StatMutatingGenome,/Game/Mods/RosesUtilities/Items/Resources/MutatingGenomes/PrimalItemResource_ColorMutatingGenome.PrimalItemResource_ColorMutatingGenome'
InfiniteFoodBuffBlacklist='Daeodon_Character_BP_C,Daeodon_Character_BP_Eden_C'
ShockAbsorbersDamageCap=1000
ShockAbsorbersDamagePercent=0.01
PlatformProtectorAllowPVPDamage=false
HoneyBarrelAutoCollectStructureWhitelist=/Game/PrimalEarth/Structures/BeeHive/BeeHive_PlayerOwned.BeeHive_PlayerOwned,/Game/Mods/StructuresPlusMod/Misc/BeeHive/BP_BeeHivePlus.BP_BeeHivePlus'
PackagerAutoCollectStructureWhitelist='/Game/PrimalEarth/Structures/Forge.Forge,/Game/PrimalEarth/Structures/IndustrialForge.IndustrialForge,/Game/Mods/StructuresPlusMod/Crafting/RefiningForge/BP_ForgePlus.BP_ForgePlus,/Game/Mods/StructuresPlusMod/Misc/IndustrialForge/BP_IndustrialForgePlus.BP_IndustrialForgePlus,/Game/Mods/StructuresPlusMod/Misc/TekForge/BP_TekForge.BP_TekForge'
CommunalNestIncubationRate=1
CommunalNestDisableMatingWhenFull=True
SnailSanctuaryProductionPerMinute=1
DinoDaycareConsumptionRate=1
DinoDaycareAllowAutoClaim=True
DinoDaycareDisableMatingNearbyDinoAmount=400
HoneyBarrelAutoCollectRange=25
PackagerAutoCollectRange=25
IndustrialComposterRange=25
CropSiloAutoCollectRange=25
CommunalNestAutoCollectRange=25
DinoDaycareRange=15
```

## S+ Pull Resource Config
Add the following to the end of the **PullResourceAdditions=** line in your **GameUserSettings.ini** file under the **\[StructuresPlus\]** section to enable S+ resource pulling for Rose's Utilities items. If the config line already has items in it from other mods, separate those items from the Rose's Utilities items with a comma.

```
/Game/Mods/RosesUtilities/Items/Consumables/FleshOfOuroboros/PrimalItemConsumable_FleshOfOuroboros.PrimalItemConsumable_FleshOfOuroboros,/Game/Mods/RosesUtilities/Items/Consumables/FruitOfGrisaia/PrimalItemConsumable_FruitOfGrisaia.PrimalItemConsumable_FruitOfGrisaia,/Game/Mods/RosesUtilities/Items/Consumables/PlatformProtector/PrimalItemConsumable_PlatformProtector.PrimalItemConsumable_PlatformProtector,/Game/Mods/RosesUtilities/Items/Consumables/Self-ImprovementBook/PrimalItemConsumable_Self-ImprovementBook.PrimalItemConsumable_Self-ImprovementBook,/Game/Mods/RosesUtilities/Items/Consumables/ShockAbsorbers/PrimalItemConsumable_ShockAbsorbers.PrimalItemConsumable_ShockAbsorbers,/Game/Mods/RosesUtilities/Items/Consumables/SurvivalKit/PrimalItemConsumable_SurvivalKit.PrimalItemConsumable_SurvivalKit,/Game/Mods/RosesUtilities/Items/Consumables/TeamBuildingBook/PrimalItemConsumable_TeamBuildingBook.PrimalItemConsumable_TeamBuildingBook,/Game/Mods/RosesUtilities/Items/Consumables/V-Mate/PrimalItemConsumable_V-Mate.PrimalItemConsumable_V-Mate,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_MetalIngots.PrimalItemResourcePallet_MetalIngots,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_ScrapMetalIngot.PrimalItemResourcePallet_ScrapMetalIngot,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Crystal.PrimalItemResourcePallet_Crystal,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Wood.PrimalItemResourcePallet_Wood,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_FungalWood.PrimalItemResourcePallet_FungalWood,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_CorruptedWood.PrimalItemResourcePallet_CorruptedWood,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Stone.PrimalItemResourcePallet_Stone,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Obsidian.PrimalItemResourcePallet_Obsidian,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_ElementShard.PrimalItemResourcePallet_ElementShard,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Flint.PrimalItemResourcePallet_Flint,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Charcoal.PrimalItemResourcePallet_Charcoal,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_GreenGem.PrimalItemResourcePallet_GreenGem,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_BlueGem.PrimalItemResourcePallet_BlueGem,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_RedGem.PrimalItemResourcePallet_RedGem,/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_ElementOre.PrimalItemResourcePallet_ElementOre,/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Achatina.PrimalItemResource_PacifiedDino_Achatina,/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_DungBeetle.PrimalItemResource_PacifiedDino_DungBeetle,/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Iguanodon.PrimalItemResource_PacifiedDino_Iguanodon,/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Oviraptor.PrimalItemResource_PacifiedDino_Oviraptor,/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Procoptodon.PrimalItemResource_PacifiedDino_Procoptodon,/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_RollRat.PrimalItemResource_PacifiedDino_RollRat
```
	
## Added Items:
### Consumables:
#### Flesh of Ouroboros
<details><summary>------- Info ---------</summary>

A cursed meat, or a savory sirloin?

Any omnivore or carnivore that consumes this food will have its hunger forever sated; only possible through element infusion and professional seasoning.

*100% grass-fed eternal snake-dragon*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/FleshOfOuroboros/PrimalItemConsumable_FleshOfOuroboros.PrimalItemConsumable_FleshOfOuroboros'" 1 0 false
```
</details>

#### Fruit of Grisaia
<details><summary>------- Info ---------</summary>

A forbidden fruit, or a delicious treat?

Any herbivore that consumes this food will have its hunger forever sated; only possible through element infusion and locally sourced produce.

*100% gluten free...ish*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/FruitOfGrisaia/PrimalItemConsumable_FruitOfGrisaia.PrimalItemConsumable_FruitOfGrisaia'" 1 0 false
```
</details>

#### Platform Protector
<details><summary>------- Info ---------</summary>

Like a pocket protector, but for giant dinos carrying giant structures!

When toggled on, the Platform Protector creates an immobilizing forcefield around the using dino that negates all damage and aggression from the outside.

It should be noted that the forcefield only protects the dino, and not any of the structures (or creatures) it's carrying.

*Great for staying safe, and for building!*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/PlatformProtector/PrimalItemConsumable_PlatformProtector.PrimalItemConsumable_PlatformProtector'" 1 0 false
```
</details>

#### Self-Improvement Book
<details><summary>------- Info ---------</summary>

For when you definitely didn't mean to increase Food instead of Health.

This guide to rediscovering yourself will help any dino go back to square one and improve themselves in new and better-planned out ways!

*Recommended for readers with a reading level of 3 or lower*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/Self-ImprovementBook/PrimalItemConsumable_Self-ImprovementBook.PrimalItemConsumable_Self-ImprovementBook'" 1 0 false
```
</details>

#### Shock Absorbers
<details><summary>------- Info ---------</summary>

Fall damage is for those who lack imagination!

With a lot of cushioning, a bit of bracing, and a not-insignificant amount of finger crossing, your dinos will never have to fear meeting the ground again! 

*Not approved for human use*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/ShockAbsorbers/PrimalItemConsumable_ShockAbsorbers.PrimalItemConsumable_ShockAbsorbers'" 1 0 false
```
</details>

#### Survival Kit
<details><summary>------- Info ---------</summary>

Punching trees isn't just for cube worlds.

Open to reveal a set of basic tools and weapons useful to all fledgling survivors!

*Usefulness may vary from person to person*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/SurvivalKit/PrimalItemConsumable_SurvivalKit.PrimalItemConsumable_SurvivalKit'" 1 0 false
```
</details>

#### Team Building Book
<details><summary>------- Info ---------</summary>

What's gonna work? TEAMMMMMWORK!

Use this book with a dino you want to improve your bond with, and watch as your teamwork and compatibility with them improves!

*Success may vary, ineffective on the inanimate*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/TeamBuildingBook/PrimalItemConsumable_TeamBuildingBook.PrimalItemConsumable_TeamBuildingBook'" 1 0 false
```
</details>

#### V-Mate
<details><summary>------- Info ---------</summary>

No mate? No problem!

The patent-pending V-Mate provides your lonely dinos with their very own virtual mate! Just use it on a dino and watch them receive all the benefits of a mate, without actually needing one! 

Works on all genders (or lack thereof), because everyone deserves love!

*Nonreusable and nonrefundable*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Consumables/V-Mate/PrimalItemConsumable_V-Mate.PrimalItemConsumable_V-Mate'" 1 0 false
```
</details>

### Resources
#### Resource Pallets
<details><summary>------- Info ---------</summary>
	
Compact packages of resources which are lighter and more space efficient than their unpackaged contents. 

Crafted in the [Packager](https://github.com/Alice0Widing/RosesUtilities#packager), and unpacked by using in an inventory. 

Types: 
- Metal Ingot
- Scrap Metal Ingot
- Crystal
- Wood
- Fungal Wood 
- Corrupted Wood
- Stone
- Obsidian
- Element Shards
- Flint
- Charcoal
- Green Gem
- Blue Gem
- Red Gem
- Element Ore

*May cause issues with some stack mods. If you only want to change the stack size of items, use the Game.ini settings instead of a stack mod. If you also want the weight reduction from a stack mod, then the Packager and Resource Pallets are redundant and shouldn't be used.*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_MetalIngots.PrimalItemResourcePallet_MetalIngots'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_ScrapMetalIngot.PrimalItemResourcePallet_ScrapMetalIngot'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Crystal.PrimalItemResourcePallet_Crystal'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Wood.PrimalItemResourcePallet_Wood'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_FungalWood.PrimalItemResourcePallet_FungalWood'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_CorruptedWood.PrimalItemResourcePallet_CorruptedWood'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Stone.PrimalItemResourcePallet_Stone'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Obsidian.PrimalItemResourcePallet_Obsidian'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_ElementShard.PrimalItemResourcePallet_ElementShard'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Flint.PrimalItemResourcePallet_Flint'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_Charcoal.PrimalItemResourcePallet_Charcoal'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_GreenGem.PrimalItemResourcePallet_GreenGem'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_BlueGem.PrimalItemResourcePallet_BlueGem'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_RedGem.PrimalItemResourcePallet_RedGem'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/Pallets/PrimalItemResourcePallet_ElementOre.PrimalItemResourcePallet_ElementOre'" 1 0 false
```
</details>

#### Pacified Dinos
<details><summary>------- Info ---------</summary>

Itemized dinos created with a Pacification Injector.

Cannot be converted back to real dinos and only used for crafting Rose Utilities structures.

Types:
- Achatina
- Dung Beetle
- Iguanodon
- Oviraptor (Can also be crafted with a Pacified Roll Rat in a Smithy)
- Procoptodon (Can also be crafted with a Pacified Roll Rat in a Smithy)
- Roll Rat

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Achatina.PrimalItemResource_PacifiedDino_Achatina'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_DungBeetle.PrimalItemResource_PacifiedDino_DungBeetle'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Iguanodon.PrimalItemResource_PacifiedDino_Iguanodon'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Oviraptor.PrimalItemResource_PacifiedDino_Oviraptor'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_Procoptodon.PrimalItemResource_PacifiedDino_Procoptodon'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/PacifiedDinos/PrimalItemResource_PacifiedDino_RollRat.PrimalItemResource_PacifiedDino_RollRat'" 1 0 false
```
</details>

#### Mutating Genomes
<details><summary>------- Info ---------</summary>

Created with the Genome Harvester, and come in Stat and Color variants, and can only be used on dinos of the same species as the one they were harvested from.

Stat Mutating Genomes boost the base stats similar to mutations of the dino they are used on.

Color Mutating Genomes randomize one of the eligible color zones on the dino they are used on.

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/MutatingGenomes/PrimalItemResource_StatMutatingGenome.PrimalItemResource_StatMutatingGenome'" 1 0 false
```
```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Resources/MutatingGenomes/PrimalItemResource_ColorMutatingGenome.PrimalItemResource_ColorMutatingGenome'" 1 0 false
```
</details>

### Tools 
#### Equipment Reconstructor
<details><summary>------- Info ---------</summary>

Like Pliers, but so much better!

When used, this tool consumes Black Pearls and/or Element Shards to charge itself. Once charged, any damaged piece of armor it is used on will instantly become as good as new!

The amount of charge consumed to repair armor depends on how much the armor needs to be repaired, and what kind of armor it is.

*Usage may void warranties*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Tools/EquipmentReconstructor/PrimalItem_EquipmentReconstructor.PrimalItem_EquipmentReconstructor'" 1 0 false
```
</details>

#### Pacification Injector
<details><summary>------- Info ---------</summary>

For when a club is too primitive.

The Pacification Injector contains a powerful narcotic concoction capable of putting any tamed dinos into a near-catatonic state. This state allows them to be used in the creation of certain structures.

Only strong "high level" dinos can be pacified, as weaker ones tend to have...complications.

For best results, carefully perform the injection through your dino's radial menu. Remember that once a dino has been pacified, it cannot be restored to its original state.

*Pacification is not covered by most health insurance providers*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Tools/PacificationInjector/PrimalItem_WeaponPacificationInjector.PrimalItem_WeaponPacificationInjector'" 1 0 false
```
</details>

#### Transfer Chute
<details><summary>------- Info ---------</summary>

Because moving items by hand is boring.

The Transfer Chute is a revolution in item transfer and sorting technology! Simply aim to select a source inventory, then fire to transfer items to a destination inventory. Pressing the Drag key (G) will set yourself as the source inventory so you can easily transfer resources, and only resources, out of your inventory.

But wait, there's more! The Transfer Chute can be reloaded (R) to switch to and from Linking mode. In this mode, the same selection controls apply (except structures cannot be selected), but instead of a one time item transfer, a persistent link is created that regularly transfers resources from the source to the destination!

*User is liable for any items lost in tranzit*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Tools/TransferChute/PrimalItem_WeaponTransferChute.PrimalItem_WeaponTransferChute'" 1 0 false
```
</details>

#### Genome Harvester
<details><summary>------- Info ---------</summary>

Why wait for mutations when you can force them?

The Genome Harvester rapidly (and destructively) cycles through the genetic code of its target, converting them into two hyper-potent genome sequences. The first is capable of instantly improving the capabilities of any dino of the same species as the now-deceased original dino, while the second causes dramatic skin, scale, feather, and hair pigmentation shifts!

Due to the temperamental nature of genetic manipulation, only the strongest of dinos can be harvested for Mutating Genomes. Additionally, dinos bred in captivity are ineligible due to a lack of genetic diversity.

*In the event of uncontrollable over-mutation, user is solely responsible for any destruction of nearby coastal cities*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Items/Tools/GenomeHarvester/PrimalItem_WeaponGenomeHarvester.PrimalItem_WeaponGenomeHarvester'" 1 0 false
```
</details>

### Structures:
#### Communal Nest
<details><summary>------- Info ---------</summary>

Turns out dinos are better at sharing than we thought...

The Communal Nest ensures that all your dinos' eggs stay safe and sound under one roof, thanks to the hard work of the integrated Oviraptor. Stored eggs are also kept from spoiling and are slowly incubated. The Oviraptor can even be instructed to only pick up specific eggs via the radial wheel menu!

*User is responsible for any over-hatching that may occur*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Structures/CommunalNest/PrimalItemStructure_CommunalNest.PrimalItemStructure_CommunalNest'" 1 0 false
```
</details>

#### Crop Silo
<details><summary>------- Info ---------</summary>

It ain't much, but it's honest work.

Crop Silos are a quintessential part of every farm, capable of storing large amounts of freshly grown crops and berries without letting them rot. They even have an integrated Iguanodon that collects from nearby crop plots so you don't have to!

*Not for use with missiles or long-range explosives*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Structures/CropSilo/PrimalItemStructure_CropSilo.PrimalItemStructure_CropSilo'" 1 0 false
```
</details>

#### Dino Daycare
<details><summary>------- Info ---------</summary>

Parenting is tough, so let someone else do it!

The Dino Daycare takes care of your baby dinos while you're busy adventuring. Not only does it feed baby dinos, it also claims them for you when they are born! Additionally, it can be trained to only claim dinos of a specific species, and cull unnamed babies that are below a certain level. As a bonus on top of all of that, it can even imprint them if given Rare Flowers; all thanks to the built-in Procoptodon and its caring, nurturing nature.

*Usage waves right to complain on how dinos are raised and taught*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Structures/DinoDaycare/PrimalItemStructure_DinoDaycare.PrimalItemStructure_DinoDaycare'" 1 0 false
```
</details>

#### Honey Barrel
<details><summary>------- Info ---------</summary>

Apparently honey's longevity was greatly exaggerated.

The Honey Barrel keeps any honey inside it fresh indefinitely thanks to a specialized patent-pending internal coating. Additionally, it can automatically collect honey from nearby friendly hives and dinos.

*No promises are made on the taste or safety of honey stored in Honey Barrels*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Structures/HoneyBarrel/PrimalItemStructure_HoneyBarrel.PrimalItemStructure_HoneyBarrel'" 1 0 false
```
</details>

#### Industrial Composter
<details><summary>------- Info ---------</summary>

A solution to all your feces-related woes!

Not only does the Industrial Composter have more capacity and a faster conversion rate than its primitive counterpart, but it also can automatically collect nearby feces and distribute produced fertilizer. All of this is thanks to the integrated Dung Beetle's incredible work-ethic.

The Dung Beetle also enables fertilizer production without thatch, at an admittedly slower rate.

*Produced fertilizer still not suitable for human consumption*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Structures/IndustrialComposter/PrimalItemStructure_IndustrialComposter.PrimalItemStructure_IndustrialComposter'" 1 0 false
```
</details>

#### Packager
<details><summary>------- Info ---------</summary>

Proper packing makes a world of difference.

The Packager uses electricity to compress and pack regular resources into pallets which are lighter and more compact, making them far easier to transport from place to place. It can also collect resources from nearby structures and dinos automatically. 

Advanced specialized internal components reduce the weight of all pallets inside the Packager, but also cause it to take much longer to pick up after being activated.

*Stamps not required!*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Structures/Packager/PrimalItemStructure_Packager.PrimalItemStructure_Packager'" 1 0 false
```
</details>

#### Snail Sanctuary
<details><summary>------- Info ---------</summary>

A safe home for our slimy friends!

Achatinas are some of the most useful dinos out there, but they can be a pain to take care of and protect. The Snail Sanctuary fixes both of those problems by automatically producing and collecting paste, while keeping the Achatina fed on the Veggie Cakes used in the construction of the Sanctuary. Infinite Cementing Paste anyone?

*Do not poke the glass, snail may bite*

```
cheat giveitem "Blueprint'/Game/Mods/RosesUtilities/Structures/SnailSanctuary/PrimalItemStructure_SnailSanctuary.PrimalItemStructure_SnailSanctuary'" 1 0 false
```
</details>

### Features
#### Slaughtering Tamed Dinos
<details><summary>------- Info ---------</summary>

Any tamed dino can be Slaughtered from their MultiUse menu while holding a Sickle. Slaughtering works the same way it does with an Ovis, killing the dino instantly.

For obvious reasons, this only works on dinos you own.

Additionally you can choose to Slaughter Many, which has the same effect as Slaughter, but affects all dinos of the same species as the original in a ~3 foundation radius. Slaughter Many also ignores dinos that are: named, have saddles, or are mating, in an attempt to prevent accidentally killing important dinos.

</details>

#### Admin Commands
<details><summary>------- Info ---------</summary>

Admins can use the following commands to receive all Rose Utilities items or to receive all items and materials to test them with, respectively.

```
cheat ScriptCommand RUGiveAll
```
```
cheat ScriptCommand RUTest
```
</details>
