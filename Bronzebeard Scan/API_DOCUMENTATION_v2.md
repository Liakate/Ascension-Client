# API Documentation v2 (evidence-backed)

- generated_at: `2026-02-15T08:13:21Z`
- bbscan_version: `0.3.92`
- client_build: `12340`

| API | kind | op | argc | argcSrc | retc | conf | runtime | iface | trace | probe | examples | hint_keys |
|---|---:|:--:|---:|:--:|---:|:--:|:--:|:--:|---:|:--:|---|---|
| `C_AccountInfo.GetCharacterAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AccountInfo.GetGMLevel` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AccountInfo.GetNumCharacters` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AccountInfo.IsGM` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AccountInfo.IsGuide` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_AccountInfo.IsNewcomer` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_AddonPanel.DeleteSaveState` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.EnableHiddenAddons` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.EnumerateAddOns` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonDisabledBy` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonIndex` | function | : | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonIndexRaw` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetAddonObject` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetNumInsecureAddons` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetSaveState` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetSaveStateIDs` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.GetSearchedAddons` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.HasConfigurableAddons` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.InitializeAddonList` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.IsAddonSearched` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.IsSecureAddon` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.MakeSaveState` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.RefreshAddonData` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.RestoreSaveState` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.UpdateAddonList` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AddonPanel.WriteSaveState` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.ApplyPendingAppearances` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.CanApplyPendingAppearances` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.CanSeeAppearances` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.CanSetAppearance` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.ClearInvalidPendingAppearances` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.ClearPendingAppearance` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.ClearPendingAppearances` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetActiveDiscount` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetAlternativeIDs` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceDetails` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceDisplayInfo` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceForCategory` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceItemSet` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetAppearanceWebURL` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetCreatureDisplayItems` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetEtherealBazaarWebURL` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetItemAppearanceID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.GetItemSetAppearanceID` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Appearance.GetPendingAppearance` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.HasPendingAppearances` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.IsEtherealBazaarAppearance` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.IsTransmogable` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.SetCanSeeAppearances` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Appearance.SetPendingAppearance` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.ApplyCategoryFilter` | function | . | 4 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.CollectItemAppearance` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_AppearanceCollection.GetAppearanceTypes` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetAvailableChapters` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetAvailableSeasons` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoriesForType` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoryAppearances` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoryInfo` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCategoryMaxPages` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetCollectedCount` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.GetSeasonalItems` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceCollection.IsAppearanceCollected` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceOutfit.DeleteOutfit` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_AppearanceOutfit.GetAppearanceOutfits` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_AppearanceOutfit.GetCurrentOutfitName` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceOutfit.GetOutfitInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_AppearanceOutfit.SaveOutfit` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_AppearanceOutfit.SetPendingOutfit` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_AssetQueryService.TryCacheCreature` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_AssetQueryService.TryCacheItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_AssetQueryService.TryCacheQuest` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Aura.UnitHasAura` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BugTracker.ClearReport` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BugTracker.GetReportCategory` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BugTracker.GetReportDescription` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BugTracker.GetReportPriority` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BugTracker.GetReportTitle` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BugTracker.IsReportPublic` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BugTracker.SetReportCategory` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BugTracker.SetReportDescription` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BugTracker.SetReportPriority` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BugTracker.SetReportPublic` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BugTracker.SetReportTitle` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BugTracker.SubmitReport` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.ActivateBuild` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.BookmarkBuild` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.CanActivateBuild` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.CanDeactivateBuild` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildCreator.DeactivateBuild` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_BuildCreator.DeleteBuild` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.ExportBuild` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildCreator.GetActiveBuild` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.GetActiveSpecForBuild` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_BuildCreator.GetBookmarkedBuildAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.GetBuild` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.GetBuildAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.GetNumBookmarkedBuilds` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.GetNumBuilds` | function | . |  | interface |  | high | Y | Y | 171 |  |  |  |
| `C_BuildCreator.GetSpell` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.IsOwnedBuild` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.IsUpvotedBuild` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.QueryAllBuilds` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.QueryBuild` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.RateBuild` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildCreator.UpdateFilter` | function | . | 3 | interface |  | high | Y | Y | 189 |  |  |  |
| `C_BuildDraft.GetDraftableBuild` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildDraft.GetDraftedBuild` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildDraft.GetNumDraftableBuilds` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildDraft.IsAwaitingRolePrompt` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildDraft.IsCompletedBuild` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildDraft.IsDraftableBuild` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_BuildDraft.IsDraftedBuild` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_BuildDraft.SelectRole` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.AddArmorType` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.AddRandomEnchant` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.AddSpell` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.AddWeaponType` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanAddArmorType` | function | . | 1 | interface |  | high | Y | Y | 2 |  |  |  |
| `C_BuildEditor.CanAddRandomEnchant` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanAddSpell` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanAddWeaponType` | function | . | 1 | interface |  | high | Y | Y | 9 |  |  |  |
| `C_BuildEditor.CanPublishBuild` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanRemoveArmorType` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanRemoveRandomEnchant` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanRemoveSpell` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanRemoveWeaponType` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanSetArmorTypeComment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanSetEnchantFlags` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetEnchantLevel` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanSetIsCoreAbility` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetIsEmpoweringAbility` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetIsOptimalAbility` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetIsSynergisticAbility` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetRandomEnchantComment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanSetRandomEnchantStacks` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanSetSpellComment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.CanSetSpellFlags` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetSpellLevel` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.CanSetWeaponTypeComment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.DiscardPendingBuild` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.DoesBuildHaveEnchant` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.DoesBuildHaveSpellID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.EditBuild` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.ExportPendingBuild` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.GetEssenceForLevel` | function | . | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.GetFilteredEntryAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.GetNumFilteredEntries` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_BuildEditor.GetPendingBuild` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.GetQualityInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_BuildEditor.GetQualityInfoForLevel` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.GetSpellByID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.ImportBuild` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.ImportCurrentBuild` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.PublishBuild` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveArmorType` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveRandomEnchant` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveSpell` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.RemoveWeaponType` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetCategory` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetComment` | function |  | 2 | interface |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.SetDescription` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetDifficultyRating` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetEnchantFlags` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetEnchantLevel` | function |  | 2 | interface |  | low | Y |  | 0 |  |  |  |
| `C_BuildEditor.SetEnchantStacks` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetFilteredEntries` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetIcon` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsCoreAbility` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsEmpoweringAbility` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsOptimalAbility` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetIsSynergisticAbility` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetName` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetPrimaryStat` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetRoles` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetSpellFlags` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_BuildEditor.SetSpellLevel` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.Exists` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.Get` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetBitfield` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetBool` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetByteString` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetCVarBitfield` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CVar.GetDefault` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetDefaultBitfield` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetDefaultBool` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetDefaultNumber` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetFlag` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetMax` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetMin` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.GetNumber` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CVar.RegisterSavedCVar` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.RegisterSavedCharacterCVar` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.ResetToDefault` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.Set` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CVar.SetBitfield` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.SetCVarBitfield` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CVar.SetCVarSave` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CVar.SetFlag` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Cache.QueryAllStats` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Cache.QueryStat` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CallboardCache.GetCallboardCacheInfo` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CallboardCache.GetCurrentPoints` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CallboardCache.GetItemLevelInfo` | function | . |  | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_CallboardCache.GetPointsForQuest` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.CanActivateChallenge` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.CanDeactivateChallenge` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.CanResurrect` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetActiveChallenges` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetAllChallenges` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetAllTrials` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetBrokenChallengeRules` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeAtIndex` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeCompletion` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeCompletions` | function | . | 3 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeCriteriaInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeCriterias` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeFailure` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetChallengeFailures` | function |  | 2 | interface |  | low | Y |  | 0 |  |  |  |
| `C_Challenge.GetChallengeIDByIndex` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeInfoByLevel` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetChallengeLevels` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetChallengesWithGroupID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetCompletedChallenges` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetConditionLocalization` | function | . | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetModifierLocalization` | function | . | 1 | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetNumChallenges` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Challenge.GetPendingChallenges` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_Challenge.GetRequirementLocalization` | function | . | 1 | interface | 7 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.GetRuleLocalization` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.HasBrokenChallengeRule` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.HasChallengeRule` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.IsChallengeActive` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.QueryChallengeCompletions` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.QueryChallengeFailures` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_Challenge.SendChallengeSyncResponse` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_Challenge.SetChallengeFilter` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.StartChallenge` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Challenge.StopChallenge` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.AddByEntryID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.AddSuggestionContextOverride` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ApplyPendingBuild` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanAddByEntryID` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanApplyPendingBuild` | function | . |  | interface | 7 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanClearPendingBuild` | function | . | 1 | interface | 5 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanLearnID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanRemoveByEntryID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanSwapEntriesByID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanSwitchActiveChrSpec` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUnlearnAllSpells` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUnlearnAllTalents` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUnlearnID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CanUseBrowser` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.CancelPendingBuild` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearPendingBuild` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearPendingBuildByTab` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearRecentlyLearnedEntries` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ClearSuggestionContextOverrides` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ExportBuild` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetAbilityEssenceCost` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetActiveChrSpec` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetActiveSpecID` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetAllEntries` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetCategories` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetCategoryDisplayInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassAEInvestment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassInfo` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassPointInvestment` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetClassTEInvestment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntriesAvailableForSwap` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntriesAvailableForTrade` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntriesByClass` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntryByInternalID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetEntryBySpellID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetExpectedAE` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetExpectedTE` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetFilteredEntryAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetFilteredEntryAtIndexByCategory` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetGlobalAEInvestment` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetGlobalTEInvestment` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetImplicitByClass` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetInspectInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetInspectedBuild` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetInternalID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownSpellEntries` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownSpellEntriesForClass` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownSpells` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownTalentEntries` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetKnownTalentEntriesForClass` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetLearnedAE` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetLearnedTE` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetLowestInvestmentRequired` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetMasteriesByClass` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetNumFilteredEntries` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CharacterAdvancement.GetNumFilteredEntriesByCategory` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingClassAEInvestment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingClassPointInvestment` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingClassTEInvestment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingExpectedAE` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingExpectedTE` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingGlobalAEInvestment` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingGlobalTEInvestment` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingRankByEntryID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingRemainingAE` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingRemainingTE` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingSummary` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CharacterAdvancement.GetPendingTabAEInvestment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetPendingTabTEInvestment` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetQualityCount` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetQualityInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetQualityLimit` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetRemainingAE` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetRemainingTE` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetRootSpellTagTypes` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSpellTagTypeDisplayInfo` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSpellTagTypes` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSpellsByClass` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetSuggestedStats` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTabAEInvestment` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.GetTabTEInvestment` | function | . | 3 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentEssenceCost` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentRankByID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentRankBySpellID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.GetTalentsByClass` | function | . | 3 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.HasAnySuggestionContextOverrides` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ImportPendingBuild` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.ImportPendingBuildID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.InspectUnit` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsAbilityID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsAbilitySpellID` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.IsActiveBuildAvailable` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CharacterAdvancement.IsConnectionAllowed` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsFiltered` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsKnownID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsKnownSpellID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsLockedID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsMastery` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsPending` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsPendingBuildAvailable` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsPendingEntryID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsSuggestionContextOverride` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentAbilityID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentAbilitySpellID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.IsTalentSpellID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.KnowsConnectedNodesFor` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.LearnID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.LockID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.MeetsInvestmentForAddByEntryID` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.PickupSpell` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.RemoveByEntryID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.RemoveSuggestionContextOverride` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SetFilteredEntries` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SetFilteredEntriesByCategory` | function | . | 4 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmLearnID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmUnlearnAllSpells` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmUnlearnAllTalents` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.ShouldConfirmUnlearnID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SwapEntriesByID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.SwitchActiveChrSpec` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnitKnownID` | function | . | 3 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnitTalentRankByID` | function | . | 3 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlearnAllSpells` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlearnAllTalents` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlearnID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterAdvancement.UnlockID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.AddPet` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.CanCreateClass` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.CanCreateCoA` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.CanCreateHero` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.CanCreateWCR` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.Dress` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeCategories` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeCategoryInfo` | function | . | 1 | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeInfo` | function | . | 1 | interface | 12 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeRoleInfo` | function | . | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeRoles` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypeSpellDescription` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.GetArchetypes` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CharacterCreate.GetCameraPosition` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.PlayCastAnimation` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.PlayPetCastAnimation` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.ResetCameraPosition` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.SetCameraPosition` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.SetSelectedArchetype` | function |  | 3 | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.StopCastAnimation` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.StopPetCastAnimation` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.TryOnItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.Undress` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.ZoomIn` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_CharacterCreate.ZoomOut` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_Chat.AcknowledgeChatInfraction` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_Chat.GetChatInfraction` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Chat.HasChatInfraction` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_ClassInfo.GetAllSpecs` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_ClassInfo.GetClassBySpecName` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_ClassInfo.GetSpecInfo` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_ClassInfo.GetSpecInfoByID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CollectorCache.GetCollectorCacheItemInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheItems` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheRarityRatesInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheRarityTypeInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CollectorCache.GetCollectorCacheTypeInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CollectorCache.GetNumCollectorCacheItems` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_CollectorCache.OpenCollectorCache` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Comm.Enqueue` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Comm.IsEmpty` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Comm.OnAttributeChanged` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Comm.OnUpdate` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Comm.SendJsonMessage` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Comm.Setup` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Comm.UpdateAvailable` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Config.GetBoolConfig` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Config.GetFloatConfig` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Config.GetFloatVectorConfig` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Config.GetIntConfig` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Config.GetIntVectorConfig` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Config.GetRateConfig` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_ContentLoader.AddToParseQueue` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_ContentLoader.Load` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_ContentLoader.ResumeRoutines` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CrowdControl.COMBAT_LOG_EVENT_UNFILTERED` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CrowdControl.CROWD_CONTROL_ADDED` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CrowdControl.CROWD_CONTROL_REMOVED` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CrowdControl.GetActiveCrowdControl` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CrowdControl.GetCrowdControlInfo` | function | : | 1 | interface | 8 | medium | Y | Y | 0 |  |  |  |
| `C_CrowdControl.PLAYER_ENTERING_WORLD` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CrowdControl.UNIT_AURA` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.ApplyCustomStoreFilter` | function | . | 4 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.CanPurchaseCustomStoreItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CustomStore.CanQueryCustomStore` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreData` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreItemInfo` | function | . | 1 | interface | 6 | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreMaxPages` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.GetCustomStoreTypeInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.IsItemLockedDueToAchievement` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.IsItemLockedDueToGameEvent` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_CustomStore.PurchaseCustomStoreItem` | function |  | 2 | interface |  | low | Y |  | 0 |  |  |  |
| `C_CustomStore.QueryCustomStore` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.Adler32` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.CompressDeflate` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.CompressDeflateWithDict` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.CompressZlib` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.CompressZlibWithDict` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.CreateCodec` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.CreateDictionary` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.DecodeForPrint` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.DecodeForWoWAddonChannel` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.DecodeForWoWChatChannel` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.DecompressDeflate` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.DecompressDeflateWithDict` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.DecompressZlib` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.DecompressZlibWithDict` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.EncodeForPrint` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.EncodeForWoWAddonChannel` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.EncodeForWoWChatChannel` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Deflate.internals.InternalClearCache` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Deflate.internals.IsEqualAdler32` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Deflate.internals.IsValidDictionary` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Deflate.internals.LoadStringToTable` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_DraftRewards.CanClaimHandOfFateRewards` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_DraftRewards.ClaimHandOfFateRewards` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_DraftRewards.GetHandOfFateRewardsReleaseInfo` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_DraftRewards.GetLevelingInfo` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_DraftRewards.GetMarkOfAscensionCost` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_DraftRewards.GetNumClaimableHandOfFateRewards` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_DraftRewards.GetNumClaimedHandOfFateRewards` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_DraftRewards.GetRewards` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_EquipmentSet.PlaceInBank` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_ExtraActionButton.GetExtraActionButtonAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_ExtraActionButton.GetExtraActionButtonInfo` | function | . | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_ExtraActionButton.GetNumExtraActionButtons` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Flipbook.CreateAtlasFlipbook` | function | : | 7 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Format.Format` | function | . | 4 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_GM.GetPlayerInfo` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GM.RequestPlayerInfo` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.ApproveAutomatedMessage` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.AssignGMTicket` | function |  | 2 | interface |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CanAssignGMTicket` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CanCloseTicket` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CanMarkResponseSeen` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CanSendTicketMessage` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CanSetTicketPriority` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CanSetTicketStatus` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CanSetTicketTitle` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.CloseTicket` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.DeclineAutomatedMessage` | function |  | 2 | interface |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetAutomatedMessage` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetNumSuggestions` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetNumTickets` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetSuggestionAtIndex` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetTicketAtIndex` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetTicketByID` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetTicketMessage` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.GetTicketMessages` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.IsResponseSeen` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.IsTicketAssignedToMe` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.MarkResponseSeen` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.SendTicketMessage` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.SetTicketFilter` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.SetTicketPriority` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.SetTicketStatus` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GMTicket.SetTicketTitle` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.ASCENSION_CUSTOM_GAME_MODE_CHANGED` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.DoesFrameHaveEvent` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.GenerateCallbackEvents` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.GetActiveGameModes` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.GetCallbackTable` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GameMode.GetCallbackTables` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GameMode.GetCallbacksByEvent` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.HasRegistrantsForEvent` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GameMode.IsAnyGameModeActive` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.IsGameModeActive` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.OnLoad` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.PLAYER_ENTERING_WORLD` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.RegisterCallback` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.RegisterCallbackWithHandle` | function | : | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_GameMode.SecureInsertEvent` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.SetUndefinedEventsAllowed` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.TriggerEvent` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.UnregisterCallback` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GameMode.UnregisterEvents` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Gossip.CheckHookItemHide` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.CheckHookItemShow` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.CheckHookNPCHide` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.CheckHookNPCShow` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.CheckItemHide` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.CheckItemShow` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.CheckNPCHide` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.CheckNPCShow` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.GOSSIP_CLOSED` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.GOSSIP_SHOW` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.HookItem` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.HookItems` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.HookNPC` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.HookNPCs` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.MakeGroup` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RedirectItem` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RedirectItems` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RedirectNPC` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RedirectNPCs` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RemoveHookItem` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RemoveHookNPC` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectItem` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectItems` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectNPC` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RemoveRedirectNPCs` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.RestoreGossip` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip.SilentHideGossip` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Gossip._hookItem.generateHandle` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Gossip._hookNPC.generateHandle` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GroupFinder.CreateListing` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GroupFinder.GetActivityInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.GetAvailableActivities` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.GetAvailableCategories` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.GetAvailableGroupTypes` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.GetCategoryInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.GetGroupInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.GetGroupTypeInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.GetListedGroupID` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_GroupFinder.GetListedGroups` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_GroupFinder.QueryListedActivities` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GroupFinder.RemoveListing` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GroupFinder.RequestInvite` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_GroupFinder.UpdateListing` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_HighRisk.CanToggleFelCommutation` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_HighRisk.GetInsuranceCostPerSlot` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_HighRisk.GetInsuranceTotalCost` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_HighRisk.IsFelCommutationActive` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_HighRisk.ToggleFelCommutation` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.DumpProfiling` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.IsRegistered` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.Register` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.RegisterAllEvents` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.RegisterBucket` | function | : | 4 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.SendBlizzardEvent` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.SendEvent` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.StartProfiling` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.StopProfiling` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Hook.Unregister` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.CanUseCheckpoint` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.GetInstanceLocks` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.GetSavedMapAndDifficulty` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.HasCheckpoint` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.IsInArena` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.IsInBattleground` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.IsInDungeon` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.IsInPVE` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.IsInPVP` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Instance.IsInRaid` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_InventoryState.ClearAllNewItems` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_InventoryState.ITEM_PUSH` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_InventoryState.IsNewItem` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_InventoryState.ItemUpdate` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_InventoryState.PLAYER_ENTERED_WORLD` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_InventoryState.RemoveNewItem` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_InventoryState.UpdateCurrentItems` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Item.CanBind` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Item.GetCacheTooltip` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Item.GetColoredItemName` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Item.GetLastUsedItemID` | function | : |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Item.GetMerchantItemRatingRequirement` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Item.GetNameAndID` | function | : | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Item.GetScalingLevel` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Item.GetSlotItemPower` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Item.ITEM_USED_PAYLOAD` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Item.IsBound` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_ItemSet.GetAppearances` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_ItemSet.GetItemSetNumCollected` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_ItemSet.GetSetName` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Keystones.ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetCurrentSetBest` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetCurrentSetString` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetDungeonBest` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetDungeonBestLink` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetKeystoneDungeonInfo` | function | . | 1 | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetKeystoneInInventory` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetKeystoneInInventoryItemID` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetPlayerSaveKey` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetProfileLink` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetSetBest` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.GetTimedDungeonsForExpansion` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.MYTHIC_PLUS_COMPLETE` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.MYTHIC_PLUS_COUNTDOWN_STARTED` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.MYTHIC_PLUS_STARTED` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Keystones.SaveKeystoneRun` | function | . | 5 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_LFG.CanUseGroupFinder` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_LFG.CanUseLFD` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_LFG.CanUseManastorm` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_LFG.CanUseRandomLFD` | function | : | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_LFG.GetLFGDungeonRewards` | function | : | 1 | interface | 7 | medium | Y | Y | 0 |  |  |  |
| `C_LFG.IsRandomDungeonDisplayable` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_LFG.IsScalingDungeon` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Logger.Debug` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Logger.Error` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Logger.Info` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Logger.LFG` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_LootLockout.GetEncounterData` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_LootLockout.GetEncounterDatasForMapAndDifficulty` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_LootLockout.GetLootLockoutTimeRemaining` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_LootLockout.GetLootLockouts` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_LootLockout.GetUnitEncounterID` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_LootLockout.GetUnitLootLockForEncounter` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_LootLockout.HasEncounterDatasForMapAndDifficulty` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_LootLockout.ListInstanceBinds` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_LootLockout.QueryInstanceBinds` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_LootLockout.ResetInstanceDifficulty` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_LoyaltyPass.CanRedeemLoyaltyPassReward` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_LoyaltyPass.ClaimRewards` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_LoyaltyPass.GetTimeUntilExpiration` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_LoyaltyPass.GetTimeUntilNextReward` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_LoyaltyPass.IsLoyaltyPassActive` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_LoyaltyPass.IsLoyaltyPassExpired` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Manastorm.CanEnter` | function | . | 1 | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.CanLeave` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.CanSetLoadoutSpellAtIndex` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Manastorm.Enter` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetActiveLevel` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetActiveManastormID` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetActiveManastormType` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetAvailableLoadoutSpells` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetBoss` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetEnterableLevels` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetExperienceModifier` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetLoadoutSpellAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetManastormCacheInfo` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetMaxCompletedLevels` | function | . | 1 | interface | 5 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetNumLoadoutSlots` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetRewardModifier` | function | . | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.GetStageBonusExperience` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.IsInManastorm` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.Leave` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_Manastorm.SetLoadoutSpellAtIndex` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Manastorm.ShowObjectiveIcon` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Map.GetBestMapForUnit` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.ApplyItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.ApplySlot` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanApplyAnySlot` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanApplyItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanApplySlot` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanCollectionReforgeAnySlot` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanCollectionReforgeItem` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanCollectionReforgeSlot` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanDestroy` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanDisenchantItem` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanDisenchantSlot` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanEquipEnchant` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanEquipItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanEquipSlot` | function | . | 1 | interface | 2 | high | Y | Y | 24 |  |  |  |
| `C_MysticEnchant.CanInspect` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.CanPurchaseMysticExtract` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.CanPurchaseMysticScroll` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanReforgeItem` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanReforgeSlot` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.CanSaveApply` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CanSaveCollectionReforge` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CollectionReforgeItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.CollectionReforgeSlot` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.Destroy` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.DisenchantItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.DisenchantSlot` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.GetAppliedEnchant` | function | . | 2 | interface | 1 | high | Y | Y | 177 |  |  |  |
| `C_MysticEnchant.GetApplyChanges` | function | . |  | interface | 1 | high | Y | Y | 1 |  |  |  |
| `C_MysticEnchant.GetApplyItemCost` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.GetCollectionReforgeChanges` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.GetCollectionReforgeItemCost` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.GetCollectionReforgeSlotCost` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.GetDisenchantCost` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.GetEnchantInfoByItem` | function | . | 1 | interface | 1 | high | Y | Y | 352 |  |  |  |
| `C_MysticEnchant.GetEnchantInfoBySpell` | function | . | 1 | interface | 1 | high | Y | Y | 2870 |  |  |  |
| `C_MysticEnchant.GetMysticScrollCost` | function | . |  | interface | 1 | high | Y | Y | 2 |  |  |  |
| `C_MysticEnchant.GetMysticScrolls` | function | . |  | interface | 1 | high | Y | Y | 12 |  |  |  |
| `C_MysticEnchant.GetProgress` | function | . |  | interface | 2 | high | Y | Y | 1 |  |  |  |
| `C_MysticEnchant.GetReforgeCost` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.GetSaveCollectionReforgeSlotCost` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.HasAnyCollected` | function | . |  | interface | 1 | high | Y | Y | 1 |  |  |  |
| `C_MysticEnchant.HasAnyScroll` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.HasAnySlotEnchanted` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_MysticEnchant.HasNearbyMysticAltar` | function | . |  | interface |  | high | Y | Y | 41 |  |  |  |
| `C_MysticEnchant.Inspect` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.PurchaseMysticExtract` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.PurchaseMysticScroll` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.QueryEnchants` | function | . | 4 | interface | 2 | high | Y | Y | 86 |  |  |  |
| `C_MysticEnchant.ReforgeItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.ReforgeSlot` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.SaveApply` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.SaveCollectionReforge` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.UndoApply` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.UndoCollectionReforge` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MysticEnchant.UndoLastApply` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchant.UndoLastCollectionReforge` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchantPreset.Activate` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchantPreset.CanActivate` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchantPreset.CanSave` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchantPreset.CanUnlock` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MysticEnchantPreset.GetNumPresets` | function | . |  | interface | 1 | high | Y | Y | 13 |  |  |  |
| `C_MysticEnchantPreset.GetPresetData` | function | . | 1 | interface |  | high | Y | Y | 12 |  |  |  |
| `C_MysticEnchantPreset.Unlock` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_MythicPlus.ActivateKeystone` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneChampions` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneEncounters` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneInfo` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneTime` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetActiveKeystoneTrash` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetCurrentAffixes` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetKeystoneInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetMapEncounters` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.GetMapFinalEncounter` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.IsItemKeystone` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_MythicPlus.IsKeystoneActive` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_NamePlate.GetNamePlateForUnit` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_NamePlate.SetNamePlateSize` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.ApplyFPSIncrease` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.CheckNamePlateMotion` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.DisableBlizzPlate` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.EnumerateActiveNamePlates` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.GetNamePlateSize` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.IsNamePlateMoving` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.RefreshNamePlateSize` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.SetEnableResizeNamePlates` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NamePlateManager.SetNamePlateSize` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_NoviceNetwork.IsNewcomer` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.CanQueueCasual` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.CanQueueInHighRisk` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.CanQueueRated` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetBattlegroundFaction` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetCurrentBestRating` | function | : |  | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetEliteTierInfo` | function | : |  | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetHolidayBGInfo` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetHonorRank` | function | : | 1 | interface | 5 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetIsCurrentMapHighRisk` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetMapIsHighRisk` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetMaxGearDropAmount` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetPVPTierInfo` | function | : | 1 | interface | 6 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetRandomBGInfo` | function | : |  | interface | 10 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetRandomBrawlBGInfo` | function | : |  | interface | 10 | medium | Y | Y | 0 |  |  |  |
| `C_PVP.GetRequiredItemLevelForEvents` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.IsLegacyWarmode` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.PLAYER_ENTERING_WORLD` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PVP.ZONE_CHANGED_NEW_AREA` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetAverageItemLevel` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetClass` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetCurrentCompanion` | function | : |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetCurrentMapContinentZone` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetCurrentMapExpansion` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetCurrentMapInfo` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetFaction` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetLevel` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetName` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetPvEPower` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetPvPPower` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetRace` | function | : |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetRuleset` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetRulesetCooldown` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.GetSex` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.HasAura` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.HasBuff` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.HasDebuff` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.HasRuleset` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.InCombat` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsCustomClass` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsDead` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsDefaultClass` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsEffectivelyTank` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsGM` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsGroupLeader` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsHero` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsHighRisk` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsImmune` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsInGroup` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsInRaid` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsMaxLevel` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsNoRiskPvE` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsNoRiskPvP` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsNoRiskPvPOrHigher` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsPrestiged` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsTitansGrip` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.IsWorldPVP` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.PLAYER_ENTERING_WORLD` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.PLAYER_LEVEL_UP` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.SetRuleset` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.UNIT_PET` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Player.UpdatePvEPower` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.CanChangeQuestionChoice` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.CanSubmitAnswer` | function | . | 3 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.GetNumQuestionChoices` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.GetNumQuestions` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.GetQuestionChoiceInfo` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.GetQuestionInfo` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.HasUnansweredQuestions` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerPoll.RequestQuestionList` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_PlayerPoll.SubmitAnswer` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.CanCloseTicket` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.CanCreateTicket` | function | . | 5 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.CanMarkResponseSeen` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_PlayerTicket.CanReopenTicket` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.CanSendTicketMessage` | function | . | 3 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.CloseTicket` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_PlayerTicket.CreateTicket` | function | . | 5 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.GetCurrentTicket` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.GetTicketMessage` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_PlayerTicket.GetTicketMessages` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.IsResponseSeen` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.MarkResponseSeen` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.ReopenTicket` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PlayerTicket.SendTicketMessage` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PopupQueue.Add` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PopupQueue.AddAchievement` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.GetActivePrimaryStat` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.GetInternalID` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatAura` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatID` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatInfo` | function | : | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.GetPrimaryStatSpell` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.GetUnitPrimaryStat` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_PrimaryStat.SetPrimaryStat` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.ASCENSION_CUSTOM_QUEST_REWARDED` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.AddAutoQuestPopUp` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.ExpandAllQuestHeaders` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.GetCurrentQuests` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.GetPortraitData` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.GetQuestID` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.GetQuestIndexByID` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.GetQuestNameByID` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Quest.GetTitleByID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.HasOrHasDoneQuest` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.IsFelforgedChallenge` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.IsOnQuestID` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.IsQuerying` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.IsQuestCachedByID` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.IsQuestComplete` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.IsQuestTurnedIn` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.PLAYER_LOGIN` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.QUEST_ACCEPTED` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.QUEST_LOG_UPDATE` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.QUEST_QUERY_COMPLETE` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Quest.SendPathToAscensionEvent` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_QuestLog.GetQuestType` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_QuestLog.GetUnitQuestInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_QuestLog.GetZoneStoryInfo` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_Realm.IsDevelopment` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Realm.IsLeague` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Realm.IsLive` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Realm.IsPTR` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Realm.IsProduction` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Realm.IsSeasonal` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_RealmSelect.GetRealmInfo` | function | . | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_RecoveryService.GetCategoryItemAtIndex` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_RecoveryService.GetNumItemsInCategory` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_RecoveryService.QueryCategory` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_RecoveryService.RecoverCategoryItemAtIndex` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_RecoveryService.SwapFactionChangePotion` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_RecoveryService.SwapRaceChangePotion` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_RecoveryService.UpdateFilter` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Scenario.GetActiveStage` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Scenario.GetEncounterAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Scenario.GetNumEncounters` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Scenario.GetScenarioName` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Scenario.IsInScenario` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.CompressForURI` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.DecompressFromURI` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.Deserialize` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.DeserializeDecompressFromPrint` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.DeserializeValue` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.FromJSON` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.FromJSONCategory` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.FromJSONData` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.IsSerializableType` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.Serialize` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.SerializeCompressForPrint` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.SerializeEx` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.ToJSON` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Serialize.jsonEncoder` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_SkillCard.GetCardAtIndex` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.GetCardCount` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_SkillCard.GetCardID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.GetCardRankAtIndex` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_SkillCard.GetCardSpellID` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.GetMaxCardCount` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.GetSkillCardInfo` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.GetSkillCardInfoAtIndex` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.GetSkillCardQuality` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.IsCardAtIndexActive` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.IsCardAtIndexBlocked` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.IsCardedID` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_SkillCard.IsCardedSpellID` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_SkillCard.RemoveCardAtIndex` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCard.SetCardAtIndex` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.CanClaimPendingSkillCardAtIndex` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_SkillCardCollection.CanPurchaseSealedCard` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.CanPurchaseSealedCardBoosterPack` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.ClaimAllPendingSkillCards` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_SkillCardCollection.ClaimPendingSkillCard` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetBonusSealedCardPacksProgress` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetMaxNumPurchasableSealedCardBoosterPacks` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetMaxRank` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_SkillCardCollection.GetNumPendingSkillCards` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetNumSkillCards` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetPendingSkillCardAtIndex` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetProgress` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetSealedCardBoosterPackCost` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetSealedCardCost` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.GetSkillCardAtIndex` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.HasAnySkillCardsCollected` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.IsCollected` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.PurchaseAllSealedCards` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_SkillCardCollection.PurchaseSealedCard` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.PurchaseSealedCardBoosterPack` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SkillCardCollection.SetSkillCardFilter` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Social.FRIEND_METADATA_CHANGED` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Social.GetFriendAddedAs` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Social.SetFriendAddedAs` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.AppliesBuff` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Spell.AppliesDebuff` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Spell.GetFirstRank` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetFreeActionButton` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetFreeActionID` | function | : |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetMaxLearnableRank` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetNameAndID` | function | : | 3 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetPresetSpell` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetSpecSpell` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetSpellActionID` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetSpellDescription` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.GetSpellID` | function | : | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.HasMultipleSpellRanks` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.HasNotMaxedRanks` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.HasRuneUI` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsActionAlmostReady` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsActivePreset` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsActiveSpec` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsAnyRankKnown` | function | : | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsCastAlmostDone` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsHarmfulSpell` | function |  | 2 | interface |  | low | Y |  | 0 |  |  |  |
| `C_Spell.IsHelpfulSpell` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsImmunitySpell` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Spell.IsPresetSpell` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsSpecSpell` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.IsTrainerSpell` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Spell.PLAYER_ENTERING_WORLD` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.PLAYER_LEVEL_UP` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.PlaceSpellOnActionBar` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.RemoveSpellFromActionBar` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.SET_ACTION_BUTTON_SPELL_PAYLOAD` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.SPELLS_CHANGED` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.ShouldHoldToCast` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Spell.TabHasNotMaxedRanks` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SpellActivationOverlay.GetSpellActivationOverlayInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SpellActivationOverlay.IsSpellOverlayed` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Sun.SetX` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Sun.SetY` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Sun.SetZ` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_SuperTrack.ClearSuperTracker` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SuperTrack.GetSuperTrackedPosition` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_SuperTrack.GetSuperTrackedWorldPosition` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_SuperTrack.GetTargetState` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_SuperTrack.IsSuperTrackingAnything` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SuperTrack.PositionFrame` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SuperTrack.SetSuperTrackedCorpse` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SuperTrack.SetSuperTrackedPosition` | function | . | 4 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_SuperTrack.SetSuperTrackedQuestID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Taxi.GetCurrentTaxiNodeID` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Taxi.GetTaxiNodeID` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Taxi.GetTaxiPathDuration` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_TemporalContracts.ActivateAllTemporalContracts` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_TemporalContracts.ActivateAllTemporalContractsByContentType` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.ActivateTemporalContract` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetCategoryData` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetCategoryName` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetCompletableQuestsByCategory` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_TemporalContracts.GetCompletableTemporalContracts` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetQuestCategory` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetQuestSortIDs` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetQuestSortText` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTemporalContractInfo` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_TemporalContracts.GetTemporalContractTypes` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContentTypeCost` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContentTypeRewards` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContractTypeCost` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TemporalContracts.GetTotalContractTypeRewards` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Token.GetTokenAmount` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Token.GetTokenInfo` | function | . | 1 | interface | 4 | medium | Y | Y | 0 |  |  |  |
| `C_Token.GetTokenTypes` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_TrackerHeader.CHALLENGE_COMPLETED` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_CRITERIA_COMPLETED` | function | : | 6 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_CRITERIA_FAILED` | function | : | 6 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_DEATH_UPDATE` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrackerHeader.CHALLENGE_FAILURE_ADDED` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrackerHeader.Hide` | function | : |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrackerHeader.Show` | function | : | 7 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TradeSkill.GetCraftedItem` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_TradeSkill.GetReagentItems` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_TrialCreator.ActivateTrial` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.CanActivateTrial` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.CanDeactivateTrial` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.CanEditTrial` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.CanSaveTrial` | function | . | 7 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.DeactivateTrial` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.DeleteTrial` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.GetActiveTrial` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.GetAllTrials` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_TrialCreator.GetNumTrials` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_TrialCreator.GetOwnedTrials` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_TrialCreator.GetTrialAtIndex` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialCompletion` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialCompletions` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialIDByIndex` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.GetTrialInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.QueryTrialCompletions` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.QueryTrials` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.RateTrial` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.SaveTrial` | function | . | 7 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrialCreator.SetTrialFilter` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrinityCore.ASCENSION_LUA` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrinityCore.ConvertBagSlots` | function | : | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrinityCore.MSG_VERSION` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrinityCore.MSG_VERSION_REPLY` | function | : | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_TrinityCore.RequestPlayerVersion` | function | : | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.AddMentorSpecialization` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.AnyUnclaimedRewards` | function |  |  | interface |  | low | Y |  | 0 |  |  |  |
| `C_Tutorial.CanCollectReward` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.CanToggleMentorStatus` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.CollectReward` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.DebugTutorialAppliccability` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Tutorial.GetAvailableMentorAtIndex` | function | . | 1 | interface | 6 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetCategories` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetCategoryInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetCategoryProgress` | function | . | 1 | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetIndexByKeywordID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetKeywordAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetKeywordID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetKeywordInfo` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetMentorSpecializationActive` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetMentorSpecializationInfo` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetMentorSpecializations` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetNumAvailableMentors` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Tutorial.GetNumKeywords` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_Tutorial.GetNumTutorials` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetObjectiveInfo` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetObjectives` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetRewards` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialAtIndex` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialByID` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialDisplay` | function | . | 1 | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.GetTutorialsRequiredForMentorStatus` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.IsCategoryEnabled` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.IsMentorStatusActive` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.IsRewardCollected` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.IsTutorialAvailable` | function | . | 1 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.IsTutorialComplete` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.IsTutorialRequiredForMentorStatus` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.QueryActiveMentors` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.RemoveMentorSpecialization` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.SetAvailableMentorFilter` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.SetKeywordFilter` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.SetTutorialFilter` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.StartQuest` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Tutorial.ToggleMentorStatus` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_UICamera.GetCameraInfo` | function | . | 1 | interface | 5 | medium | Y | Y | 0 |  |  |  |
| `C_UICamera.GetItemCameraID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_VanityCollection.GetAllItems` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_VanityCollection.GetDPPrice` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_VanityCollection.GetItem` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_VanityCollection.GetNum` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_VanityCollection.GetVPPrice` | function |  |  |  |  | low | Y |  | 0 | Y |  |  |
| `C_VanityCollection.IsCollectionItemOwned` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_VanityCollection.IsConsolidatedVanityBuff` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_VanityCollection.IsPurchaseInProgress` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_VanityCollection.PurchaseCollectionItem` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_VanityCollection.PurchaseWebShopItem` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.AddAllDesiredFilter` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.AddAllUndesiredFilter` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.AddDesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.AddUndesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanAddDesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanAddUndesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanRepurchaseAbilityRolls` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.CanRepurchaseAnyRolls` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanRepurchaseRolls` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanRepurchaseTalentRolls` | function | . | 2 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanResetAbilities` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanRollAbilities` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanStartRapidRolling` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.CanUseRapidRolling` | function | . |  | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.ClearDesiredSpells` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.ClearUndesiredSpells` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetFilteredDesiredEntryAtIndex` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetFilteredUndesiredEntryAtIndex` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetMaxRepurchasableAbilityRolls` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.GetMaxRepurchasableRolls` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.GetMaxRepurchasableTalentRolls` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.GetMaximumRapidRolls` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetNextUnlearnedID` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetNumFilteredDesiredEntries` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetNumFilteredUndesiredEntries` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetNumRepurchasableAbilityRolls` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.GetNumRepurchasableRolls` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetNumRepurchasableTalentRolls` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetRapidRollAbilityBreakpointInfo` | function | . |  | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetRapidRollTalentBreakpointInfo` | function | . |  | interface | 3 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetRepurchaseAbilityRollCost` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.GetRepurchaseRollCost` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetRepurchaseTalentRollCost` | function | . | 2 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.GetRollIcons` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.IsDesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.IsRapidRollingEnabled` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.IsUndesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.RemoveAllUndesiredAbilities` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.RemoveAllUndesiredTalents` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.RemoveDesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.RemoveUndesiredID` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.RepurchaseAbilityRolls` | function |  |  |  |  | low | Y |  | 0 |  |  |  |
| `C_Wildcard.RepurchaseRolls` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.RepurchaseTalentRolls` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.ResetAbilities` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.RollAbilities` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.SetFilteredDesiredEntries` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.SetFilteredUndesiredEntries` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.StartRapidRolling` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.UnlearnAbility` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_Wildcard.WillRollStartingAbilities` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.CanClaimScrollOfFortuneRewards` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.ClaimScrollOfFortuneRewards` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.GetLevelingInfo` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.GetMarkOfAscensionCost` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.GetNumClaimableScrollOfFortuneRewards` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.GetNumClaimedScrollOfFortuneRewards` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.GetRewards` | function | . | 3 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WildcardRewards.GetScrollOfFortuneRewardsReleaseInfo` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.CanShowPOI` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetCurrentMapID` | function | . |  | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetMapFileByAreaID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetMapFileByZoneID` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_WorldMap.GetMapIDByAreaID` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetMapIDByZoneID` | function | . | 1 | interface | 1 | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetMapPosition` | function | . | 4 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetPOIFilter` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetVisiblePOI` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetWorldPosition` | function | . | 3 | interface | 2 | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.GetZoneIDByAreaID` | function |  | 1 | interface |  | low | Y |  | 0 |  |  |  |
| `C_WorldMap.IsOnCityMap` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.IsOnContinentMap` | function | . |  | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.SetPOIFilter` | function | . | 2 | interface |  | medium | Y | Y | 0 |  |  |  |
| `C_WorldMap.SetPOIFilters` | function | . | 1 | interface |  | medium | Y | Y | 0 |  |  |  |
