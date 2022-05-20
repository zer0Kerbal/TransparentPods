# Changelog  

| modName    | Transparent Pods (PODS)                                           |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | nli2work and zer0Kerbal                                           |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/187495-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/TransparentPods)        |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/TransparentPods)      |
| spacedock  | (https://spacedock.info/mod/2212)                                 |
| ckan       | TransparentPods                                                   |

## Version 1.2.3.4 - `<>`

* 17 May 2022
* for KSP 1.12.3

### Added

* [tags]
* stock
  * //#autoLOC_500863 = a.r.m arm asteroid capture cla* ect dock fasten grab join klaw nasa
* [scale] = 1

* [JSIAdvTransparentPods.cfg]
  * moved from part.cfg's
* [RasterPropMonitor.cfg]
  * moved from part.cfg's

### Updated

* [crashTolerance]
  * 50 is the correct amount
* [TransparentPods.version]
  * removed KSP_VERSION_MAX

### Parts

* updated config
* linted
* Added
  * [DRAG_CUBE]
  * [ModuleColorChanger]
  * [ModuleConductionMultiplier]
  * [ModuleCargoPart]
    * [cycloPod.cfg]
    * [monoPod.cfg]
    * [handrail1.cfg]
    * [handrail2.cfg]
    * [microKlaw.cfg]
    * [microLegRadial.cfg]
    * [microLegVentral.cfg]
  * [ModuleInventoryPart]
    * [panoPod.cfg]

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* updates #33 - Asset Updates

### Part Localization

* create agency
* run localizer
* Parts to localize
  * [monoPod.cfg]
  * [microLegVentral.cfg]
  * [handrail1.cfg]
  * [handrail2.cfg]
  * [microLegRadial.cfg]
  * [microKlaw.cfg]
  * [cycloPod.cfg]
  * [panoPod.cfg]

### docs/

* Update
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
* Add
  * [404-petunia.md]
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [PartInvoice.md] v1.1.3.1
  * [_config.yml]

* Status
* #4 - Fix version file URL property - contributed by HebaruSan
* #10 - [ImgBot] Optimize images - contributed by imgbot[bot]

---

## Version 1.2.3.3-release - `<Klaws'R'Us>`

* 2019-10-16
* Released for Kerbal Space Program 1.7.3

### Updated

* MicroKlaw
  * move from Utility to Coupling
  * adjust cost from 4050 to 405
  * adjust entryCost from 8000 to 4400
  * adjust angularDrag from 4 to 1
  * adjust maxTemp from 3000 to 2000
  * add fuelCrossFeed = False
  * adjust breakingForce from 1500 to 50
  * adjust breakingTorque from 1500 to 50
  * change title from 'Micro Klaw' to 'MicroKlaw'
  * adjusted ModuleAnimateGeneric to reflect new part name
  * add ModuleToggleCrossfeed (false) (techRequired = fuelSystems)
  * ModuleGrappleNode nodeType was size2, corrected to size1 as per the stock "Advanced Grabbing Unit"

### Removed

* removed
  * Stock-microLegRadial, microLegRadial-KSPWheel
  * [ghost.cfg]
    * added for Stock-microLegRadial, microLegRadial-KSPWheel(+PART microLegRadial)
  * ***[ghost.cfg] patch will be removed next update***

### Added

* [ODFC.cfg] (On Demand Fuel Cells) patch
  * 0.75 EC/s ODFC fuel cell to monoPod
  * 1.5 EC/s ODFC fuel cell to cycloPod
  * 4.45 EC/s ODFC fuel cell to panoPod
  * *ODFC production/consumption subject to balance pass (feedback desired)*

---

## Version 1.2.3.2-release - `<Check out the Space Squids!`>

* 2019-08-29
* Released for Kerbal Space Program 1.7.3

* *unplugging Val's kPod she left hidden under her seat in the CycloPod.* 
  * (maxEC should have been 75 not 70)
  * thank you to ***[Kottabos Games](https://www.youtube.com/user/KottabosGames/videos)*** for spotting the inconsistency and for the review.
  * [KSP Mods - Transparent Command Pods Repressurized](https://youtu.be/mUntbQHC4-g)
* darn extra trailing `/` in url's in Readme

* Status
* #1 - V.1.2.3.2 - contributed by zer0Kerbal
* #2 - V.1.2.3.2 - contributed by zer0Kerbal

---

## Version v.1.2.3.1-release - `<What was lost, is still lost>`

* 2019-08-22
* Released for Kerbal Space Program 1.7.3

### Updates

* missed several references when updating file structure
* added to JPLAdvTransparentPods module in each Pod: "distanceToCameraThreshold = 50"

---

## Version v.1.2.3.0-adoption - `<*Repressurizing*.... Please Stand By... >`

* 2019-08-12
* Released for Kerbal Space Program 1.7.3

### Adopted by zer0Kerbal

* Formerly known as Transparent Command Pods
* Updated all parts to 1.7.3

* Status
* #1 - V.1.2.3.2 - contributed by zer0Kerbal
* #2 - V.1.2.3.2 - contributed by zer0Kerbal

---

## Version 1.2.2 Transparent Pods by nil2work for KSP v0.90

* Original
* Uploaded for posterity and completeness.

---
