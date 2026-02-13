# C_PVP



**Members:** 19  •  **Functions:** 18  •  **Interface calls:** 128 (across up to 4 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_PVP.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| InHighRisk | boolean | C_PVP.InHighRisk |  |
| CanQueueCasual | function | C_PVP:CanQueueCasual() | { name = "AscensionPVPFrameCasualFrame", label = "QUICK_MATCH", icon = "Interface\\Icons\\achieve... |
| CanQueueInHighRisk | function | C_PVP:CanQueueInHighRisk() | if not C_PVP:CanQueueInHighRisk() then |
| CanQueueRated | function | C_PVP:CanQueueRated() | { name = "AscensionPVPFrameRatedFrame", label = "RATED", label2 = "[ARENA_POINTS]", icon = "Inter... |
| GetBattlegroundFaction | function | C_PVP:GetBattlegroundFaction() | self:StartTimer(seconds / 1000, C_PVP:GetBattlegroundFaction()) |
| GetCurrentBestRating | function | C_PVP:GetCurrentBestRating() | function C_PVP:GetCurrentBestRating() |
| GetEliteTierInfo | function | C_PVP:GetEliteTierInfo() | local eliteName, eliteMinRating, elitePrevTier, eliteIcon = C_PVP:GetEliteTierInfo() |
| GetHolidayBGInfo | function | C_PVP:GetHolidayBGInfo() | local holidays = C_PVP:GetHolidayBGInfo() |
| GetHonorRank | function | C_PVP:GetHonorRank(arg1) | local level, currentIcon, currentGloryReq, nextIcon, nextGloryReq = C_PVP:GetHonorRank(glory) |
| GetIsCurrentMapHighRisk | function | C_PVP:GetIsCurrentMapHighRisk() | local isHighRisk = C_PVP:GetIsCurrentMapHighRisk() |
| GetMapIsHighRisk | function | C_PVP:GetMapIsHighRisk(arg1) | local isHighRisk = C_PVP:GetMapIsHighRisk(GetMapInfo()) |
| GetMaxGearDropAmount | function | C_PVP:GetMaxGearDropAmount() | function C_PVP:GetMaxGearDropAmount() |
| GetPVPTierInfo | function | C_PVP:GetPVPTierInfo(arg1) | ratingName, _, _, _, _, ratingIcon = C_PVP:GetPVPTierInfo(team.rating) |
| GetRandomBGInfo | function | C_PVP:GetRandomBGInfo() | local bgName, canQueue, battleGroundIndex, battleGroundID, hasWon, winHonorAmount, winArenaAmount... |
| GetRandomBrawlBGInfo | function | C_PVP:GetRandomBrawlBGInfo() | local bgName, canQueue, battleGroundIndex, battleGroundID, hasWon, winHonorAmount, winArenaAmount... |
| GetRequiredItemLevelForEvents | function | C_PVP:GetRequiredItemLevelForEvents() | function() return format(EVENT_HR_MATERIALS_HERB_DESC, "Dreadmaul Rock", C_PVP:GetRequiredItemLev... |
| IsLegacyWarmode | function | C_PVP:IsLegacyWarmode() | ﻿if not C_PVP:IsLegacyWarmode() then |
| PLAYER_ENTERING_WORLD | function | C_PVP:PLAYER_ENTERING_WORLD() | function C_PVP:PLAYER_ENTERING_WORLD() |
| ZONE_CHANGED_NEW_AREA | function | C_PVP:ZONE_CHANGED_NEW_AREA() | function C_PVP:ZONE_CHANGED_NEW_AREA() |
