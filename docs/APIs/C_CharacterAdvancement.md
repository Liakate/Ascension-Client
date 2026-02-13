# C_CharacterAdvancement



**Members:** 127  •  **Functions:** 127  •  **Interface calls:** 582 (across up to 22 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| AddByEntryID | function | C_CharacterAdvancement.AddByEntryID(arg1, arg2) | C_CharacterAdvancement.AddByEntryID(dropdown.targetEntry.ID, numRanks) |
| AddSuggestionContextOverride | function | C_CharacterAdvancement.AddSuggestionContextOverride(arg1) | C_CharacterAdvancement.AddSuggestionContextOverride(dropdown.targetEntry.ID) |
| ApplyPendingBuild | function | C_CharacterAdvancement.ApplyPendingBuild() | C_CharacterAdvancement.ApplyPendingBuild() |
| CanAddByEntryID | function | C_CharacterAdvancement.CanAddByEntryID(arg1, arg2) | info.disabled = not C_CharacterAdvancement.CanAddByEntryID(dropdown.targetEntry.ID, numRanks) |
| CanApplyPendingBuild | function | C_CharacterAdvancement.CanApplyPendingBuild() | local canApply, reason, traversalError, entryID, entryRank, marksCost, goldCost = C_CharacterAdva... |
| CanClearPendingBuild | function | C_CharacterAdvancement.CanClearPendingBuild(arg1) | local canReset, reason, traversalError, entryID, entryRank = C_CharacterAdvancement.CanClearPendi... |
| CanLearnID | function | C_CharacterAdvancement.CanLearnID(arg1) | info.disabled = not C_CharacterAdvancement.CanLearnID(entry.ID) |
| CanRemoveByEntryID | function | C_CharacterAdvancement.CanRemoveByEntryID(arg1) | local canUnlearn, reason = C_CharacterAdvancement.CanRemoveByEntryID(dropdown.targetEntry.ID) |
| CanSwapEntriesByID | function | C_CharacterAdvancement.CanSwapEntriesByID(arg1) | if C_CharacterAdvancement.CanSwapEntriesByID(swapData) then |
| CanSwitchActiveChrSpec | function | C_CharacterAdvancement.CanSwitchActiveChrSpec(arg1) | if not C_CharacterAdvancement.CanSwitchActiveChrSpec(self.specInfo.ID) then |
| CanUnlearnAllSpells | function | C_CharacterAdvancement.CanUnlearnAllSpells() | canReset, reason = C_CharacterAdvancement.CanUnlearnAllSpells() |
| CanUnlearnAllTalents | function | C_CharacterAdvancement.CanUnlearnAllTalents() | local canReset, reason = C_CharacterAdvancement.CanUnlearnAllTalents() |
| CanUnlearnID | function | C_CharacterAdvancement.CanUnlearnID(arg1) | info.disabled = not C_CharacterAdvancement.CanUnlearnID(entry.ID) |
| CanUseBrowser | function | C_CharacterAdvancement.CanUseBrowser() | function C_CharacterAdvancement.CanUseBrowser() |
| CancelPendingBuild | function | C_CharacterAdvancement.CancelPendingBuild() | C_CharacterAdvancement.CancelPendingBuild() |
| ClearPendingBuild | function | C_CharacterAdvancement.ClearPendingBuild(arg1) | C_CharacterAdvancement.ClearPendingBuild(Const.CharacterAdvancement.OnlyClearAllowed) |
| ClearPendingBuildByTab | function | C_CharacterAdvancement.ClearPendingBuildByTab(arg1, arg2, arg3) | C_CharacterAdvancement.ClearPendingBuildByTab(self.class, self.tab, clearType) |
| ClearRecentlyLearnedEntries | function | C_CharacterAdvancement.ClearRecentlyLearnedEntries() | C_CharacterAdvancement.ClearRecentlyLearnedEntries() |
| ClearSuggestionContextOverrides | function | C_CharacterAdvancement.ClearSuggestionContextOverrides() | C_CharacterAdvancement.ClearSuggestionContextOverrides() |
| ExportBuild | function | C_CharacterAdvancement.ExportBuild(arg1) | local buildLink = C_CharacterAdvancement.ExportBuild(true) |
| GetAbilityEssenceCost | function | C_CharacterAdvancement.GetAbilityEssenceCost(arg1) | local aeCost = C_CharacterAdvancement.GetAbilityEssenceCost(self.spellID) or 0 |
| GetActiveChrSpec | function | C_CharacterAdvancement.GetActiveChrSpec() | local activeSpecID = C_CharacterAdvancement.GetActiveChrSpec() |
| GetActiveSpecID | function | C_CharacterAdvancement.GetActiveSpecID() | local activeId = C_CharacterAdvancement.GetActiveSpecID() |
| GetAllEntries | function | C_CharacterAdvancement.GetAllEntries() | for _, data in ipairs(C_CharacterAdvancement.GetAllEntries()) do |
| GetCategories | function | C_CharacterAdvancement.GetCategories() | local categories = C_CharacterAdvancement.GetCategories() |
| GetCategoryDisplayInfo | function | C_CharacterAdvancement.GetCategoryDisplayInfo(arg1) | local reqLevel, name, icon, description = C_CharacterAdvancement.GetCategoryDisplayInfo(categoryID) |
| GetClassAEInvestment | function | C_CharacterAdvancement.GetClassAEInvestment(...) |  |
| GetClassInfo | function | C_CharacterAdvancement.GetClassInfo(arg1) | local class, spec = C_CharacterAdvancement.GetClassInfo(self.spellID) |
| GetClassPointInvestment | function | C_CharacterAdvancement.GetClassPointInvestment(arg1, arg2) | local classTESpent = C_CharacterAdvancement.GetClassPointInvestment(class, 0) or 0 |
| GetClassTEInvestment | function | C_CharacterAdvancement.GetClassTEInvestment(...) |  |
| GetEntriesAvailableForSwap | function | C_CharacterAdvancement.GetEntriesAvailableForSwap(arg1) | swapSuggestions = C_CharacterAdvancement.GetEntriesAvailableForSwap({Entry = dropdown.targetEntry... |
| GetEntriesAvailableForTrade | function | C_CharacterAdvancement.GetEntriesAvailableForTrade(arg1) | swapSuggestions = C_CharacterAdvancement.GetEntriesAvailableForTrade({Entry = dropdown.targetEntr... |
| GetEntriesByClass | function | C_CharacterAdvancement.GetEntriesByClass(...) |  |
| GetEntryByInternalID | function | C_CharacterAdvancement.GetEntryByInternalID(arg1) | local talentInfo = C_CharacterAdvancement.GetEntryByInternalID(talent.TalentID) |
| GetEntryBySpellID | function | C_CharacterAdvancement.GetEntryBySpellID(arg1) | local entry = C_CharacterAdvancement.GetEntryBySpellID(dropdown.spell) |
| GetExpectedAE | function | C_CharacterAdvancement.GetExpectedAE(arg1) | self.expectedAEByLevel[i] = C_CharacterAdvancement.GetExpectedAE(i) or 0 |
| GetExpectedTE | function | C_CharacterAdvancement.GetExpectedTE(...) |  |
| GetFilteredEntryAtIndex | function | C_CharacterAdvancement.GetFilteredEntryAtIndex(arg1) | self.entry = C_CharacterAdvancement.GetFilteredEntryAtIndex(self.index) |
| GetFilteredEntryAtIndexByCategory | function | C_CharacterAdvancement.GetFilteredEntryAtIndexByCategory(arg1, arg2) | local entry, isSuggested = C_CharacterAdvancement.GetFilteredEntryAtIndexByCategory(self:GetCateg... |
| GetGlobalAEInvestment | function | C_CharacterAdvancement.GetGlobalAEInvestment() | local totalAESpent = C_CharacterAdvancement.GetGlobalAEInvestment() or 0 |
| GetGlobalTEInvestment | function | C_CharacterAdvancement.GetGlobalTEInvestment() | local totalTESpent = C_CharacterAdvancement.GetGlobalTEInvestment() or 0 |
| GetImplicitByClass | function | C_CharacterAdvancement.GetImplicitByClass(arg1, arg2) | for _, entry in ipairs(C_CharacterAdvancement.GetImplicitByClass(class, spec)) do |
| GetInspectInfo | function | C_CharacterAdvancement.GetInspectInfo(arg1) | local _, unlockedSpecs = C_CharacterAdvancement.GetInspectInfo(AscensionInspectFrame:GetUnit()) |
| GetInspectedBuild | function | C_CharacterAdvancement.GetInspectedBuild(arg1, arg2) | local entries = C_CharacterAdvancement.GetInspectedBuild(unit, self.activeSpec) |
| GetInternalID | function | C_CharacterAdvancement.GetInternalID(arg1) | table.insert(internalIDs, {C_CharacterAdvancement.GetInternalID(spellID), 1}) |
| GetKnownSpellEntries | function | C_CharacterAdvancement.GetKnownSpellEntries() | for i, entry in ipairs(C_CharacterAdvancement.GetKnownSpellEntries()) do |
| GetKnownSpellEntriesForClass | function | C_CharacterAdvancement.GetKnownSpellEntriesForClass(arg1, arg2) | local knownSpells = C_CharacterAdvancement.GetKnownSpellEntriesForClass(CharacterAdvancementUtil.... |
| GetKnownSpells | function | C_CharacterAdvancement.GetKnownSpells() | for _, spellID in ipairs(C_CharacterAdvancement.GetKnownSpells()) do |
| GetKnownTalentEntries | function | C_CharacterAdvancement.GetKnownTalentEntries() | for i, entry in ipairs(C_CharacterAdvancement.GetKnownTalentEntries()) do |
| GetKnownTalentEntriesForClass | function | C_CharacterAdvancement.GetKnownTalentEntriesForClass(arg1, arg2) | local knownTalents = C_CharacterAdvancement.GetKnownTalentEntriesForClass(CharacterAdvancementUti... |
| GetLearnedAE | function | C_CharacterAdvancement.GetLearnedAE() | local ae = C_CharacterAdvancement.GetLearnedAE(class, spec) |
| GetLearnedTE | function | C_CharacterAdvancement.GetLearnedTE() | local te = C_CharacterAdvancement.GetLearnedTE(class, spec) |
| GetLowestInvestmentRequired | function | C_CharacterAdvancement.GetLowestInvestmentRequired(...) |  |
| GetMasteriesByClass | function | C_CharacterAdvancement.GetMasteriesByClass(arg1, arg2) | for _, entry in ipairs(C_CharacterAdvancement.GetMasteriesByClass(class, spec)) do |
| GetNumFilteredEntries | function | C_CharacterAdvancement.GetNumFilteredEntries(...) | self.SideBar.SpellList:SetGetNumResultsFunction(C_CharacterAdvancement.GetNumFilteredEntries) |
| GetNumFilteredEntriesByCategory | function | C_CharacterAdvancement.GetNumFilteredEntriesByCategory(arg1) | local categoryTotalResults = C_CharacterAdvancement.GetNumFilteredEntriesByCategory(categoryID) |
| GetPendingClassAEInvestment | function | C_CharacterAdvancement.GetPendingClassAEInvestment(...) |  |
| GetPendingClassPointInvestment | function | C_CharacterAdvancement.GetPendingClassPointInvestment(arg1) | return C_CVar.GetBool("previewCharacterAdvancementChanges") and C_CharacterAdvancement.GetPending... |
| GetPendingClassTEInvestment | function | C_CharacterAdvancement.GetPendingClassTEInvestment(...) |  |
| GetPendingExpectedAE | function | C_CharacterAdvancement.GetPendingExpectedAE(...) |  |
| GetPendingExpectedTE | function | C_CharacterAdvancement.GetPendingExpectedTE(...) |  |
| GetPendingGlobalAEInvestment | function | C_CharacterAdvancement.GetPendingGlobalAEInvestment(arg1) | return C_CVar.GetBool("previewCharacterAdvancementChanges") and C_CharacterAdvancement.GetPending... |
| GetPendingGlobalTEInvestment | function | C_CharacterAdvancement.GetPendingGlobalTEInvestment(arg1) | return C_CVar.GetBool("previewCharacterAdvancementChanges") and C_CharacterAdvancement.GetPending... |
| GetPendingRankByEntryID | function | C_CharacterAdvancement.GetPendingRankByEntryID(arg1) | rank, maxRank = C_CharacterAdvancement.GetPendingRankByEntryID(entry.ID) |
| GetPendingRemainingAE | function | C_CharacterAdvancement.GetPendingRemainingAE() | aeCount = C_CharacterAdvancement.IsPending() and C_CharacterAdvancement.GetPendingRemainingAE() o... |
| GetPendingRemainingTE | function | C_CharacterAdvancement.GetPendingRemainingTE() | teCount = C_CharacterAdvancement.IsPending() and C_CharacterAdvancement.GetPendingRemainingTE() o... |
| GetPendingSummary | function | C_CharacterAdvancement.GetPendingSummary(...) |  |
| GetPendingTabAEInvestment | function | C_CharacterAdvancement.GetPendingTabAEInvestment(...) |  |
| GetPendingTabTEInvestment | function | C_CharacterAdvancement.GetPendingTabTEInvestment(arg1) | return C_CVar.GetBool("previewCharacterAdvancementChanges") and C_CharacterAdvancement.GetPending... |
| GetQualityCount | function | C_CharacterAdvancement.GetQualityCount(arg1) | amount = C_CharacterAdvancement.GetQualityCount(self.quality) |
| GetQualityInfo | function | C_CharacterAdvancement.GetQualityInfo(arg1) | local quality, qualityCount = C_CharacterAdvancement.GetQualityInfo(spellID) |
| GetQualityLimit | function | C_CharacterAdvancement.GetQualityLimit(arg1) | local limit = C_CharacterAdvancement.GetQualityLimit(self.quality) |
| GetRemainingAE | function | C_CharacterAdvancement.GetRemainingAE() | return C_CharacterAdvancement.GetRemainingAE() or 0 |
| GetRemainingTE | function | C_CharacterAdvancement.GetRemainingTE() | return C_CharacterAdvancement.GetRemainingTE() or 0 |
| GetRootSpellTagTypes | function | C_CharacterAdvancement.GetRootSpellTagTypes() | local rootTags = C_CharacterAdvancement.GetRootSpellTagTypes() |
| GetSpellTagTypeDisplayInfo | function | C_CharacterAdvancement.GetSpellTagTypeDisplayInfo(arg1) | local name = C_CharacterAdvancement.GetSpellTagTypeDisplayInfo(value) or value |
| GetSpellTagTypes | function | C_CharacterAdvancement.GetSpellTagTypes(arg1) | tags = C_CharacterAdvancement.GetSpellTagTypes(rootTag) |
| GetSpellsByClass | function | C_CharacterAdvancement.GetSpellsByClass(arg1, arg2, arg3) | for i, entry in ipairs(C_CharacterAdvancement.GetSpellsByClass(class, spec, false)) do |
| GetSuggestedStats | function | C_CharacterAdvancement.GetSuggestedStats() | local topStat, topStats = C_CharacterAdvancement.GetSuggestedStats() |
| GetTabAEInvestment | function | C_CharacterAdvancement.GetTabAEInvestment(...) |  |
| GetTabTEInvestment | function | C_CharacterAdvancement.GetTabTEInvestment(arg1, arg2, arg3) | local treeTESpent = C_CharacterAdvancement.GetTabTEInvestment(class, spec, 0) or 0 |
| GetTalentEssenceCost | function | C_CharacterAdvancement.GetTalentEssenceCost(arg1) | local teCost = C_CharacterAdvancement.GetTalentEssenceCost(spellID) or 0 |
| GetTalentRankByID | function | C_CharacterAdvancement.GetTalentRankByID(arg1) | local currentRank, maxRank = C_CharacterAdvancement.GetTalentRankByID(entry.ID) |
| GetTalentRankBySpellID | function | C_CharacterAdvancement.GetTalentRankBySpellID(arg1) | local talentRank = C_CharacterAdvancement.GetTalentRankBySpellID(spellID) |
| GetTalentsByClass | function | C_CharacterAdvancement.GetTalentsByClass(arg1, arg2, arg3) | for i, entry in ipairs(C_CharacterAdvancement.GetTalentsByClass(class, spec, false)) do |
| HasAnySuggestionContextOverrides | function | C_CharacterAdvancement.HasAnySuggestionContextOverrides() | if C_CharacterAdvancement.HasAnySuggestionContextOverrides() then |
| ImportPendingBuild | function | C_CharacterAdvancement.ImportPendingBuild(arg1) |  |
| ImportPendingBuildID | function | C_CharacterAdvancement.ImportPendingBuildID(arg1) | C_CharacterAdvancement.ImportPendingBuildID(buildID) |
| InspectUnit | function | C_CharacterAdvancement.InspectUnit(arg1) | C_CharacterAdvancement.InspectUnit(AscensionInspectFrame:GetUnit()) |
| IsAbilityID | function | C_CharacterAdvancement.IsAbilityID(arg1) | elseif C_CharacterAdvancement.IsAbilityID(internalID) or C_CharacterAdvancement.IsTalentAbilityID... |
| IsAbilitySpellID | function | C_CharacterAdvancement.IsAbilitySpellID(...) |  |
| IsActiveBuildAvailable | function | C_CharacterAdvancement.IsActiveBuildAvailable(...) |  |
| IsConnectionAllowed | function | C_CharacterAdvancement.IsConnectionAllowed(arg1, arg2) | return C_CharacterAdvancement.IsConnectionAllowed(otherEntryID, self.entry.ID) |
| IsFiltered | function | C_CharacterAdvancement.IsFiltered(arg1) | self.Icon.LocationIcon:SetShown(C_CharacterAdvancement.IsFiltered(self.entry.ID)) |
| IsKnownID | function | C_CharacterAdvancement.IsKnownID(arg1) | if C_CharacterAdvancement.IsKnownID(dropdown.targetEntry.ID) and C_GameMode:IsGameModeActive(Enum... |
| IsKnownSpellID | function | C_CharacterAdvancement.IsKnownSpellID(arg1) | self.Icon.Known:SetShown(C_CharacterAdvancement.IsKnownSpellID(spellID)) |
| IsLockedID | function | C_CharacterAdvancement.IsLockedID(arg1) | if C_CharacterAdvancement.IsLockedID(dropdown.targetEntry.ID) then |
| IsMastery | function | C_CharacterAdvancement.IsMastery(arg1) | elseif C_CharacterAdvancement.IsMastery(entry.Spells[1]) then |
| IsPending | function | C_CharacterAdvancement.IsPending() | if C_CharacterAdvancement.IsPending() then |
| IsPendingBuildAvailable | function | C_CharacterAdvancement.IsPendingBuildAvailable() | if C_CharacterAdvancement.IsPendingBuildAvailable() then |
| IsPendingEntryID | function | C_CharacterAdvancement.IsPendingEntryID(arg1) | C_CharacterAdvancement.IsPendingEntryID(self.nodeID) or |
| IsSuggestionContextOverride | function | C_CharacterAdvancement.IsSuggestionContextOverride(arg1) | if C_CharacterAdvancement.IsSuggestionContextOverride(dropdown.targetEntry.ID) then |
| IsTalentAbilityID | function | C_CharacterAdvancement.IsTalentAbilityID(arg1) | if C_CharacterAdvancement.IsTalentID(entry.ID) or C_CharacterAdvancement.IsTalentAbilityID(entry.... |
| IsTalentAbilitySpellID | function | C_CharacterAdvancement.IsTalentAbilitySpellID(arg1) | elseif C_CharacterAdvancement.IsTalentAbilitySpellID(dropdown.spellID) then |
| IsTalentID | function | C_CharacterAdvancement.IsTalentID(arg1) | if C_CharacterAdvancement.IsTalentID(entry.ID) or C_CharacterAdvancement.IsTalentAbilityID(entry.... |
| IsTalentSpellID | function | C_CharacterAdvancement.IsTalentSpellID(arg1) | if C_CharacterAdvancement.IsTalentSpellID(self.spellID) then |
| KnowsConnectedNodesFor | function | C_CharacterAdvancement.KnowsConnectedNodesFor(arg1) | local canAdd = C_CharacterAdvancement.KnowsConnectedNodesFor(entry.ID) |
| LearnID | function | C_CharacterAdvancement.LearnID(arg1) | DevConsole:Print("Example: dfunc C_CharacterAdvancement.LearnID") |
| LockID | function | C_CharacterAdvancement.LockID(arg1) | C_CharacterAdvancement.LockID(dropdown.targetEntry.ID) |
| MeetsInvestmentForAddByEntryID | function | C_CharacterAdvancement.MeetsInvestmentForAddByEntryID(arg1, arg2) | self.isGated = not C_CharacterAdvancement.MeetsInvestmentForAddByEntryID(self.entry.ID, numRanks) |
| PickupSpell | function | C_CharacterAdvancement.PickupSpell(arg1) | C_CharacterAdvancement.PickupSpell(self.entry.ID) |
| RemoveByEntryID | function | C_CharacterAdvancement.RemoveByEntryID(arg1) | C_CharacterAdvancement.RemoveByEntryID(dropdown.targetEntry.ID) |
| RemoveSuggestionContextOverride | function | C_CharacterAdvancement.RemoveSuggestionContextOverride(arg1) | C_CharacterAdvancement.RemoveSuggestionContextOverride(dropdown.targetEntry.ID) |
| SetFilteredEntries | function | C_CharacterAdvancement.SetFilteredEntries(arg1, arg2) | C_CharacterAdvancement.SetFilteredEntries("", OnlyKnownFilter) |
| SetFilteredEntriesByCategory | function | C_CharacterAdvancement.SetFilteredEntriesByCategory(arg1, arg2, arg3, arg4) | C_CharacterAdvancement.SetFilteredEntriesByCategory(categoryID, filterOutput[2], searchQuery or "... |
| ShouldConfirmLearnID | function | C_CharacterAdvancement.ShouldConfirmLearnID(arg1) | local shouldConfirm, reasons = C_CharacterAdvancement.ShouldConfirmLearnID(internalID) |
| ShouldConfirmUnlearnAllSpells | function | C_CharacterAdvancement.ShouldConfirmUnlearnAllSpells() | local shouldConfirm, reasons = C_CharacterAdvancement.ShouldConfirmUnlearnAllSpells() |
| ShouldConfirmUnlearnAllTalents | function | C_CharacterAdvancement.ShouldConfirmUnlearnAllTalents() | local shouldConfirm, reasons = C_CharacterAdvancement.ShouldConfirmUnlearnAllTalents() |
| ShouldConfirmUnlearnID | function | C_CharacterAdvancement.ShouldConfirmUnlearnID(arg1) | local shouldConfirm, reasons = C_CharacterAdvancement.ShouldConfirmUnlearnID(internalID) |
| SwapEntriesByID | function | C_CharacterAdvancement.SwapEntriesByID(arg1) | C_CharacterAdvancement.SwapEntriesByID(swapData) |
| SwitchActiveChrSpec | function | C_CharacterAdvancement.SwitchActiveChrSpec(arg1) | C_CharacterAdvancement.SwitchActiveChrSpec(specID) |
| UnitKnownID | function | C_CharacterAdvancement.UnitKnownID(arg1, arg2, arg3) | if C_CharacterAdvancement.UnitKnownID(unit, entry.ID, self.activeSpec) then |
| UnitTalentRankByID | function | C_CharacterAdvancement.UnitTalentRankByID(arg1, arg2, arg3) | local currentRank = C_CharacterAdvancement.UnitTalentRankByID(unit, entry.ID, self.activeSpec) |
| UnlearnAllSpells | function | C_CharacterAdvancement.UnlearnAllSpells() | C_CharacterAdvancement.UnlearnAllSpells() |
| UnlearnAllTalents | function | C_CharacterAdvancement.UnlearnAllTalents() | C_CharacterAdvancement.UnlearnAllTalents() |
| UnlearnID | function | C_CharacterAdvancement.UnlearnID(arg1) | C_CharacterAdvancement.UnlearnID(spells) |
| UnlockID | function | C_CharacterAdvancement.UnlockID(arg1) | C_CharacterAdvancement.UnlockID(dropdown.targetEntry.ID) |



## Notes


- 3 member(s) had a runtime probe marked `ok` in the scan data.
