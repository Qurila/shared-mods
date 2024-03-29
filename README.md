# Shared Anno 1800 Mods

Shared mods from Kurilas's Collection.

## Shared General Modules

Contains adjustments of the UI elements for modules.

Instead of agricultural terms and icons, more general ones are used (as far as possible).

### Use General Modules

Add the following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_general_modules_kurila.zip"
]
```

## Shared General Permits

Contains adjustments to the UI elements of the building permits.

Instead of only Great Eastern and Advanced Pier, they are now designed for ships/harbour structures and industrial buildings.

### Use General Permits

Add the following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_general_permits_kurila.zip"
]
```

## Shared Info Parts

Contains text modules for an extended InfoDescription

There are also some minor changes to vanilla texts.

![](./doc/infodescription.jpg)

### Use Info Parts in your Mod

For more information on the use of extended InfoDescription, read the mod's readme.
<https://github.com/Qurila/shared-mods/tree/main/%5BShared%5D%20Info%20Parts%20(Kurila)>

Add the following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_info_parts_kurila.zip"
]
```

## Shared Products

Shared products from Kurila, Jakob and Lrds42.

These products are planned as additional productions and have little influence on the vanilla game.

Contains products with definition, icon and Docklands information.

Icon | GUID | Name |
---|---|---|
<img src="./shared_products_kurila/data/products/apples/icon_apples.png" width="20" /> | 1404420032 | Apples |
<img src="./shared_products_kurila/data/products/coloured-tiles/icon_tiles.png" width="20" /> | 1500301073 | Coloured Tiles |
<img src="./shared_products_kurila/data/products/liqueur/icon_liqueur.png" width="20" /> | 1500300040 | Liqueur |
<img src="./shared_products_kurila/data/products/sandwiches/icon_sandwich.png" width="20" /> | 1500300060 | Sandwiches |
<img src="./shared_products_kurila/data/products/smoked-fish/icon_smoked_fish.png" width="20" /> | 1500300020 | Smoked Fish |
<img src="./doc/icon_wooden_ring_16.png" width="20" /> | 1500010150 | Wooden Jewelry |

## Shared Products Extended

Shared extended products from Kurila and Lrds42.

These products are planned as intermediate stages to existing production chains and have a greater impact on the vanilla game.

Contains products with definition, icon and Docklands information.

Icon | GUID | Name |
---|---|---|
<img src="./doc/icon_cattle_16.png" width="20" /> | 1404422300 | Cattle |
<img src="./shared_products_extended_kurila/data/products/cherries/icon_cherries.png" width="20" /> | 1404420030 | Cherries |
<img src="./doc/icon_cloth_16.png" width="20" /> | 1500020000 | Wool Fabric |
<img src="./doc/icon_wool_16.png" width="20" /> | 1500020010 | Sewing Thread |
<img src="./shared_products_extended_kurila/data/products/barrels/icon_barrels.png" width="20" /> | 1500300000 | Barrels |
<img src="./doc/icon_wansa_wood_16.png" width="20" /> | 1500301150 | Wanza Wood |
<img src="./shared_products_extended_kurila/data/products/cherry-timber/icon_cherry_planks.png" width="20" /> | 1500301151 | Cherry Timber |

### Use Products in your Mod

Add one/all of the following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_products_kurila.zip",
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_products_extended_kurila.zip"
]
```

Products are not unlocked automatically, you need to unlock them yourself, if you use the products.

## Shared Recipe Buildings

This mods convert vanilla buildings to recipe buildings.

This way, modders who plan new recipes can all build on the same base and there are no compatibility problems.

### Converted buildings

- Lumberjack
- Marquetry Workshops
- Sawmills (Inlcuding Mod Buildings)
- Schnapps Distilleries (Inlcuding Mod Buildings)
- (Beer)Breweries
- Wool Farms (Sheep and Alpaca)

### Use Recipe Buildings in your Mod

Add the desired dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_lumberjack_kurila.zip"

  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_sawmill_kurila.zip"
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_sawmill_river_kurila.zip"
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_sawmill_industrial_kurila.zip"

  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_marquetry_workshop_kurila.zip"

  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_beer_brewery_kurila.zip"

  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_schnapps_kurila.zip"
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_schnapps_industrial_kurila.zip"

  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_wool_farms_kurila.zip"
]
```

## Shared Vegetables Integration

This mod replaces peppers with vegetables instead of having vegetables and peppers separately.

The pepper farm has been changed to a vegetable farm. The vegetable icon has been extended with paprika.

### Use Vegetables Integration in your Mod

Add following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_vegetables_integration_kurila.zip",
  "https://github.com/jakobharder/anno1800-shared-mods/releases/download/v3.2.4/shared-products-jakob.zip"
]
```

## Shared UI Change

This mod makes it possible to switch between two different UIs on buildings ingame.

- An example is found in the assets.xml

It should be noted that during the change selected buildings must be selected again to see the new UI.

The trigger code was created by [Serp](https://github.com/Serpens66).

### Use UI Change in your Mod

Add following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_ui_change_kurila.zip"
]
```

## Shared Cherry Sawmill

This mod makes it possible to produce Cherry Timber from Cherry Wood in Sawmills that have been converted into recipe buildings.

### Use Cherry Sawmill in your Mod

Add the following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_cherry_sawmill_kurila.zip",
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_products_extended_kurila.zip",
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_sawmill_kurila.zip",
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_sawmill_river_kurila.zip",
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_sawmill_industrial_kurila.zip"
]
```

## Shared Wanza Sawmill

This mod makes it possible to produce Wanza Timber from Wanza Wood in a new Enbesa Sawmill.

### Use Wanza Sawmill in your Mod

Add the following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_wanza_sawmill_kurila.zip",
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_products_extended_kurila.zip"
]
```

## Shared Clay Works

This mod provides a farmer-level Clay Sink as an early source of Clay and an ingineer-level Clay Mine as a late source of Clay.

### Use Clay Works in your Mod

Add the following dependencies to your `modinfo.json`:

```json
"ModDependencies": [
  "https://github.com/Qurila/shared-mods/releases/download/v6/shared_clay_works_kurila.zip"
]
```

## How to Build

### Build with Visual Studio Code plugin

The mods are made with the [Modding Tools for Anno](https://marketplace.visualstudio.com/items?itemName=JakobHarder.anno-modding-tools) extension for [VS Code](https://code.visualstudio.com/).

Make sure to set `annoMods` settings.

Install the plugin, open a mod folder and press `F1` and choose `Build Anno Mod` or right click on a `modinfo.json` file.

### Build with Node.js

Run the following commands:

```
npm install .
npm run build
npm run package
```
