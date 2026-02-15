# EvidenceIndex verification report (BBScan)

- generated_at: `2026-02-15T08:13:21Z`
- bbscan_version: `0.3.92`
- client_build: `12340`
- savedvars: `E:\Ascension Launcher\resources\client\WTF\Account\CtrlAlt\SavedVariables\BBScan.lua`
- apiindex: `E:\Ascension Launcher\resources\client\Interface\AddOns\BBScan\Core\ApiIndex.lua`

Entries: **1560**

## Case-collisions

These entries differ only by case (can break on case-sensitive FS or tooling):

- C_Quest.IsQuerying, C_Quest.isQuerying

## Mixed dot/colon usage in Interface

Interface call-sites use both `.` and `:` for the same member. Treat as unsafe until confirmed (or split by context).

Count: **0**


## Interface vs trace call-style mismatch

Observed calls disagree with Interface `op`. This can indicate different implementations, wrapper tables, or hook artifacts.

Count: **0**


## Interface-called but namespace is non-table at runtime (likely false positive)

Runtime presence scan reports `type(namespace)` is not `table`/`userdata`, so the Interface match is likely a constant (e.g. `C_FOO` string) used with a Lua method like `:format(...)`.

Count: **5**

- `C_RealmMerge.GetAvailableOptions`
- `C_RealmMerge.GetTargetRealm`
- `C_RealmMerge.IsMergeAvailable`
- `C_RealmMerge.NeedsSetTargetRealm`
- `C_RealmMerge.SetTargetRealm`

## Interface-called but missing at runtime

UI code calls it, but runtime scan didn't find it. Common causes: LoadOnDemand not loaded, gated system, or seasonal feature.

Count: **5**

- `C_Aura.UnitAura`
- `C_CharacterAdvancement.IsTraitID`
- `C_ItemSet.GetItemSetName`
- `C_Scenario.GetScenarioInfo`
- `C_Serialize.DeserializeCompressForPrint`

## Interface-called but runtime not checked yet

Interface evidence exists, but there is no per-member runtime presence data in this EvidenceIndex (run `scan runtime_members`). Treat as *unknown* rather than missing.

Count: **0**


## Trace-called but runtime not checked yet

apitrace observed calls, but this EvidenceIndex lacks per-member runtime presence. This usually means the presence scan was run in a different session/context (or not run).

Count: **0**


## Interface-called but runtime kind is not function

Interface evidence suggests callable, but runtime scan reports non-function. Usually indicates stale evidence or table-metamethod behavior.

Count: **0**


## Interface-called and present (index-only) but not a function

Index-only presence scan found a non-function (table/field) where Interface evidence suggests callable. This is usually a false-positive call-site parse or a metamethod/wrapper edge case.

Count: **0**


## Runtime function never called (no evidence)

Function exists at runtime but was neither called in Interface call-sites nor observed via apitrace. Likely niche, gated, or new.

Count: **292**

- `C_AccountInfo.IsGuide`
- `C_AccountInfo.IsNewcomer`
- `C_Appearance.GetItemSetAppearanceID`
- `C_AppearanceCollection.CollectItemAppearance`
- `C_AppearanceOutfit.DeleteOutfit`
- `C_AppearanceOutfit.GetAppearanceOutfits`
- `C_AppearanceOutfit.SaveOutfit`
- `C_AssetQueryService.TryCacheCreature`
- `C_AssetQueryService.TryCacheItem`
- `C_AssetQueryService.TryCacheQuest`
- `C_BugTracker.GetReportCategory`
- `C_BugTracker.GetReportDescription`
- `C_BugTracker.GetReportPriority`
- `C_BugTracker.GetReportTitle`
- `C_BugTracker.IsReportPublic`
- `C_BuildCreator.CanDeactivateBuild`
- `C_BuildCreator.DeactivateBuild`
- `C_BuildCreator.ExportBuild`
- `C_BuildCreator.GetActiveSpecForBuild`
- `C_BuildDraft.IsDraftableBuild`
- `C_BuildDraft.IsDraftedBuild`
- `C_BuildEditor.CanAddRandomEnchant`
- `C_BuildEditor.CanRemoveArmorType`
- `C_BuildEditor.CanRemoveRandomEnchant`
- `C_BuildEditor.CanRemoveWeaponType`
- `C_BuildEditor.CanSetArmorTypeComment`
- `C_BuildEditor.CanSetEnchantLevel`
- `C_BuildEditor.CanSetRandomEnchantComment`
- `C_BuildEditor.CanSetRandomEnchantStacks`
- `C_BuildEditor.CanSetSpellComment`
- `C_BuildEditor.CanSetWeaponTypeComment`
- `C_BuildEditor.ExportPendingBuild`
- `C_BuildEditor.GetNumFilteredEntries`
- `C_BuildEditor.GetQualityInfo`
- `C_BuildEditor.ImportBuild`
- `C_BuildEditor.ImportCurrentBuild`
- `C_BuildEditor.SetComment`
- `C_BuildEditor.SetEnchantLevel`
- `C_CVar.GetCVarBitfield`
- `C_CVar.SetCVarBitfield`
- ... (252 more)

## Ambiguous call-style (no Interface and no trace)

Runtime sees a function, but there is no evidence for `.` vs `:` yet. Avoid calling without additional proof (apitrace or interface update).

Count: **292**

- `C_AccountInfo.IsGuide`
- `C_AccountInfo.IsNewcomer`
- `C_Appearance.GetItemSetAppearanceID`
- `C_AppearanceCollection.CollectItemAppearance`
- `C_AppearanceOutfit.DeleteOutfit`
- `C_AppearanceOutfit.GetAppearanceOutfits`
- `C_AppearanceOutfit.SaveOutfit`
- `C_AssetQueryService.TryCacheCreature`
- `C_AssetQueryService.TryCacheItem`
- `C_AssetQueryService.TryCacheQuest`
- `C_BugTracker.GetReportCategory`
- `C_BugTracker.GetReportDescription`
- `C_BugTracker.GetReportPriority`
- `C_BugTracker.GetReportTitle`
- `C_BugTracker.IsReportPublic`
- `C_BuildCreator.CanDeactivateBuild`
- `C_BuildCreator.DeactivateBuild`
- `C_BuildCreator.ExportBuild`
- `C_BuildCreator.GetActiveSpecForBuild`
- `C_BuildDraft.IsDraftableBuild`
- `C_BuildDraft.IsDraftedBuild`
- `C_BuildEditor.CanAddRandomEnchant`
- `C_BuildEditor.CanRemoveArmorType`
- `C_BuildEditor.CanRemoveRandomEnchant`
- `C_BuildEditor.CanRemoveWeaponType`
- `C_BuildEditor.CanSetArmorTypeComment`
- `C_BuildEditor.CanSetEnchantLevel`
- `C_BuildEditor.CanSetRandomEnchantComment`
- `C_BuildEditor.CanSetRandomEnchantStacks`
- `C_BuildEditor.CanSetSpellComment`
- `C_BuildEditor.CanSetWeaponTypeComment`
- `C_BuildEditor.ExportPendingBuild`
- `C_BuildEditor.GetNumFilteredEntries`
- `C_BuildEditor.GetQualityInfo`
- `C_BuildEditor.ImportBuild`
- `C_BuildEditor.ImportCurrentBuild`
- `C_BuildEditor.SetComment`
- `C_BuildEditor.SetEnchantLevel`
- `C_CVar.GetCVarBitfield`
- `C_CVar.SetCVarBitfield`
- ... (252 more)

