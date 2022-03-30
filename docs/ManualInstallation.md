---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.1.0
HBSensorModules (HBSM)
created: 01 Oct 2019
updated: 27 Mar 2022 -->

<!-- based upon work by Lisias -->

# HBSensorModules (HBSM)

Adds Mallet, Survey Stake, Recycler, Disposable Pad, Orbital Dock and Control Reference; and turns Cupola module to Survey Station. Requires SimpleConstruction! for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/HotBeveragesInc/HBSensorModules`
* Extract the package's `HBSensorModules/` folder into your KSP's as follows:
  * `<PACKAGE>/SimpleConstruction` --> `<KSP_ROOT>/GameData/HotBeveragesInc/HBSensorModules`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/HotBeveragesInc/HBSensorModules`
* Extract the package's `GameData/HotBeveragesInc/HBSensorModules` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/HotBeveragesInc/HBSensorModules` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```
<KSP_ROOT>
  [GameData]
    [HotBeveragesInc]
      [HotBeveragesInc]
        [Agencies]
          ...
        [Flags]
          ...
      [HBSensorModules]
        [Assets]
          ...
        [Compatibility]
          ...
        [Config]
          ...
        [Localization]
          ...
        [Parts]
          ...
        1.0.0.0.htm
        changelog.md
        HBSensorModules.version
        License.txt
        readme.htm
    ...
  KSP.log
  ...
```

### Dependencies

* [HotBeverages (HB)][hb]

[hb]:  "Hot Beverages Common Files"
[scon]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-* "SimpleConstruction! (SCON!)"
[mm]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
