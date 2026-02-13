# EvidenceIndex verification report (BBScan)

- generated_at: `2026-02-13T21:39:35Z`
- bbscan_version: `0.3.58`
- client_build: `12340`
- savedvars: `E:\Ascension Launcher\resources\client\WTF\Account\CtrlAlt\SavedVariables\BBScan.lua`
- apiindex: `E:\Ascension Launcher\resources\client\Interface\AddOns\BBScan\Core\ApiIndex.lua`

Entries: **1089**

> NOTE: No `runtime_members` presence data found in this EvidenceIndex.
> The "missing at runtime" signal is *not* confirmed for members yet.
> Run `scan runtime_members` in-game (out of combat), then regenerate EvidenceIndex.

## Mixed dot/colon usage in Interface

Interface call-sites use both `.` and `:` for the same member. Treat as unsafe until confirmed (or split by context).

Count: **0**


## Interface vs trace call-style mismatch

Observed calls disagree with Interface `op`. This can indicate different implementations, wrapper tables, or hook artifacts.

Count: **0**


## Interface-called but namespace is non-table at runtime (likely false positive)

Runtime presence scan reports `type(namespace)` is not `table`/`userdata`, so the Interface match is likely a constant (e.g. `C_FOO` string) used with a Lua method like `:format(...)`.

Count: **0**


## Interface-called but missing at runtime

UI code calls it, but runtime scan didn't find it. Common causes: LoadOnDemand not loaded, gated system, or seasonal feature.

Count: **0**


## Interface-called but runtime not checked yet

Interface evidence exists, but there is no per-member runtime presence data in this EvidenceIndex (run `scan runtime_members`). Treat as *unknown* rather than missing.

Count: **904**

- `C_AccountInfo.GetCharacterAtIndex`
- `C_AccountInfo.GetGMLevel`
- `C_AccountInfo.GetNumCharacters`
- `C_AccountInfo.IsGM`
- `C_AddonPanel.DeleteSaveState`
- `C_AddonPanel.EnableHiddenAddons`
- `C_AddonPanel.EnumerateAddOns`
- `C_AddonPanel.GetAddonDisabledBy`
- `C_AddonPanel.GetAddonIndex`
- `C_AddonPanel.GetAddonIndexRaw`
- `C_AddonPanel.GetAddonObject`
- `C_AddonPanel.GetNumInsecureAddons`
- `C_AddonPanel.GetSaveState`
- `C_AddonPanel.GetSaveStateIDs`
- `C_AddonPanel.GetSearchedAddons`
- `C_AddonPanel.HasConfigurableAddons`
- `C_AddonPanel.InitializeAddonList`
- `C_AddonPanel.IsAddonSearched`
- `C_AddonPanel.IsSecureAddon`
- `C_AddonPanel.MakeSaveState`
- `C_AddonPanel.RefreshAddonData`
- `C_AddonPanel.RestoreSaveState`
- `C_AddonPanel.UpdateAddonList`
- `C_AddonPanel.WriteSaveState`
- `C_Appearance.ApplyPendingAppearances`
- `C_Appearance.CanApplyPendingAppearances`
- `C_Appearance.CanSeeAppearances`
- `C_Appearance.CanSetAppearance`
- `C_Appearance.ClearInvalidPendingAppearances`
- `C_Appearance.ClearPendingAppearance`
- `C_Appearance.ClearPendingAppearances`
- `C_Appearance.GetActiveDiscount`
- `C_Appearance.GetAlternativeIDs`
- `C_Appearance.GetAppearanceDetails`
- `C_Appearance.GetAppearanceDisplayInfo`
- `C_Appearance.GetAppearanceForCategory`
- `C_Appearance.GetAppearanceItemSet`
- `C_Appearance.GetAppearanceWebURL`
- `C_Appearance.GetCreatureDisplayItems`
- `C_Appearance.GetEtherealBazaarWebURL`
- ... (864 more)

## Trace-called but runtime not checked yet

apitrace observed calls, but this EvidenceIndex lacks per-member runtime presence. This usually means the presence scan was run in a different session/context (or not run).

Count: **17**

- `C_BuildCreator.GetNumBuilds`
- `C_BuildCreator.QueryAllBuilds`
- `C_BuildCreator.UpdateFilter`
- `C_BuildEditor.CanAddArmorType`
- `C_BuildEditor.CanAddWeaponType`
- `C_MysticEnchant.CanEquipSlot`
- `C_MysticEnchant.GetAppliedEnchant`
- `C_MysticEnchant.GetEnchantInfoByItem`
- `C_MysticEnchant.GetEnchantInfoBySpell`
- `C_MysticEnchant.GetMysticScrollCost`
- `C_MysticEnchant.GetMysticScrolls`
- `C_MysticEnchant.GetProgress`
- `C_MysticEnchant.HasAnyCollected`
- `C_MysticEnchant.HasNearbyMysticAltar`
- `C_MysticEnchant.QueryEnchants`
- `C_MysticEnchantPreset.GetNumPresets`
- `C_MysticEnchantPreset.GetPresetData`

## Interface-called but runtime kind is not function

Interface evidence suggests callable, but runtime scan reports non-function. Usually indicates stale evidence or table-metamethod behavior.

Count: **0**


## Interface-called and present (index-only) but not a function

Index-only presence scan found a non-function (table/field) where Interface evidence suggests callable. This is usually a false-positive call-site parse or a metamethod/wrapper edge case.

Count: **0**


## Runtime function never called (no evidence)

Function exists at runtime but was neither called in Interface call-sites nor observed via apitrace. Likely niche, gated, or new.

Count: **0**


## Ambiguous call-style (no Interface and no trace)

Runtime sees a function, but there is no evidence for `.` vs `:` yet. Avoid calling without additional proof (apitrace or interface update).

Count: **0**


