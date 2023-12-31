# starsmith-expanded-oracles

![GitHub all releases](https://img.shields.io/github/downloads/jendave/starsmith-expanded-oracles/total)
[![Latest Version](https://img.shields.io/github/v/release/jendave/starsmith-expanded-oracles?display_name=tag&sort=semver&label=Latest%20Version)](https://github.com/jendave/starsmith-expanded-oracles/releases/latest)
![Foundry Version](https://img.shields.io/endpoint?url=https://foundryshields.com/version?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjendave%2Fstarsmith-expanded-oracles%2Fmain%2Fmodule.json)
[![License](https://img.shields.io/github/license/jendave/starsmith-expanded-oracles)](LICENSE)

# About
A FoundryVTT compendium of the supplement by Eric Bright adds two additional tables for nearly every table for the Ironsworn: Starforged system.

# Contact
* [Ironsworn/Starforged Discord Server - FoundryVTT Channel](https://discord.com/channels/437120373436186625/867434336201605160)
* [GitHub Repository](https://github.com/jendave/starsmith-expanded-oracles)

# Features and Notes
* Oracle tables from the PDF are included.
* Tables that are copies of the Starforged official tables are included if they are part of Starsmith 1-2, 3-4, 5-6 array.
* Tables that are simply copies of official Starforged tables without the array (some planet and several of the derelict tables for example) are not included since they would be redundant with the standard Starforged System tables.

# Module Installation
To install the module, search for `Starsmith` or `Starforged` in the `Add-On Modules` tab of of the Foundry VTT game setup screen. Then click on `Install`.

Or use this URL and click on `Install`:

```
https://github.com/jendave/starsmith-expanded-oracles/releases/latest/download/module.json
```

# Tabletop Integration
By default, the Oracles will be integrated into the Oracle Tree in the Character Sheet. 
![Character Sheet - Oracles Tree](./docs/oracle-tree-character-sheet.jpg)

If this is not desired, then uncheck the `Enable Oracles in Default Tree` in `Configure Settings` game settings. 
![Module Game Settings](./docs/module-game-settings.jpg)

The Oracles can also be added to the character sheet by using the `Custom Folders` method below.

Macros for Starship Registry Number and Dice rolling can be found in the `Starsmith Expanded Oracles Macros` compendium. Drag and drop any you need into the macro toolbar.

## (Optional Installation) Use Custom Folders to add Character Sheet Oracles 
* If integrating the Starsmith Oracles directly into the default Oracle Tree if not desired, then use this method to add the Starsmith Oracles.
* If it does not already exist, create a `Custom Oracles` folder in `Rollable Tables` tab called:
  * `Custom Oracles` - EN
  * `Oráculos personalizados` - ES
  * `Oracles personnalisés` - FR
  * `Własne Wyrocznie` - PL

Open the `Starsmith Expanded Oracles` compendium and copy the folders into the `Rollable Tables` `Custom Oracles` folder.

![Rollable Tables - Custom Oracles](./docs/custom-oracles-rollable-tables.jpg)

The Oracles will be available in the Character sheet under `Custom Oracles`.

![Character Sheet - Custom Oracles](./docs/custom-oracles-character-sheet.jpg)

# Credits
[Starsmith Expanded Oracles](https://www.drivethrurpg.com/product/417619/Starsmith-Expanded-Oracles) by Eric Bright are licensed for use under the [Creative Commons Attribution 4.0 International License (CC-BY)](https://creativecommons.org/licenses/by/4.0/).

Original oracles by Shawn Tomkin from [Ironsworn: Starforged](https://preview.drivethrurpg.com/en/product/391653/ironsworn-starforged) are used under the [Creative Commons Attribution 4.0 International License (CC-BY)](https://creativecommons.org/licenses/by/4.0/).

Module by David Hudson and licensed for use under the [MIT license](https://opensource.org/license/mit/).

The Starship Registry number generator macro was contributed by @el_reverend (Discord).

Licenses and permissions for the macros are listed in the source code.

# Acknowledgements
Many thanks to Ben Straub for his fantastic [Ironsworn & Starforged Game System](https://foundryvtt.com/packages/foundry-ironsworn).

## Modules
The following modules were used in the development process
* [foundryvtt-importer module](https://github.com/EthanJWright/foundryvtt-importer)
* [Mana's Compendium Importer](https://gitlab.com/mkahvi/fvtt-compendium-importer)
* [DF Manual Rolls](https://foundryvtt.com/packages/df-manual-rolls)
