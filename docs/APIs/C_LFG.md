# C_LFG



**Members:** 12  •  **Functions:** 7  •  **Interface calls:** 19 (across up to 3 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_LFG.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanUseGroupFinder | function | C_LFG:CanUseGroupFinder() | function C_LFG:CanUseGroupFinder() |
| CanUseLFD | function | C_LFG:CanUseLFD() | { name = "AscensionPVEFrame", check = function() return C_LFG:CanUseLFD() or C_LFG:CanUseManastor... |
| CanUseManastorm | function | C_LFG:CanUseManastorm() | { name = "AscensionPVEFrame", check = function() return C_LFG:CanUseLFD() or C_LFG:CanUseManastor... |
| CanUseRandomLFD | function | C_LFG:CanUseRandomLFD(arg1) | local canUse, reason = C_LFG:CanUseRandomLFD(id) |
| GetLFGDungeonRewards | function | C_LFG:GetLFGDungeonRewards(arg1) | local doneToday, moneyBase, moneyVar, experienceBase, experienceVar, numRewards, rewards = C_LFG:... |
| IsRandomDungeonDisplayable | function | C_LFG:IsRandomDungeonDisplayable(arg1) | if C_LFG:IsRandomDungeonDisplayable(id) then |
| IsScalingDungeon | function | C_LFG:IsScalingDungeon(arg1) | if C_LFG:IsScalingDungeon(dungeonID) then |
| RequiredExpansion | table | C_LFG.RequiredExpansion |  |
| RequiredRandomItemLevel | table | C_LFG.RequiredRandomItemLevel |  |
| RequiredRandomPVEPower | table | C_LFG.RequiredRandomPVEPower |  |
| RequiresGameEvent | table | C_LFG.RequiresGameEvent | for dungeonID, events in pairs(C_LFG.RequiresGameEvent) do |
| ScalingDungeons | table | C_LFG.ScalingDungeons |  |
