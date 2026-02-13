# C_Player



**Members:** 44  •  **Functions:** 43  •  **Interface calls:** 341 (across up to 33 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_Player.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetAverageItemLevel | function | C_Player:GetAverageItemLevel() | local averageItemLevel = C_Player:GetAverageItemLevel() |
| GetClass | function | C_Player:GetClass() | PortraitFrame_SetClassIcon(self, C_Player:GetClass()) |
| GetCurrentCompanion | function | C_Player:GetCurrentCompanion() | local _, companionName = C_Player:GetCurrentCompanion() |
| GetCurrentMapContinentZone | function | C_Player:GetCurrentMapContinentZone() | function C_Player:GetCurrentMapContinentZone() |
| GetCurrentMapExpansion | function | C_Player:GetCurrentMapExpansion() | function C_Player:GetCurrentMapExpansion() |
| GetCurrentMapInfo | function | C_Player:GetCurrentMapInfo() | function C_Player:GetCurrentMapInfo() |
| GetFaction | function | C_Player:GetFaction() | creature = C_Player:GetFaction() == "Horde" and 80190 or 80189, |
| GetLevel | function | C_Player:GetLevel() | if C_Player:GetLevel() == maxLevel or C_Player:IsGM() or isWildCard then |
| GetName | function | C_Player:GetName() | if C_Player:GetName() ~= "Unknown" then |
| GetPvEPower | function | C_Player:GetPvEPower() | local PVEPower = C_Player:GetPvEPower() |
| GetPvPPower | function | C_Player:GetPvPPower() | local pvpPower = C_Player:GetPvPPower() |
| GetRace | function | C_Player:GetRace() | function C_Player:GetRace() |
| GetRuleset | function | C_Player:GetRuleset() | self.selected = ruleset or C_Player:GetRuleset() |
| GetRulesetCooldown | function | C_Player:GetRulesetCooldown() | local cooldown = C_Player:GetRulesetCooldown() |
| GetSex | function | C_Player:GetSex() | function C_Player:GetSex() |
| HasAura | function | C_Player:HasAura(arg1) | if C_Player:HasAura(801647) then |
| HasBuff | function | C_Player:HasBuff(arg1) | function C_Player:HasBuff(buffID) |
| HasDebuff | function | C_Player:HasDebuff(arg1) | function C_Player:HasDebuff(debuffID) |
| HasRuleset | function | C_Player:HasRuleset() | function C_Player:HasRuleset() |
| InCombat | function | C_Player:InCombat() | if C_Player:InCombat() then |
| IsCustomClass | function | C_Player:IsCustomClass() | elseif C_Player:IsCustomClass() then |
| IsDead | function | C_Player:IsDead() | return C_Manastorm.IsInManastorm() and C_Manastorm.GetActiveManastormType() == "SOLO" and C_Playe... |
| IsDefaultClass | function | C_Player:IsDefaultClass() | elseif C_Player:IsDefaultClass() then |
| IsEffectivelyTank | function | C_Player:IsEffectivelyTank() | return assignedRole == "TANK" or C_Player:IsEffectivelyTank() |
| IsGM | function | C_Player:IsGM() | if IsControlKeyDown() and C_Player:IsGM() and not UnitExists("target") and not C_AppearanceCollec... |
| IsGroupLeader | function | C_Player:IsGroupLeader() | function C_Player:IsGroupLeader() |
| IsHero | function | C_Player:IsHero() | if C_Player:IsHero() then |
| IsHighRisk | function | C_Player:IsHighRisk() | if not C_Player:IsHighRisk() then |
| IsImmune | function | C_Player:IsImmune() | if C_Player:IsImmune() then |
| IsInGroup | function | C_Player:IsInGroup() | function C_Player:IsInGroup() |
| IsInRaid | function | C_Player:IsInRaid() | function C_Player:IsInRaid() |
| IsMaxLevel | function | C_Player:IsMaxLevel() | if C_Player:IsMaxLevel() and self.build.EndGameIDPVE and self.build.EndGameIDPVE:len() > 0 then |
| IsNoRiskPvE | function | C_Player:IsNoRiskPvE() | function C_Player:IsNoRiskPvE() |
| IsNoRiskPvP | function | C_Player:IsNoRiskPvP() | if C_Player:IsNoRiskPvP() then |
| IsNoRiskPvPOrHigher | function | C_Player:IsNoRiskPvPOrHigher() | function C_Player:IsNoRiskPvPOrHigher() |
| IsPrestiged | function | C_Player:IsPrestiged() | local isPrestiged = C_Player:IsPrestiged() |
| IsTitansGrip | function | C_Player:IsTitansGrip() | function C_Player:IsTitansGrip() |
| IsWorldPVP | function | C_Player:IsWorldPVP() | function C_Player:IsWorldPVP() |
| PLAYER_ENTERING_WORLD | function | C_Player:PLAYER_ENTERING_WORLD() | function C_Player:PLAYER_ENTERING_WORLD() |
| PLAYER_LEVEL_UP | function | C_Player:PLAYER_LEVEL_UP(arg1) | function C_Player:PLAYER_LEVEL_UP(level) |
| SetRuleset | function | C_Player:SetRuleset(arg1) | function C_Player:SetRuleset(ruleset) |
| UNIT_PET | function | C_Player:UNIT_PET() | function C_Player:UNIT_PET() |
| UpdatePvEPower | function | C_Player:UpdatePvEPower() | function C_Player:UpdatePvEPower() |
| currentLevel | number | C_Player.currentLevel |  |
