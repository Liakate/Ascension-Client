# API Documentation v2 - runtime objects

- generated_at: `2026-02-13T21:39:35Z`
- scan_tool_version: `0.3.58`
- client_build: `12340`

| API | kind | op | argc | argcSrc | retc | conf | runtime | iface | trace | probe | examples | hint_keys |
|---|---:|:--:|---:|:--:|---:|:--:|:--:|:--:|---:|:--:|---|---|
| `C_AccountInfo` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AccountInfo.GetCharacterAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AccountInfo.GetGMLevel` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AccountInfo.GetNumCharacters` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AccountInfo.IsGM` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AccountInfo.IsGuide` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_AccountInfo.IsNewcomer` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_AddonPanel` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AddonPanel.DeleteSaveState` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.EnableHiddenAddons` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.EnumerateAddOns` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonDisabledBy` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonIndex` | unknown | : | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonIndexRaw` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonObject` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetNumInsecureAddons` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetSaveState` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetSaveStateIDs` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.GetSearchedAddons` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.HasConfigurableAddons` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.InitializeAddonList` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.IsAddonSearched` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.IsSecureAddon` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.MakeSaveState` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.RefreshAddonData` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.RestoreSaveState` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.UpdateAddonList` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AddonPanel.WriteSaveState` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Appearance.ApplyPendingAppearances` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance.CanApplyPendingAppearances` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Appearance.CanSeeAppearances` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Appearance.CanSetAppearance` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Appearance.ClearInvalidPendingAppearances` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance.ClearPendingAppearance` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance.ClearPendingAppearances` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetActiveDiscount` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetAlternativeIDs` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceDetails` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceDisplayInfo` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceForCategory` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceItemSet` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceWebURL` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetCreatureDisplayItems` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetEtherealBazaarWebURL` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetItemAppearanceID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.GetPendingAppearance` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.HasPendingAppearances` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Appearance.IsEtherealBazaarAppearance` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance.IsTransmogable` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance.SetCanSeeAppearances` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Appearance.SetPendingAppearance` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AppearanceCollection.ApplyCategoryFilter` | unknown | . | 4 |  |  |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetAppearanceTypes` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetAvailableChapters` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetAvailableSeasons` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoriesForType` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoryAppearances` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoryInfo` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoryMaxPages` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCollectedCount` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetSeasonalItems` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceCollection.IsAppearanceCollected` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceOutfit` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AppearanceOutfit.GetAppearanceOutfits` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_AppearanceOutfit.GetCurrentOutfitName` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceOutfit.GetOutfitInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_AppearanceOutfit.SetPendingOutfit` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_AssetQueryService` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Aura` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Aura.UnitAura` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Aura.UnitHasAura` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_BugTracker.ClearReport` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker.SetReportCategory` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker.SetReportDescription` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker.SetReportPriority` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker.SetReportPublic` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker.SetReportTitle` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker.SubmitReport` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_BuildCreator.ActivateBuild` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.BookmarkBuild` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.CanActivateBuild` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.DeleteBuild` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.GetActiveBuild` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.GetActiveSpecForBuild` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_BuildCreator.GetBookmarkedBuildAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.GetBuild` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.GetBuildAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.GetNumBookmarkedBuilds` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.GetNumBuilds` | unknown | . |  |  |  |  |  | Y | 180 |  |  |  |
| `C_BuildCreator.GetSpell` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.IsOwnedBuild` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.IsUpvotedBuild` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.QueryAllBuilds` | unknown | . | 1 |  |  |  |  | Y | 18 |  |  |  |
| `C_BuildCreator.QueryBuild` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.RateBuild` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildCreator.UpdateFilter` | unknown | . | 3 |  |  |  |  | Y | 198 |  |  |  |
| `C_BuildDraft` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_BuildDraft.GetDraftableBuild` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildDraft.GetDraftedBuild` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildDraft.GetNumDraftableBuilds` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildDraft.IsAwaitingRolePrompt` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildDraft.IsCompletedBuild` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildDraft.IsDraftableBuild` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_BuildDraft.IsDraftedBuild` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_BuildDraft.SelectRole` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_BuildEditor.AddArmorType` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.AddRandomEnchant` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.AddSpell` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.AddWeaponType` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanAddArmorType` | unknown | . | 1 |  |  |  |  | Y | 2 |  |  |  |
| `C_BuildEditor.CanAddSpell` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanAddWeaponType` | unknown | . | 1 |  |  |  |  | Y | 9 |  |  |  |
| `C_BuildEditor.CanPublishBuild` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanRemoveSpell` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetEnchantFlags` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetIsCoreAbility` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetIsEmpoweringAbility` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetIsOptimalAbility` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetIsSynergisticAbility` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetSpellFlags` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetSpellLevel` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.DiscardPendingBuild` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.DoesBuildHaveEnchant` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.DoesBuildHaveSpellID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.EditBuild` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.GetEssenceForLevel` | unknown | . | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.GetFilteredEntryAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.GetNumFilteredEntries` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_BuildEditor.GetPendingBuild` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.GetQualityInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_BuildEditor.GetQualityInfoForLevel` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.GetSpellByID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.PublishBuild` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveArmorType` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveRandomEnchant` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveSpell` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveWeaponType` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetCategory` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetDescription` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetDifficultyRating` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetEnchantFlags` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetEnchantStacks` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetFilteredEntries` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetIcon` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsCoreAbility` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsEmpoweringAbility` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsOptimalAbility` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsSynergisticAbility` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetName` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetPrimaryStat` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetRoles` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetSpellFlags` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BuildEditor.SetSpellLevel` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Exists` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.Get` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CVar.GetBitfield` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CVar.GetBool` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CVar.GetByteString` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetCVarBitfield` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CVar.GetDefault` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetDefaultBitfield` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetDefaultBool` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetDefaultNumber` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetFlag` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetMax` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetMin` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.GetNumber` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CVar.RegisterSavedCVar` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.RegisterSavedCharacterCVar` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.ResetToDefault` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.Set` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CVar.SetBitfield` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.SetCVarSave` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CVar.SetFlag` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Cache` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Cache.QueryAllStats` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Cache.QueryStat` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CallboardCache` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CallboardCache.GetCallboardCacheInfo` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CallboardCache.GetCurrentPoints` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CallboardCache.GetItemLevelInfo` | unknown | . |  |  | 3 |  |  | Y | 0 |  |  |  |
| `C_CallboardCache.GetPointsForQuest` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Challenge` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Challenge.CanActivateChallenge` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.CanDeactivateChallenge` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.CanResurrect` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetActiveChallenges` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetAllChallenges` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetAllTrials` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetBrokenChallengeRules` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeAtIndex` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeCompletion` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeCompletions` | unknown | . | 3 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeCriteriaInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeCriterias` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeFailure` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeIDByIndex` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeInfoByLevel` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeLevels` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetChallengesWithGroupID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetCompletedChallenges` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetConditionLocalization` | unknown | . | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetModifierLocalization` | unknown | . | 1 |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetNumChallenges` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Challenge.GetRequirementLocalization` | unknown | . | 1 |  | 7 |  |  | Y | 0 |  |  |  |
| `C_Challenge.GetRuleLocalization` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Challenge.HasBrokenChallengeRule` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.HasChallengeRule` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.IsChallengeActive` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Challenge.QueryChallengeCompletions` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.SetChallengeFilter` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.StartChallenge` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Challenge.StopChallenge` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.AddByEntryID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.AddSuggestionContextOverride` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ApplyPendingBuild` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanAddByEntryID` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanApplyPendingBuild` | unknown | . |  |  | 7 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanClearPendingBuild` | unknown | . | 1 |  | 5 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanLearnID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanRemoveByEntryID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanSwapEntriesByID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanSwitchActiveChrSpec` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUnlearnAllSpells` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUnlearnAllTalents` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUnlearnID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUseBrowser` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CancelPendingBuild` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearPendingBuild` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearPendingBuildByTab` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearRecentlyLearnedEntries` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearSuggestionContextOverrides` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ExportBuild` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetAbilityEssenceCost` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetActiveChrSpec` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetActiveSpecID` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetAllEntries` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetCategories` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetCategoryDisplayInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassAEInvestment` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassInfo` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassPointInvestment` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassTEInvestment` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntriesAvailableForSwap` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntriesAvailableForTrade` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntriesByClass` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntryByInternalID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntryBySpellID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetExpectedAE` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetExpectedTE` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetFilteredEntryAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetFilteredEntryAtIndexByCategory` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetGlobalAEInvestment` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetGlobalTEInvestment` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetImplicitByClass` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetInspectInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetInspectedBuild` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetInternalID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownSpellEntries` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownSpellEntriesForClass` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownSpells` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownTalentEntries` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownTalentEntriesForClass` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetLearnedAE` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetLearnedTE` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetLowestInvestmentRequired` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetMasteriesByClass` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetNumFilteredEntries` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CharacterAdvancement.GetNumFilteredEntriesByCategory` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingClassAEInvestment` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingClassPointInvestment` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingClassTEInvestment` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingExpectedAE` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingExpectedTE` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingGlobalAEInvestment` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingGlobalTEInvestment` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingRankByEntryID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingRemainingAE` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingRemainingTE` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingSummary` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CharacterAdvancement.GetPendingTabAEInvestment` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingTabTEInvestment` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetQualityCount` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetQualityInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetQualityLimit` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetRemainingAE` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetRemainingTE` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetRootSpellTagTypes` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSpellTagTypeDisplayInfo` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSpellTagTypes` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSpellsByClass` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSuggestedStats` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTabAEInvestment` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetTabTEInvestment` | unknown | . | 3 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentEssenceCost` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentRankByID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentRankBySpellID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentsByClass` | unknown | . | 3 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.HasAnySuggestionContextOverrides` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ImportPendingBuildID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.InspectUnit` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsAbilityID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsAbilitySpellID` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_CharacterAdvancement.IsActiveBuildAvailable` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CharacterAdvancement.IsConnectionAllowed` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsFiltered` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsKnownID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsKnownSpellID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsLockedID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsMastery` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsPending` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsPendingBuildAvailable` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsPendingEntryID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsSuggestionContextOverride` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentAbilityID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentAbilitySpellID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentSpellID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTraitID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.KnowsConnectedNodesFor` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.LearnID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.LockID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.MeetsInvestmentForAddByEntryID` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.PickupSpell` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.RemoveByEntryID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.RemoveSuggestionContextOverride` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SetFilteredEntries` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SetFilteredEntriesByCategory` | unknown | . | 4 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmLearnID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmUnlearnAllSpells` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmUnlearnAllTalents` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmUnlearnID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SwapEntriesByID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SwitchActiveChrSpec` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnitKnownID` | unknown | . | 3 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnitTalentRankByID` | unknown | . | 3 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlearnAllSpells` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlearnAllTalents` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlearnID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlockID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CharacterCreate.CanCreateClass` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeCategories` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeCategoryInfo` | unknown | . | 1 |  | 3 |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeInfo` | unknown | . | 1 |  | 12 |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeRoleInfo` | unknown | . | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeRoles` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeSpellDescription` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypes` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Chat` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Chat.GetChatInfraction` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Chat.HasChatInfraction` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_ClassInfo` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ClassInfo.GetAllSpecs` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_ClassInfo.GetClassBySpecName` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_ClassInfo.GetSpecInfo` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_ClassInfo.GetSpecInfoByID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CollectorCache` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CollectorCache.GetCollectorCacheItemInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheItems` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheRarityRatesInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheRarityTypeInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheTypeInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_CollectorCache.GetNumCollectorCacheItems` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Comm` | frame |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.Enqueue` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Comm.IsEmpty` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Comm.OnAttributeChanged` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Comm.OnUpdate` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Comm.SendJsonMessage` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Comm.SetAttribute` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Comm.Setup` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Comm.UpdateAvailable` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Config` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Config.GetBoolConfig` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Config.GetFloatConfig` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Config.GetFloatVectorConfig` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Config.GetIntConfig` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Config.GetIntVectorConfig` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Config.GetRateConfig` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_ContentLoader` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ContentLoader.AddToParseQueue` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_ContentLoader.Load` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_ContentLoader.ResumeRoutines` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CrowdControl` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CrowdControl.COMBAT_LOG_EVENT_UNFILTERED` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CrowdControl.CROWD_CONTROL_ADDED` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CrowdControl.CROWD_CONTROL_REMOVED` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CrowdControl.GetActiveCrowdControl` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CrowdControl.GetCrowdControlInfo` | unknown | : | 1 |  | 8 |  |  | Y | 0 |  |  |  |
| `C_CrowdControl.PLAYER_ENTERING_WORLD` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CrowdControl.UNIT_AURA` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CustomStore` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CustomStore.ApplyCustomStoreFilter` | unknown | . | 4 |  |  |  |  | Y | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreData` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreItemInfo` | unknown | . | 1 |  | 6 |  |  | Y | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreMaxPages` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreTypeInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_CustomStore.IsItemLockedDueToAchievement` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CustomStore.IsItemLockedDueToGameEvent` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CustomStore.QueryCustomStore` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Deflate.Adler32` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Deflate.CompressDeflate` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Deflate.CompressDeflateWithDict` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.CompressZlib` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.CompressZlibWithDict` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.CreateCodec` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.CreateDictionary` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.DecodeForPrint` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Deflate.DecodeForWoWAddonChannel` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.DecodeForWoWChatChannel` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.DecompressDeflate` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Deflate.DecompressDeflateWithDict` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.DecompressZlib` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.DecompressZlibWithDict` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.EncodeForPrint` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.EncodeForWoWAddonChannel` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Deflate.EncodeForWoWChatChannel` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_DraftRewards` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_DraftRewards.GetNumClaimableHandOfFateRewards` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_EquipmentSet` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ExtraActionButton` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ExtraActionButton.GetExtraActionButtonAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_ExtraActionButton.GetExtraActionButtonInfo` | unknown | . | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_ExtraActionButton.GetNumExtraActionButtons` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Flipbook` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Flipbook.CreateAtlasFlipbook` | unknown | : | 7 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Format` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Format.Format` | unknown | . | 4 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_GM` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GMTicket` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GameMode` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GameMode.ASCENSION_CUSTOM_GAME_MODE_CHANGED` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_GameMode.GenerateCallbackEvents` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_GameMode.GetActiveGameModes` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_GameMode.GetCallbackTable` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GameMode.GetCallbackTables` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GameMode.GetCallbacksByEvent` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_GameMode.HasRegistrantsForEvent` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GameMode.IsAnyGameModeActive` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_GameMode.IsGameModeActive` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_GameMode.PLAYER_ENTERING_WORLD` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_GameMode.RegisterCallback` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_GameMode.RegisterCallbackWithHandle` | unknown | : | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Gossip` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip.CheckHookItemHide` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.CheckHookItemShow` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.CheckHookNPCHide` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.CheckHookNPCShow` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.CheckItemHide` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.CheckItemShow` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.CheckNPCHide` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.CheckNPCShow` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.GOSSIP_CLOSED` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.GOSSIP_SHOW` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.HookItem` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.HookItems` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.HookNPC` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.HookNPCs` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.MakeGroup` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Gossip.RedirectItem` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RedirectItems` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RedirectNPC` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RedirectNPCs` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RemoveHookItem` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RemoveHookNPC` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectItem` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectItems` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectNPC` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectNPCs` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.RestoreGossip` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Gossip.SilentHideGossip` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_GroupFinder` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GroupFinder.GetActivityInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GroupFinder.GetAvailableActivities` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GroupFinder.GetAvailableCategories` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GroupFinder.GetAvailableGroupTypes` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GroupFinder.GetCategoryInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GroupFinder.GetGroupInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GroupFinder.GetGroupTypeInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_GroupFinder.GetListedGroups` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_HighRisk` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_HighRisk.CanToggleFelCommutation` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_HighRisk.GetInsuranceCostPerSlot` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_HighRisk.GetInsuranceTotalCost` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_HighRisk.IsFelCommutationActive` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_HighRisk.ToggleFelCommutation` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.DumpProfiling` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.IsRegistered` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.Register` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.RegisterAllEvents` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.RegisterBucket` | unknown | : | 4 |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.SendBlizzardEvent` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.SendEvent` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.StartProfiling` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.StopProfiling` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Hook.Unregister` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Instance.CanUseCheckpoint` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.GetInstanceLocks` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.GetSavedMapAndDifficulty` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.HasCheckpoint` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.IsInArena` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.IsInBattleground` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.IsInDungeon` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.IsInPVE` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.IsInPVP` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Instance.IsInRaid` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_InventoryState` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_InventoryState.ClearAllNewItems` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_InventoryState.ITEM_PUSH` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_InventoryState.IsNewItem` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_InventoryState.ItemUpdate` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_InventoryState.PLAYER_ENTERED_WORLD` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_InventoryState.RemoveNewItem` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_InventoryState.UpdateCurrentItems` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Item` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Item.CanBind` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Item.GetCacheTooltip` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Item.GetColoredItemName` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Item.GetLastUsedItemID` | unknown | : |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Item.GetMerchantItemRatingRequirement` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Item.GetNameAndID` | unknown | : | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Item.GetScalingLevel` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Item.GetSlotItemPower` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Item.ITEM_USED_PAYLOAD` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Item.IsBound` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_ItemSet` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ItemSet.GetAppearances` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_ItemSet.GetItemSetName` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_ItemSet.GetItemSetNumCollected` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Keystones` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Keystones.ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetCurrentSetBest` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetCurrentSetString` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetDungeonBest` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetDungeonBestLink` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetKeystoneDungeonInfo` | unknown | . | 1 |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetKeystoneInInventory` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetKeystoneInInventoryItemID` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetPlayerSaveKey` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetProfileLink` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetSetBest` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.GetTimedDungeonsForExpansion` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Keystones.MYTHIC_PLUS_COMPLETE` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.MYTHIC_PLUS_COUNTDOWN_STARTED` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.MYTHIC_PLUS_STARTED` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Keystones.SaveKeystoneRun` | unknown | . | 5 |  |  |  |  | Y | 0 |  |  |  |
| `C_LFG` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LFG.CanUseGroupFinder` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_LFG.CanUseLFD` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_LFG.CanUseManastorm` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_LFG.CanUseRandomLFD` | unknown | : | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_LFG.GetLFGDungeonRewards` | unknown | : | 1 |  | 7 |  |  | Y | 0 |  |  |  |
| `C_LFG.IsRandomDungeonDisplayable` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_LFG.IsScalingDungeon` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Logger` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Logger.Error` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Logger.Info` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_LootLockout` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LootLockout.GetEncounterData` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_LootLockout.GetEncounterDatasForMapAndDifficulty` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_LootLockout.GetLootLockoutTimeRemaining` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_LootLockout.GetLootLockouts` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_LootLockout.GetUnitEncounterID` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_LootLockout.GetUnitLootLockForEncounter` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_LootLockout.HasEncounterDatasForMapAndDifficulty` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_LootLockout.ListInstanceBinds` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_LoyaltyPass` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Manastorm` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Manastorm.CanEnter` | unknown | . | 1 |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.CanLeave` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.Enter` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetActiveLevel` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetActiveManastormID` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetActiveManastormType` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetAvailableLoadoutSpells` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetBoss` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetEnterableLevels` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetExperienceModifier` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetLoadoutSpellAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetManastormCacheInfo` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetMaxCompletedLevels` | unknown | . | 1 |  | 5 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetNumLoadoutSlots` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetRewardModifier` | unknown | . | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.GetStageBonusExperience` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Manastorm.IsInManastorm` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Manastorm.SetLoadoutSpellAtIndex` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Map` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Map.GetBestMapForUnit` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanCollectionReforgeAnySlot` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.CanCollectionReforgeItem` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.CanCollectionReforgeSlot` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.CanDestroy` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.CanDisenchantItem` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.CanDisenchantSlot` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.CanEquipSlot` | unknown | . | 1 |  | 2 |  |  | Y | 40 |  |  |  |
| `C_MysticEnchant.CanInspect` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.CanPurchaseMysticExtract` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.CanReforgeItem` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.CanReforgeSlot` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.GetAppliedEnchant` | unknown | . | 2 |  | 1 |  |  | Y | 288 |  |  |  |
| `C_MysticEnchant.GetApplyChanges` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.GetCollectionReforgeChanges` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.GetCollectionReforgeItemCost` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.GetCollectionReforgeSlotCost` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.GetDisenchantCost` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.GetEnchantInfoByItem` | unknown | . | 1 |  | 1 |  |  | Y | 945 |  |  |  |
| `C_MysticEnchant.GetEnchantInfoBySpell` | unknown | . | 1 |  | 1 |  |  | Y | 4057 |  |  |  |
| `C_MysticEnchant.GetMysticScrollCost` | unknown | . |  |  | 1 |  |  | Y | 1 |  |  |  |
| `C_MysticEnchant.GetMysticScrolls` | unknown | . |  |  | 1 |  |  | Y | 9 |  |  |  |
| `C_MysticEnchant.GetProgress` | unknown | . |  |  | 2 |  |  | Y | 3 |  |  |  |
| `C_MysticEnchant.GetReforgeCost` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.HasAnyCollected` | unknown | . |  |  | 1 |  |  | Y | 3 |  |  |  |
| `C_MysticEnchant.HasAnyScroll` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.HasAnySlotEnchanted` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_MysticEnchant.HasNearbyMysticAltar` | unknown | . |  |  |  |  |  | Y | 51 |  |  |  |
| `C_MysticEnchant.Inspect` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.PurchaseMysticExtract` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.QueryEnchants` | unknown | . | 4 |  | 2 |  |  | Y | 115 |  |  |  |
| `C_MysticEnchant.UndoApply` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_MysticEnchant.UndoCollectionReforge` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_MysticEnchantPreset` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_MysticEnchantPreset.GetNumPresets` | unknown | . |  |  | 1 |  |  | Y | 17 |  |  |  |
| `C_MysticEnchantPreset.GetPresetData` | unknown | . | 1 |  |  |  |  | Y | 18 |  |  |  |
| `C_MythicPlus` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_MythicPlus.ActivateKeystone` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneChampions` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneEncounters` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneInfo` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneTime` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneTrash` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetCurrentAffixes` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetKeystoneInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetMapEncounters` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.GetMapFinalEncounter` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.IsItemKeystone` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_MythicPlus.IsKeystoneActive` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_NamePlate` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_NamePlate.GetNamePlateForUnit` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_NamePlate.SetNamePlateSize` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_NamePlateManager.ApplyFPSIncrease` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.CheckNamePlateMotion` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.DisableBlizzPlate` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.EnumerateActiveNamePlates` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.GetNamePlateSize` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.IsNamePlateMoving` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.RefreshNamePlateSize` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.SetEnableResizeNamePlates` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_NamePlateManager.SetNamePlateSize` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_NoviceNetwork` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_NoviceNetwork.IsNewcomer` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PVP` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PVP.CanQueueCasual` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.CanQueueInHighRisk` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.CanQueueRated` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.GetBattlegroundFaction` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.GetCurrentBestRating` | unknown | : |  |  | 3 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetEliteTierInfo` | unknown | : |  |  | 4 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetHolidayBGInfo` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetHonorRank` | unknown | : | 1 |  | 5 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetIsCurrentMapHighRisk` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetMapIsHighRisk` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetMaxGearDropAmount` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.GetPVPTierInfo` | unknown | : | 1 |  | 6 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetRandomBGInfo` | unknown | : |  |  | 10 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetRandomBrawlBGInfo` | unknown | : |  |  | 10 |  |  | Y | 0 |  |  |  |
| `C_PVP.GetRequiredItemLevelForEvents` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.IsLegacyWarmode` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.PLAYER_ENTERING_WORLD` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PVP.ZONE_CHANGED_NEW_AREA` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Player.GetAverageItemLevel` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetClass` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetCurrentCompanion` | unknown | : |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Player.GetCurrentMapContinentZone` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.GetCurrentMapExpansion` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.GetCurrentMapInfo` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetFaction` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetLevel` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetName` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.GetPvEPower` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetPvPPower` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetRace` | unknown | : |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Player.GetRuleset` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetRulesetCooldown` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.GetSex` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.HasAura` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.HasBuff` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.HasDebuff` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.HasRuleset` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.InCombat` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsCustomClass` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsDead` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsDefaultClass` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.IsEffectivelyTank` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsGM` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.IsGroupLeader` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsHero` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.IsHighRisk` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsImmune` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsInGroup` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsInRaid` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsMaxLevel` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.IsNoRiskPvE` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsNoRiskPvP` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsNoRiskPvPOrHigher` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsPrestiged` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Player.IsTitansGrip` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.IsWorldPVP` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.PLAYER_ENTERING_WORLD` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.PLAYER_LEVEL_UP` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.SetRuleset` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.UNIT_PET` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Player.UpdatePvEPower` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PlayerPoll.CanChangeQuestionChoice` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll.CanSubmitAnswer` | unknown | . | 3 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll.GetNumQuestionChoices` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll.GetNumQuestions` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll.GetQuestionChoiceInfo` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll.GetQuestionInfo` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll.HasUnansweredQuestions` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerPoll.SubmitAnswer` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PlayerTicket.CanCloseTicket` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.CanCreateTicket` | unknown | . | 5 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.CanReopenTicket` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.CanSendTicketMessage` | unknown | . | 3 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.CreateTicket` | unknown | . | 5 |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.GetCurrentTicket` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.GetTicketMessages` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.IsResponseSeen` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.MarkResponseSeen` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.ReopenTicket` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_PlayerTicket.SendTicketMessage` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_PopupQueue` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PopupQueue.Add` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_PopupQueue.AddAchievement` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PrimaryStat.GetActivePrimaryStat` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat.GetInternalID` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatAura` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatID` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatInfo` | unknown | : | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatSpell` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat.GetUnitPrimaryStat` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_PrimaryStat.SetPrimaryStat` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.ASCENSION_CUSTOM_QUEST_REWARDED` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.AddAutoQuestPopUp` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.ExpandAllQuestHeaders` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.GetCurrentQuests` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.GetPortraitData` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.GetQuestID` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.GetQuestIndexByID` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.GetQuestNameByID` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Quest.GetTitleByID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.HasOrHasDoneQuest` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.IsFelforgedChallenge` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.IsOnQuestID` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.IsQuerying` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.IsQuestCachedByID` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.IsQuestComplete` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.IsQuestTurnedIn` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.PLAYER_LOGIN` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.QUEST_ACCEPTED` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.QUEST_LOG_UPDATE` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.QUEST_QUERY_COMPLETE` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Quest.SendPathToAscensionEvent` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_QuestLog` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_QuestLog.GetUnitQuestInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Realm` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Realm.IsDevelopment` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Realm.IsLeague` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Realm.IsLive` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Realm.IsPTR` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Realm.IsProduction` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Realm.IsSeasonal` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_RealmMerge.GetAvailableOptions` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_RealmMerge.GetTargetRealm` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_RealmMerge.IsMergeAvailable` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_RealmMerge.NeedsSetTargetRealm` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_RealmMerge.SetTargetRealm` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_RealmSelect` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_RealmSelect.GetRealmInfo` | unknown | . | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_RecoveryService` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_RecoveryService.GetCategoryItemAtIndex` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_RecoveryService.GetNumItemsInCategory` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_RecoveryService.QueryCategory` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_RecoveryService.UpdateFilter` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Scenario` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Scenario.GetActiveStage` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Scenario.GetEncounterAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Scenario.GetNumEncounters` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Scenario.GetScenarioInfo` | unknown | . |  |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Scenario.GetScenarioName` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Scenario.IsInScenario` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Serialize.CompressForURI` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.DecompressFromURI` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.Deserialize` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.DeserializeCompressForPrint` | unknown | : | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Serialize.DeserializeDecompressFromPrint` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Serialize.DeserializeValue` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.FromJSON` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Serialize.FromJSONCategory` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.FromJSONData` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.IsSerializableType` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.Serialize` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.SerializeCompressForPrint` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Serialize.SerializeEx` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Serialize.ToJSON` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SkillCard` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SkillCard.GetCardAtIndex` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCard.GetCardCount` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_SkillCard.GetCardID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_SkillCard.GetCardRankAtIndex` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_SkillCard.GetCardSpellID` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SkillCard.GetMaxCardCount` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SkillCard.GetSkillCardInfo` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCard.GetSkillCardInfoAtIndex` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCard.GetSkillCardQuality` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SkillCard.IsCardAtIndexActive` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCard.IsCardAtIndexBlocked` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCard.IsCardedID` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_SkillCard.RemoveCardAtIndex` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCard.SetCardAtIndex` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SkillCardCollection.CanPurchaseSealedCard` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.CanPurchaseSealedCardBoosterPack` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.ClaimPendingSkillCard` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetBonusSealedCardPacksProgress` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetMaxNumPurchasableSealedCardBoosterPacks` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetNumPendingSkillCards` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetNumSkillCards` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetPendingSkillCardAtIndex` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetProgress` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetSealedCardBoosterPackCost` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetSealedCardCost` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetSkillCardAtIndex` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.HasAnySkillCardsCollected` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.IsCollected` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.PurchaseSealedCard` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.PurchaseSealedCardBoosterPack` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SkillCardCollection.SetSkillCardFilter` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_Social` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Social.FRIEND_METADATA_CHANGED` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Social.GetFriendAddedAs` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Social.SetFriendAddedAs` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.GetFirstRank` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.GetFreeActionButton` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.GetFreeActionID` | unknown | : |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.GetMaxLearnableRank` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.GetNameAndID` | unknown | : | 3 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Spell.GetPresetSpell` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.GetSpecSpell` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.GetSpellActionID` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.GetSpellDescription` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.GetSpellID` | unknown | : | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.HasMultipleSpellRanks` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.HasNotMaxedRanks` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.HasRuneUI` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsActionAlmostReady` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsActivePreset` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsActiveSpec` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsAnyRankKnown` | unknown | : | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.IsCastAlmostDone` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsHelpfulSpell` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsImmunitySpell` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_Spell.IsPresetSpell` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsSpecSpell` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.IsTrainerSpell` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Spell.PLAYER_ENTERING_WORLD` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.PLAYER_LEVEL_UP` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.PlaceSpellOnActionBar` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.RemoveSpellFromActionBar` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.SET_ACTION_BUTTON_SPELL_PAYLOAD` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.SPELLS_CHANGED` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.ShouldHoldToCast` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Spell.TabHasNotMaxedRanks` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SpellActivationOverlay` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SpellActivationOverlay.GetSpellActivationOverlayInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SpellActivationOverlay.IsSpellOverlayed` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Sun` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SuperTrack` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SuperTrack.ClearSuperTracker` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_SuperTrack.GetSuperTrackedPosition` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_SuperTrack.GetTargetState` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_SuperTrack.IsSuperTrackingAnything` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_SuperTrack.PositionFrame` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SuperTrack.SetSuperTrackedCorpse` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_SuperTrack.SetSuperTrackedPosition` | unknown | . | 4 |  |  |  |  | Y | 0 |  |  |  |
| `C_SuperTrack.SetSuperTrackedQuestID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Taxi` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Taxi.GetCurrentTaxiNodeID` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Taxi.GetTaxiNodeID` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_Taxi.GetTaxiPathDuration` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_TemporalContracts` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TemporalContracts.ActivateAllTemporalContractsByContentType` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.ActivateTemporalContract` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetCategoryData` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetCategoryName` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetCompletableQuestsByCategory` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_TemporalContracts.GetCompletableTemporalContracts` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetQuestCategory` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetQuestSortIDs` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetQuestSortText` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTemporalContractInfo` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_TemporalContracts.GetTemporalContractTypes` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContentTypeCost` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContentTypeRewards` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContractTypeCost` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContractTypeRewards` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Timer` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Timer.After` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Timer.NewTicker` | unknown | . | 3 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Token` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Token.GetTokenAmount` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Token.GetTokenInfo` | unknown | . | 1 |  | 4 |  |  | Y | 0 |  |  |  |
| `C_Token.GetTokenTypes` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_TrackerHeader` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_COMPLETED` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_CRITERIA_COMPLETED` | unknown | : | 6 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_CRITERIA_FAILED` | unknown | : | 6 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_DEATH_UPDATE` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_FAILURE_ADDED` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrackerHeader.Hide` | unknown | : |  |  |  |  |  | Y | 0 |  |  |  |
| `C_TrackerHeader.Show` | unknown | : | 7 |  |  |  |  | Y | 0 |  |  |  |
| `C_TradeSkill` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TradeSkill.GetCraftedItem` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_TradeSkill.GetReagentItems` | unknown |  |  |  |  |  |  |  | 0 |  |  |  |
| `C_TrialCreator` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrialCreator.ActivateTrial` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.CanActivateTrial` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.CanDeactivateTrial` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.CanEditTrial` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.CanSaveTrial` | unknown | . | 7 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.DeactivateTrial` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.DeleteTrial` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.GetActiveTrial` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.GetAllTrials` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_TrialCreator.GetNumTrials` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_TrialCreator.GetOwnedTrials` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_TrialCreator.GetTrialAtIndex` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialCompletion` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialCompletions` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialIDByIndex` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.QueryTrialCompletions` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.QueryTrials` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.RateTrial` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.SaveTrial` | unknown | . | 7 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrialCreator.SetTrialFilter` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrinityCore` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrinityCore.ASCENSION_LUA` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrinityCore.ConvertBagSlots` | unknown | : | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrinityCore.MSG_VERSION` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrinityCore.MSG_VERSION_REPLY` | unknown | : | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_TrinityCore.RequestPlayerVersion` | unknown | : | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Tutorial.AddMentorSpecialization` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.CanCollectReward` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.CanToggleMentorStatus` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.CollectReward` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetAvailableMentorAtIndex` | unknown | . | 1 |  | 6 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetCategories` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetCategoryInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetCategoryProgress` | unknown | . | 1 |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetIndexByKeywordID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetKeywordAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetKeywordID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetKeywordInfo` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetMentorSpecializationActive` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetMentorSpecializationInfo` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetMentorSpecializations` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetNumAvailableMentors` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Tutorial.GetNumKeywords` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_Tutorial.GetNumTutorials` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetObjectiveInfo` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetObjectives` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetRewards` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialAtIndex` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialByID` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialDisplay` | unknown | . | 1 |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialsRequiredForMentorStatus` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.IsCategoryEnabled` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.IsMentorStatusActive` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.IsRewardCollected` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.IsTutorialAvailable` | unknown | . | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.IsTutorialComplete` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.IsTutorialRequiredForMentorStatus` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Tutorial.QueryActiveMentors` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.RemoveMentorSpecialization` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.SetAvailableMentorFilter` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.SetKeywordFilter` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.SetTutorialFilter` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.StartQuest` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Tutorial.ToggleMentorStatus` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_UICamera` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_UICamera.GetCameraInfo` | unknown | . | 1 |  | 5 |  |  | Y | 0 |  |  |  |
| `C_UICamera.GetItemCameraID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_VanityCollection` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_VanityCollection.GetAllItems` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_VanityCollection.GetDPPrice` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_VanityCollection.GetItem` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_VanityCollection.GetNum` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_VanityCollection.GetVPPrice` | unknown |  |  |  |  |  |  |  | 0 | Y |  |  |
| `C_VanityCollection.IsCollectionItemOwned` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_VanityCollection.IsPurchaseInProgress` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_VanityCollection.PurchaseCollectionItem` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_VanityCollection.PurchaseWebShopItem` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Wildcard.AddAllDesiredFilter` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.AddDesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.AddUndesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanAddDesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanAddUndesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanRepurchaseAnyRolls` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanRepurchaseRolls` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanRepurchaseTalentRolls` | unknown | . | 2 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanResetAbilities` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanRollAbilities` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanStartRapidRolling` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.CanUseRapidRolling` | unknown | . |  |  | 2 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.ClearDesiredSpells` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.ClearUndesiredSpells` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetFilteredDesiredEntryAtIndex` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetFilteredUndesiredEntryAtIndex` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetMaximumRapidRolls` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetNextUnlearnedID` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetNumFilteredDesiredEntries` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetNumFilteredUndesiredEntries` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetNumRepurchasableRolls` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetNumRepurchasableTalentRolls` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetRapidRollAbilityBreakpointInfo` | unknown | . |  |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetRapidRollTalentBreakpointInfo` | unknown | . |  |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetRepurchaseRollCost` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetRepurchaseTalentRollCost` | unknown | . | 2 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.GetRollIcons` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Wildcard.IsDesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.IsUndesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.RemoveDesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.RemoveUndesiredID` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.RepurchaseRolls` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.RepurchaseTalentRolls` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.ResetAbilities` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.RollAbilities` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.SetFilteredDesiredEntries` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.SetFilteredUndesiredEntries` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.StartRapidRolling` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.UnlearnAbility` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_Wildcard.WillRollStartingAbilities` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_WildcardRewards.CanClaimScrollOfFortuneRewards` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards.ClaimScrollOfFortuneRewards` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards.GetLevelingInfo` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards.GetMarkOfAscensionCost` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards.GetNumClaimableScrollOfFortuneRewards` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards.GetNumClaimedScrollOfFortuneRewards` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards.GetRewards` | unknown | . | 3 |  |  |  |  | Y | 0 |  |  |  |
| `C_WildcardRewards.GetScrollOfFortuneRewardsReleaseInfo` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_WorldMap.CanShowPOI` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetCurrentMapID` | unknown | . |  |  | 1 |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetMapFileByAreaID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetMapIDByAreaID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetMapIDByZoneID` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetMapPosition` | unknown | . | 4 |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetPOIFilter` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetVisiblePOI` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.GetWorldPosition` | unknown | . | 3 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_WorldMap.IsOnCityMap` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.IsOnContinentMap` | unknown | . |  |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.SetPOIFilter` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_WorldMap.SetPOIFilters` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
