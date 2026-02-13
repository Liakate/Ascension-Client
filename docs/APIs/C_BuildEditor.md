# C_BuildEditor



**Members:** 63  •  **Functions:** 63  •  **Interface calls:** 153 (across up to 8 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| AddArmorType | function | C_BuildEditor.AddArmorType(arg1) | C_BuildEditor.AddArmorType(armor) |
| AddRandomEnchant | function | C_BuildEditor.AddRandomEnchant(arg1) | C_BuildEditor.AddRandomEnchant(enchant) |
| AddSpell | function | C_BuildEditor.AddSpell(arg1) | C_BuildEditor.AddSpell(spell) |
| AddWeaponType | function | C_BuildEditor.AddWeaponType(arg1) | C_BuildEditor.AddWeaponType(weapon) |
| CanAddArmorType | function | C_BuildEditor.CanAddArmorType(arg1) | if C_BuildEditor.CanAddArmorType(armor) then |
| CanAddRandomEnchant | function | C_BuildEditor.CanAddRandomEnchant(...) |  |
| CanAddSpell | function | C_BuildEditor.CanAddSpell(arg1) | local canLearn, reason = C_BuildEditor.CanAddSpell(BuildCreatorUtil.CreateSpellInfo(self.spellID,... |
| CanAddWeaponType | function | C_BuildEditor.CanAddWeaponType(arg1) | if C_BuildEditor.CanAddWeaponType(weapon) then |
| CanPublishBuild | function | C_BuildEditor.CanPublishBuild() | local canPublish, failReasons = C_BuildEditor.CanPublishBuild() |
| CanRemoveArmorType | function | C_BuildEditor.CanRemoveArmorType(...) |  |
| CanRemoveRandomEnchant | function | C_BuildEditor.CanRemoveRandomEnchant(...) |  |
| CanRemoveSpell | function | C_BuildEditor.CanRemoveSpell(arg1) | canUnlearn, reason = C_BuildEditor.CanRemoveSpell(BuildCreatorUtil.CreateSpellInfo(self.spellID, ... |
| CanRemoveWeaponType | function | C_BuildEditor.CanRemoveWeaponType(...) |  |
| CanSetArmorTypeComment | function | C_BuildEditor.CanSetArmorTypeComment(...) |  |
| CanSetEnchantFlags | function | C_BuildEditor.CanSetEnchantFlags(arg1) | info.enabled = C_BuildEditor.CanSetEnchantFlags(spellID) |
| CanSetEnchantLevel | function | C_BuildEditor.CanSetEnchantLevel(...) |  |
| CanSetIsCoreAbility | function | C_BuildEditor.CanSetIsCoreAbility(arg1, arg2) | info.disabled = not C_BuildEditor.CanSetIsCoreAbility(spellID, not buildSpell.IsCoreAbility) |
| CanSetIsEmpoweringAbility | function | C_BuildEditor.CanSetIsEmpoweringAbility(arg1, arg2) | info.disabled = not C_BuildEditor.CanSetIsEmpoweringAbility(spellID, not buildSpell.IsEmpoweringA... |
| CanSetIsOptimalAbility | function | C_BuildEditor.CanSetIsOptimalAbility(arg1, arg2) | info.disabled = not C_BuildEditor.CanSetIsOptimalAbility(spellID, not buildSpell.IsOptimalAbility) |
| CanSetIsSynergisticAbility | function | C_BuildEditor.CanSetIsSynergisticAbility(arg1, arg2) | info.disabled = not C_BuildEditor.CanSetIsSynergisticAbility(spellID, not buildSpell.IsSynergisti... |
| CanSetRandomEnchantComment | function | C_BuildEditor.CanSetRandomEnchantComment(...) |  |
| CanSetRandomEnchantStacks | function | C_BuildEditor.CanSetRandomEnchantStacks(...) |  |
| CanSetSpellComment | function | C_BuildEditor.CanSetSpellComment(...) |  |
| CanSetSpellFlags | function | C_BuildEditor.CanSetSpellFlags(arg1) | info.enabled = C_BuildEditor.CanSetSpellFlags(spellID) |
| CanSetSpellLevel | function | C_BuildEditor.CanSetSpellLevel(arg1, arg2) | elseif spell and C_BuildEditor.CanSetSpellLevel(spell.Spell, level) then |
| CanSetWeaponTypeComment | function | C_BuildEditor.CanSetWeaponTypeComment(...) |  |
| DiscardPendingBuild | function | C_BuildEditor.DiscardPendingBuild() | C_BuildEditor.DiscardPendingBuild() |
| DoesBuildHaveEnchant | function | C_BuildEditor.DoesBuildHaveEnchant(arg1) | if C_BuildEditor.DoesBuildHaveEnchant(self.spellID) then |
| DoesBuildHaveSpellID | function | C_BuildEditor.DoesBuildHaveSpellID(arg1) | if nextSpellID and not C_BuildEditor.DoesBuildHaveSpellID(nextSpellID) then |
| EditBuild | function | C_BuildEditor.EditBuild(arg1) | C_BuildEditor.EditBuild(build.ID) |
| ExportPendingBuild | function | C_BuildEditor.ExportPendingBuild(...) |  |
| GetEssenceForLevel | function | C_BuildEditor.GetEssenceForLevel(arg1) | local _, aeRemaining, _, teRemaining = C_BuildEditor.GetEssenceForLevel(GetMaxLevel()) |
| GetFilteredEntryAtIndex | function | C_BuildEditor.GetFilteredEntryAtIndex(arg1) | self.entry = C_BuildEditor.GetFilteredEntryAtIndex(self.index) |
| GetNumFilteredEntries | function | C_BuildEditor.GetNumFilteredEntries(...) | self.SideBar.SpellList:SetGetNumResultsFunction(C_BuildEditor.GetNumFilteredEntries) |
| GetPendingBuild | function | C_BuildEditor.GetPendingBuild() | local build = C_BuildEditor.GetPendingBuild() |
| GetQualityInfo | function | C_BuildEditor.GetQualityInfo(...) |  |
| GetQualityInfoForLevel | function | C_BuildEditor.GetQualityInfoForLevel() | amount = select(self.quality, C_BuildEditor.GetQualityInfoForLevel()) or 0 |
| GetSpellByID | function | C_BuildEditor.GetSpellByID(arg1) | local spellInfo = C_BuildEditor.GetSpellByID(self.spellID) |
| ImportBuild | function | C_BuildEditor.ImportBuild(arg1) |  |
| ImportCurrentBuild | function | C_BuildEditor.ImportCurrentBuild(...) |  |
| PublishBuild | function | C_BuildEditor.PublishBuild() | local publishSent, failReason = C_BuildEditor.PublishBuild() |
| RemoveArmorType | function | C_BuildEditor.RemoveArmorType(arg1) | C_BuildEditor.RemoveArmorType(self.info.Type) |
| RemoveRandomEnchant | function | C_BuildEditor.RemoveRandomEnchant(arg1) | C_BuildEditor.RemoveRandomEnchant(self.spellID) |
| RemoveSpell | function | C_BuildEditor.RemoveSpell(arg1) | C_BuildEditor.RemoveSpell(self.spellID) |
| RemoveWeaponType | function | C_BuildEditor.RemoveWeaponType(arg1) | C_BuildEditor.RemoveWeaponType(self.info.Type) |
| SetCategory | function | C_BuildEditor.SetCategory(arg1) | C_BuildEditor.SetCategory(deserializedBuild.Category) |
| SetComment | function | C_BuildEditor.SetComment(arg1, arg2) |  |
| SetDescription | function | C_BuildEditor.SetDescription(arg1) | C_BuildEditor.SetDescription(deserializedBuild.Description) |
| SetDifficultyRating | function | C_BuildEditor.SetDifficultyRating(arg1) | C_BuildEditor.SetDifficultyRating(deserializedBuild.DifficultyRating) |
| SetEnchantFlags | function | C_BuildEditor.SetEnchantFlags(arg1, arg2) | C_BuildEditor.SetEnchantFlags(spellID, bit.bxor(buildSpell.Flags, Enum.BuildSpellFlags.NotifyOnLe... |
| SetEnchantLevel | function | C_BuildEditor.SetEnchantLevel(arg1, arg2) |  |
| SetEnchantStacks | function | C_BuildEditor.SetEnchantStacks(arg1, arg2) | C_BuildEditor.SetEnchantStacks(self.spellID, self.info.Stacks + 1) |
| SetFilteredEntries | function | C_BuildEditor.SetFilteredEntries(arg1, arg2) | C_BuildEditor.SetFilteredEntries("", OnlyKnownFilter) |
| SetIcon | function | C_BuildEditor.SetIcon(arg1) | C_BuildEditor.SetIcon(deserializedBuild.Icon) |
| SetIsCoreAbility | function | C_BuildEditor.SetIsCoreAbility(arg1, arg2) | C_BuildEditor.SetIsCoreAbility(spellID, not buildSpell.IsCoreAbility) |
| SetIsEmpoweringAbility | function | C_BuildEditor.SetIsEmpoweringAbility(arg1, arg2) | C_BuildEditor.SetIsEmpoweringAbility(self.spellID, not self.info.IsEmpoweringAbility) |
| SetIsOptimalAbility | function | C_BuildEditor.SetIsOptimalAbility(arg1, arg2) | C_BuildEditor.SetIsOptimalAbility(self.spellID, not self.info.IsOptimalAbility) |
| SetIsSynergisticAbility | function | C_BuildEditor.SetIsSynergisticAbility(arg1, arg2) | C_BuildEditor.SetIsSynergisticAbility(self.spellID, not self.info.IsSynergisticAbility) |
| SetName | function | C_BuildEditor.SetName(arg1) | C_BuildEditor.SetName(deserializedBuild.Name) |
| SetPrimaryStat | function | C_BuildEditor.SetPrimaryStat(arg1) | C_BuildEditor.SetPrimaryStat(deserializedBuild.PrimaryStat) |
| SetRoles | function | C_BuildEditor.SetRoles(arg1) | C_BuildEditor.SetRoles(deserializedBuild.Roles) |
| SetSpellFlags | function | C_BuildEditor.SetSpellFlags(arg1, arg2) | C_BuildEditor.SetSpellFlags(spellID, bit.bxor(buildSpell.Flags, Enum.BuildSpellFlags.NotifyOnLearn)) |
| SetSpellLevel | function | C_BuildEditor.SetSpellLevel(arg1, arg2) | C_BuildEditor.SetSpellLevel(spell.Spell, 60) |



## Notes


- 2 member(s) had a runtime probe marked `ok` in the scan data.
