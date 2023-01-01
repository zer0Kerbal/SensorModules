---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Sensor Modules (SENS)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Sensor Modules (SENS)

[Home](./index.md)

Going to the dark side of [random planet] and worried about running out of snacks to go with your Jeb Nuclear Coffee!? Look no further, we've got the perfect snack luggage!!  For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `HotBeverage` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/HotBeverage/SensorModules`
* Extract the package's `HotBeverage` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/HotBeverage` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/HotBeverage/SensorModules`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/HotBeverage/SensorModules`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/HotBeverage/SensorModules`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [HotBeverage]
      + [HotBeverageInc]
        + [Agencies]
          ...
        + [Flags]
          ...
        ...
      + [SensorModules]
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Localization]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-ND-4.0.txt
        * changelog.md
        * SensorModules.version
        * ManualInstallation.htm
        * readme.htm
        ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [HotBeverageInc](https://forum.kerbalspaceprogram.com/index.php?/topic/208353-*/)