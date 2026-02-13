# C_Wildcard



**Members:** 51  •  **Functions:** 51  •  **Interface calls:** 76 (across up to 5 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| AddAllDesiredFilter | function | C_Wildcard.AddAllDesiredFilter() |  |
| AddAllUndesiredFilter | function | C_Wildcard.AddAllUndesiredFilter(...) |  |
| AddDesiredID | function | C_Wildcard.AddDesiredID(arg1, arg2) | C_Wildcard.AddDesiredID(id, spellType) |
| AddUndesiredID | function | C_Wildcard.AddUndesiredID(arg1, arg2) | C_Wildcard.AddUndesiredID(ID, entry.Type) |
| CanAddDesiredID | function | C_Wildcard.CanAddDesiredID(arg1, arg2) | return C_Wildcard.CanAddDesiredID(self.entry.ID, self.entry.Type) |
| CanAddUndesiredID | function | C_Wildcard.CanAddUndesiredID(arg1, arg2) | if C_Wildcard.CanAddUndesiredID(id, spellType) then |
| CanRepurchaseAbilityRolls | function | C_Wildcard.CanRepurchaseAbilityRolls(...) |  |
| CanRepurchaseAnyRolls | function | C_Wildcard.CanRepurchaseAnyRolls(arg1) | tab:SetTabEnabled(C_Wildcard.CanRepurchaseAnyRolls(false), REPURCHASE_SCROLLS, REPURCHASE_SCROLLS... |
| CanRepurchaseRolls | function | C_Wildcard.CanRepurchaseRolls(arg1, arg2) | local canPurchase, error = C_Wildcard.CanRepurchaseRolls(self.scrollClaimAmount, isUsingGold) |
| CanRepurchaseTalentRolls | function | C_Wildcard.CanRepurchaseTalentRolls(arg1, arg2) | local canPurchase, error = C_Wildcard.CanRepurchaseTalentRolls(self.talentScrollClaimAmount, false) |
| CanResetAbilities | function | C_Wildcard.CanResetAbilities() | if (C_Wildcard.CanResetAbilities()) then |
| CanRollAbilities | function | C_Wildcard.CanRollAbilities() | if not C_Wildcard.CanRollAbilities() then |
| CanStartRapidRolling | function | C_Wildcard.CanStartRapidRolling() | local canRoll, reason = C_Wildcard.CanStartRapidRolling() |
| CanUseRapidRolling | function | C_Wildcard.CanUseRapidRolling() | local canActivate = C_Wildcard.CanUseRapidRolling() |
| ClearDesiredSpells | function | C_Wildcard.ClearDesiredSpells() | C_Wildcard.ClearDesiredSpells() |
| ClearUndesiredSpells | function | C_Wildcard.ClearUndesiredSpells() | C_Wildcard.ClearUndesiredSpells() |
| GetFilteredDesiredEntryAtIndex | function | C_Wildcard.GetFilteredDesiredEntryAtIndex(arg1) | return C_Wildcard.GetFilteredDesiredEntryAtIndex(self.index) |
| GetFilteredUndesiredEntryAtIndex | function | C_Wildcard.GetFilteredUndesiredEntryAtIndex(arg1) | return C_Wildcard.GetFilteredUndesiredEntryAtIndex(self.index) |
| GetMaxRepurchasableAbilityRolls | function | C_Wildcard.GetMaxRepurchasableAbilityRolls(...) |  |
| GetMaxRepurchasableRolls | function | C_Wildcard.GetMaxRepurchasableRolls(...) |  |
| GetMaxRepurchasableTalentRolls | function | C_Wildcard.GetMaxRepurchasableTalentRolls(...) |  |
| GetMaximumRapidRolls | function | C_Wildcard.GetMaximumRapidRolls() | local maxRolls = C_Wildcard.GetMaximumRapidRolls() |
| GetNextUnlearnedID | function | C_Wildcard.GetNextUnlearnedID() | if C_Wildcard.GetNextUnlearnedID() == self.entry.ID then |
| GetNumFilteredDesiredEntries | function | C_Wildcard.GetNumFilteredDesiredEntries() | local numDesired = C_Wildcard.GetNumFilteredDesiredEntries() |
| GetNumFilteredUndesiredEntries | function | C_Wildcard.GetNumFilteredUndesiredEntries() | local numUndesired = C_Wildcard.GetNumFilteredUndesiredEntries() |
| GetNumRepurchasableAbilityRolls | function | C_Wildcard.GetNumRepurchasableAbilityRolls(...) |  |
| GetNumRepurchasableRolls | function | C_Wildcard.GetNumRepurchasableRolls() | local maximumClaim = C_Wildcard.GetNumRepurchasableRolls() |
| GetNumRepurchasableTalentRolls | function | C_Wildcard.GetNumRepurchasableTalentRolls() | local maximumClaim = C_Wildcard.GetNumRepurchasableTalentRolls() |
| GetRapidRollAbilityBreakpointInfo | function | C_Wildcard.GetRapidRollAbilityBreakpointInfo() | local currentRolls = C_Wildcard.GetRapidRollAbilityBreakpointInfo() |
| GetRapidRollTalentBreakpointInfo | function | C_Wildcard.GetRapidRollTalentBreakpointInfo() | local currentRolls = C_Wildcard.GetRapidRollTalentBreakpointInfo() |
| GetRepurchaseAbilityRollCost | function | C_Wildcard.GetRepurchaseAbilityRollCost(...) |  |
| GetRepurchaseRollCost | function | C_Wildcard.GetRepurchaseRollCost(arg1, arg2) | local cost = C_Wildcard.GetRepurchaseRollCost(self.scrollClaimAmount, isUsingGold) |
| GetRepurchaseTalentRollCost | function | C_Wildcard.GetRepurchaseTalentRollCost(arg1, arg2) | local cost = C_Wildcard.GetRepurchaseTalentRollCost(self.talentScrollClaimAmount, isUsingGold) |
| GetRollIcons | function | C_Wildcard.GetRollIcons(arg1) | local fakeInternalIDs = C_Wildcard.GetRollIcons(self.iconsTotal) |
| IsDesiredID | function | C_Wildcard.IsDesiredID(arg1, arg2) | return C_Wildcard.IsDesiredID(self.entry.ID, self.entry.Type) |
| IsRapidRollingEnabled | function | C_Wildcard.IsRapidRollingEnabled(...) |  |
| IsUndesiredID | function | C_Wildcard.IsUndesiredID(arg1, arg2) | elseif not C_Wildcard.IsUndesiredID(id, spellType) then |
| RemoveAllUndesiredAbilities | function | C_Wildcard.RemoveAllUndesiredAbilities(...) |  |
| RemoveAllUndesiredTalents | function | C_Wildcard.RemoveAllUndesiredTalents(...) |  |
| RemoveDesiredID | function | C_Wildcard.RemoveDesiredID(arg1, arg2) | C_Wildcard.RemoveDesiredID(entryID, entryType) |
| RemoveUndesiredID | function | C_Wildcard.RemoveUndesiredID(arg1, arg2) | C_Wildcard.RemoveUndesiredID(entryID, entryType) |
| RepurchaseAbilityRolls | function | C_Wildcard.RepurchaseAbilityRolls(...) |  |
| RepurchaseRolls | function | C_Wildcard.RepurchaseRolls(arg1, arg2) | C_Wildcard.RepurchaseRolls(self.scrollClaimAmount, self.UseGold:GetBoolValue()) |
| RepurchaseTalentRolls | function | C_Wildcard.RepurchaseTalentRolls(arg1, arg2) | C_Wildcard.RepurchaseTalentRolls(self.talentScrollClaimAmount, self.UseGold:GetBoolValue()) |
| ResetAbilities | function | C_Wildcard.ResetAbilities() | C_Wildcard.ResetAbilities() |
| RollAbilities | function | C_Wildcard.RollAbilities() | C_Wildcard.RollAbilities() -- roll new abilities only if we rolled everything in memory |
| SetFilteredDesiredEntries | function | C_Wildcard.SetFilteredDesiredEntries(arg1, arg2) | C_Wildcard.SetFilteredDesiredEntries(text, self.DesiredFilter:GetFilter()) |
| SetFilteredUndesiredEntries | function | C_Wildcard.SetFilteredUndesiredEntries(arg1, arg2) | C_Wildcard.SetFilteredUndesiredEntries(text, self.UndesiredFilter:GetFilter()) |
| StartRapidRolling | function | C_Wildcard.StartRapidRolling(arg1) | C_Wildcard.StartRapidRolling(false) |
| UnlearnAbility | function | C_Wildcard.UnlearnAbility(arg1) | dprint("C_Wildcard.UnlearnAbility("..internalID..")") |
| WillRollStartingAbilities | function | C_Wildcard.WillRollStartingAbilities() | if (C_Wildcard.WillRollStartingAbilities() or (C_CharacterAdvancement.GetLearnedAE() <= 8)) then |
