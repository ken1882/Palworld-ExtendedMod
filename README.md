# Palworld - Extended Mod

Custom mod for Palworld using UnrealPak and UAssetGUI


### BuildObjects

| Image | ID | Name | Slots (default) | Slots (modded) |
| -------- | --- | -------- | -------- | -------- |
| ![](https://hackmd.io/_uploads/HJioAhJ8yl.png) | ItemChest | Wooden Chest | 10 | 24 |
| ![](https://hackmd.io/_uploads/r1EcrpJ8ye.png)| ItemChest_02 | Metal Chest | 24 | 42 |
| ![](https://hackmd.io/_uploads/Skd_LaJL1l.png) | ItemChest_03 | Refined MetalChest | 40 | 84 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_ItemChest_04.webp) | ItemChest_04 | Advanced Chest | 54 | 240 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_CoolerBox.webp) | CoolerBox | Cooler Box | 10 | 24 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Refrigerator.webp) | Refrigerator | Refrigerator | 25 | 72 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Barrel_Wood.webp) | Barrel_Wood | Wooden Barrel | 8 | 20 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Box_Wood.webp) | Box_Wood | Wooden Box | 10 | 24 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Box01_Iron.webp) | Box01_Iron | Small Container | 10 | 24 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Box02_Iron.webp) | Box02_Iron | Cloth Covered Container | 10 | 24 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Container01_Iron.webp) | Container01_Iron | Large Conatiner | 40 | 240 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Shelf_Cask_Wood.webp) | Shelf_Cask_Wood | Wooden Barrel Shelf | 15 | 36 |
| ![](https://hackmd.io/_uploads/H1PD36k8yg.png) | Shelf_Hang01_Wood | Wooden Wall Shelf | 2 | 8 |
| ![](https://hackmd.io/_uploads/HJYtnTk81l.png) | Shelf_Wood | Wooden Shelf | 8 | 24 |
| ![](https://hackmd.io/_uploads/BJIchTJIJg.png) | Shelf01_Wall_Stone | Antique Wall Cabinet | 3 |  12|
| ![未命名](https://hackmd.io/_uploads/Bkn3naJUkg.png) | Shelf01_Stone | Antique Bookshelf | 10 | 28 |
| ![未命名-1](https://hackmd.io/_uploads/BJAa3p1LJg.png) | Shelf02_Stone | Antique Wardrobe | 20 | 42 |
| ![未命名](https://hackmd.io/_uploads/HJ1JppJ8kg.png) | Shelf03_Stone | Antique Chest | 10 | 24 |
| ![未命名-1](https://hackmd.io/_uploads/SkTbT61Ukg.png) | Shelf04_Stone | Antique Side Chest | 7 | 18 |
| ![未命名](https://hackmd.io/_uploads/BkeNa618yg.png) | Shelf05_Stone | Antique Cabinet | 12 | 30 |
| ![未命名](https://hackmd.io/_uploads/SyDfp6kIyg.png) | Shelf06_Stone | Antique Long Cabinet | 15 | 36 |
| ![未命名-1](https://hackmd.io/_uploads/Sk7mpTyLke.png) | Shelf07_Stone | Large Antique Cabinet | 15 | 40 |
| ![](https://hackmd.io/_uploads/H1QBh61Lkl.png) | Shelf01_Wall_Iron | Iron Wall Shelf | 3 | 12 |
| ![](https://hackmd.io/_uploads/ByamnaJL1e.png) | Shelf01_Iron | Iron Shelf | 15 | 36 |
| ![](https://media.discordapp.net/attachments/267593694272552961/1323191222990540800/T_icon_buildObject_Shelf02_Iron.webp?ex=67739d5b&is=67724bdb&hm=4e1be2f217b314e8bc092e798b242a9ef9680a884eef8b1313d8e82ad8ecf66b&=&format=webp&width=614&height=614) | Shelf02_Iron | Long Iron Shelf | 15 | 30 |
| ![](https://media.discordapp.net/attachments/267593694272552961/1323191076286365747/T_icon_buildObject_Shelf03_Iron.webp?ex=67739d38&is=67724bb8&hm=9d29f928fdbaab9b388dbff9ed4a3e6b0383233f58ed7af002963aa2eaa1ddb2&=&format=webp&width=614&height=614) | Shelf03_Iron | Orange Locker | 20 | 42 |
| ![](https://cdn.discordapp.com/attachments/267593694272552961/1323190752334839861/T_icon_buildObject_Shelf04_Iron.webp?ex=67739ceb&is=67724b6b&hm=76e614ffc33bb4b936ca75739facec5241c4d7cd932227b2906c14ed3a64cfba&) | Shelf04_Iron | Locker | 20 | 40 |
| ![](https://cdn.paldb.cc/image/Pal/Texture/BuildObject/PNG/T_icon_buildObject_Tansu.webp) | Tansu | Japanese Chest | 10 | 30 |

### Blueprint/System/PalGameSettings

```
"RarePal_AppearanceProbability": 0.1, // modded: 1.0
"GuildChestSlotNum": 54, // modded: 540

```

### DataTable/BaseCamp/DT_BaseCampLevelData
* BaseCampMaxNumInGuild:
* Level. Num
    1. 1
    2. 1
    3. 2
    4. 2
    5. 3
    6. 3
    7. 3
    8. 4
    9. 4
    10. 5
    11. 5
    12. 6
    13. 5
    14. 7
    15. 7
    16. 8
    17. 8
    18. 9
    19. 9
    20. 10
    21. 10
    22. 10
    23. 11
    24. 11
    25. 12
    26. 13
    27. 13
    28. 14
    29. 14
    30. 15


### DataTable/ItemShop/DT_ItemShopCreateData_Common

* MerchantID
    * Index. GoodsID (PriceOverride)

* Village_Shop
    0~7. Blueprint_Headxxx_5 (50000)
    29. IceOrgan
    30. PalItem_ColorfulBird
    31. PalItem_MopBaby
    32. PalItem_RaijinDaughter
    33. PalItem_PlantSlime
    34. PalItem_PinkRabbit
    35. PalItem_NegativeOctopus
    36. Mushroom (100)
    37. PalItem_CatMage
    38. PalItem_CaptainPenguin
    39. PalItem_LizardMan
    40. Sweet
* Desert_Shop / Volcano_Shop
    17. PotatoSeeds
    18. CarrotSeeds
    19. OnionSeeds
    20. Poppy
    21. PalUpgradeStone (300)
    22. PalUpgradeStone2 (800)
    23. PalUpgradeStone3 (2000)
    24. PalUpgradeStone4 (5000)
    25. StatusPointResetSan
    26. Potion_Low
    27. Potion
    28. Potion_High
    29. Potion_Extreme (5000)
* Desert_Shop2 / Volcano_Shop2
    0~6. Blueprint_Headxxx_5 (50000)
    19. Arrow_Poison
    20. ExplosiveBullet
    21. FlamethrowerBullet
    22. LaserBullet
    23. GatlingBullet
    24. GrenadeBullet
    25. MissileBullet
    26. ReinforcedArrow (150)
    27. SFArrow (2000)
    28. LaserGatlingBullet (1200)
    29. EnergyLauncherBullet (20000)
* Wander_Shop
    .1. PalCrystal_Ex (3000)
    2. AncientParts2 (8000)
    3. PredatorCrystal (15000)
    4. Mushroom (100)
    5. PoisonMushroom (150)
    6. CaveMushroom (300)
    7. Honey
    23. Meat_BerryGoat
    24. Meat_Boar
    25. Meat_ChickenPal
    26. Meat_CowPal
    27. Meat_Deer
    28. Meat_Eagle
    29. Meat_GrassMammoth
    30. Meat_IceDeer
    31. Meat_Kelpie
    32. Meat_LazyCatfish
    33. Meat_SakuraSaurus
    34. Meat_SheepBall
* Medal_Shop
    19. Rankup_1 (30)
    20. Rankup_2 (125)
    21. Rankup_3 (1000)
    22. WorkSuitability_AddTicket_EmitFlame (1000)
    23. WorkSuitability_AddTicket_Watering (1000)
    24. WorkSuitability_AddTicket_Seeding (1000)
    25. WorkSuitability_AddTicket_GenerateElectricity (1000)
    26. WorkSuitability_AddTicket_Collection (1000)
    27. WorkSuitability_AddTicket_Deforest (1000)
    28. WorkSuitability_AddTicket_Mining (1000)
    29. WorkSuitability_AddTicket_ProductMedicine (1000)
    30. WorkSuitability_AddTicket_Cool (1000)
    31. WorkSuitability_AddTicket_Transport (1000)

### DataTable/Character/DT_PalDropItem_Common
* MimicDog000
    * DogCoin: 70~232
* MimicDog010
    * DogCoin: 70~232
* MimicDog020
    * DogCoin: 100~300
* MimicDog030
    * DogCoin: 120~351
* MimicDog040
    * DogCoin: 140~380
* MimicDog050
    * DogCoin: 152~420
* PREDATOR_xxx
    * PredatorCrystal: n\*3 ~ m\*10 
    * PalUpgradeStone4: n\*3 ~ m\*10 
* Legendary Schematics: 3% -> 10%
    * BOSS_KingAlpaca: Blueprint_WeakerBow_5
    * BOSS_QueenBee: Blueprint_CopperArmor_5
    * BOSS_Ronin: Blueprint_BowGun_5
    * BOSS_SaintCentaur: Blueprint_StealArmorCold_5
    * BOSS_SkyDragon: Blueprint_Musket_5
    * BOSS_VioletFairy: Blueprint_DoubleBarrelShotgun_5
    * BOSS_WeaselDragon: Blueprint_ClothArmor_5
    * BOSS_ThunderBird: Blueprint_HandGun_Default_5
    * BOSS_Suzaku: Blueprint_PumpActionShotgun_5
    * BOSS_LilyQueen_Dark: Blueprint_IronArmorCold_5
    * BOSS_JetDragon: Blueprint_Launcher_Default_5
    * BOSS_IceHorse_Dark: Blueprint_LaserRifle_5
    * BOSS_IceHorse: Blueprint_StealHelmet_5
    * BOSS_HerculesBeetle: Blueprint_CopperHelmet_5
    * BOSS_GrassRabbitMan: Blueprint_SingleShotRifle_5
    * BOSS_FengyunDeeper: Blueprint_MakeshiftHandgun_5
    * BOSS_DarkScorpion: Blueprint_IronHelmet_5
    * BOSS_CaptainPenguin: Blueprint_FurHelmet_5
    * BOSS_BlackMetalDragon: Blueprint_IronArmorHeat_5
    * BOSS_BlueDragon: Blueprint_FurArmor_5
    * BOSS_BlackCentaur: Blueprint_StealArmorHeat_5

### DataTable/Item/DT_ItemLotteryDataTable
* Oilrig_Large_02#3
    * AncientParts2
        * Weight: 90 -> 50
        * Number: 1 ~ 5 -> 5 ~ 50
    * Weight: 1 -> 5
        * Blueprint_GuidedMissileLauncher_5
        * Blueprint_GatlingGun_5
        * Blueprint_GrenadeLauncher_5
        * Blueprint_LaserRifle_5
        * Blueprint_Launcher_Default_5
        * Blueprint_SemiAutoShotgun_5
        * Blueprint_SemiAutoRifle_5
        * Blueprint_SubmachineGun_5
        * Blueprint_OldRevolver_5
* Oilrig_Large_02#2
    * Crude Oil
        * Number: 50 ~ 150 -> 300 ~ 1000
* Oilrig_Large_02#1
    * Blueprint_*
        * Weight: n -> 5
* Oilrig_Large_01#2
    * Money
        * Number: 100 ~ 200 -> 10000 ~ 20000
    * CrudeOil
        * Number: 5 ~ 50 -> 50 ~ 500
    * DogCoin
        * Number: 16 ~ 20 -> 160 ~ 300
* Oilrig_Large_01#1
    * PalUpgradeStone4
        * Number: 1 -> 10 ~ 50
        * Weight: 40 -> 30
    * Money
        * Number: 600 ~ 1600 -> 12000 ~ 28000
        * Weight: 30 -> 15
    * TreasureBoxKey03
        * Number: 1 -> 10
        * Weight: 20 -> 1
    * LuxuryMedicines
        * Number: 1 -> 5
        * Weight: 10 -> 2
    * Potion_Extreme
        * Number: 1 -> 5
    * Blueprint_*
        * Weight: n -> 6
