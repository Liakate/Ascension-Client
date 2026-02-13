# C_Manastorm



**Members:** 21  •  **Functions:** 21  •  **Interface calls:** 44 (across up to 6 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanEnter | function | C_Manastorm.CanEnter(arg1) | local canEnter, reasons, ineligilbeUnits = C_Manastorm.CanEnter(self.selectedLevel) |
| CanLeave | function | C_Manastorm.CanLeave() | local canLeave, reasons = C_Manastorm.CanLeave() |
| CanSetLoadoutSpellAtIndex | function | C_Manastorm.CanSetLoadoutSpellAtIndex(...) |  |
| Enter | function | C_Manastorm.Enter(arg1) | StaticPopup_GenericConfirm(MANASTORM_SPELL_LOADOUT_MISSING, nil, nil, YES, CANCEL, GenerateClosur... |
| GetActiveLevel | function | C_Manastorm.GetActiveLevel() | local currentLevel = C_Manastorm.GetActiveLevel() |
| GetActiveManastormID | function | C_Manastorm.GetActiveManastormID() | local manastormID = C_Manastorm.GetActiveManastormID() |
| GetActiveManastormType | function | C_Manastorm.GetActiveManastormType() | local groupType = C_Manastorm.GetActiveManastormType() |
| GetAvailableLoadoutSpells | function | C_Manastorm.GetAvailableLoadoutSpells() | local availableSpells, unavailableSpells = C_Manastorm.GetAvailableLoadoutSpells() |
| GetBoss | function | C_Manastorm.GetBoss() | self:SetGetEncounterFunction(C_Manastorm.GetBoss) |
| GetEnterableLevels | function | C_Manastorm.GetEnterableLevels() | self.levels = C_Manastorm.GetEnterableLevels() |
| GetExperienceModifier | function | C_Manastorm.GetExperienceModifier(arg1, arg2) | local expModifier = C_Manastorm.GetExperienceModifier(self.parent.maxLevelInGroup and 2 or 0, level) |
| GetLoadoutSpellAtIndex | function | C_Manastorm.GetLoadoutSpellAtIndex(arg1) | local spell = C_Manastorm.GetLoadoutSpellAtIndex(index) |
| GetManastormCacheInfo | function | C_Manastorm.GetManastormCacheInfo() | local numCaches, additionalCacheChance = C_Manastorm.GetManastormCacheInfo() |
| GetMaxCompletedLevels | function | C_Manastorm.GetMaxCompletedLevels(arg1) | local _, solo, duo, trio, group = C_Manastorm.GetMaxCompletedLevels("player") |
| GetNumLoadoutSlots | function | C_Manastorm.GetNumLoadoutSlots() | local numSlots = C_Manastorm.GetNumLoadoutSlots() |
| GetRewardModifier | function | C_Manastorm.GetRewardModifier(arg1) | local endReward, encounterReward, groupEndReward, groupEncounterReward = C_Manastorm.GetRewardMod... |
| GetStageBonusExperience | function | C_Manastorm.GetStageBonusExperience() | local expModifier = C_Manastorm.GetStageBonusExperience() |
| IsInManastorm | function | C_Manastorm.IsInManastorm() | if not C_Manastorm.IsInManastorm() then |
| Leave | function | C_Manastorm.Leave() |  |
| SetLoadoutSpellAtIndex | function | C_Manastorm.SetLoadoutSpellAtIndex(arg1, arg2) | C_Manastorm.SetLoadoutSpellAtIndex(self.button:GetID(), button.spell.spellID) |
| ShowObjectiveIcon | function | C_Manastorm.ShowObjectiveIcon(...) |  |
