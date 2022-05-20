---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Transparent Pods (PODS)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Transparent Pods(PODS)

[Home](./index.md)

Adds eight (8) parts. Transparent Command Pods and other parts by nli2work for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the TransparentPods folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/TransparentPods`
* Extract the package's `TransparentPods/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/TransparentPods` --> `<KSP_ROOT>/GameData/TransparentPods`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/TransparentPods`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/TransparentPods`
* Extract the package's `GameData/TransparentPods` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData/TransparentPods` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/TransparentPods`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [TransparentPods]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * changelog.md
      * License.txt
      * readme.htm
      * TransparentPods.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
