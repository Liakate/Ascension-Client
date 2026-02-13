# C_Quest



**Members:** 31  •  **Functions:** 21  •  **Interface calls:** 65 (across up to 7 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_Quest.lua` line 3




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| isQuerying | boolean | C_Quest.isQuerying |  |
| ASCENSION_CUSTOM_QUEST_REWARDED | function | C_Quest:ASCENSION_CUSTOM_QUEST_REWARDED(arg1) | function C_Quest:ASCENSION_CUSTOM_QUEST_REWARDED(id) |
| AddAutoQuestPopUp | function | C_Quest:AddAutoQuestPopUp(arg1) | C_Quest:AddAutoQuestPopUp(Enum.Quests.PTAscension.RankUpYourSpells) |
| ExpandAllQuestHeaders | function | C_Quest:ExpandAllQuestHeaders() | function C_Quest:ExpandAllQuestHeaders() |
| GetCurrentQuests | function | C_Quest:GetCurrentQuests(arg1) | function C_Quest:GetCurrentQuests(forceTrack) |
| GetPortraitData | function | C_Quest:GetPortraitData() | function C_Quest:GetPortraitData(questID) |
| GetQuestID | function | C_Quest:GetQuestID(arg1) | function C_Quest:GetQuestID(index) |
| GetQuestIndexByID | function | C_Quest:GetQuestIndexByID(arg1) | return C_Quest:GetQuestIndexByID(self.questID) |
| GetQuestNameByID | function | C_Quest:GetQuestNameByID(arg1) | local name = C_Quest:GetQuestNameByID(questID) |
| GetTitleByID | function | C_Quest.GetTitleByID(arg1) | function C_Quest.GetTitleByID(questID) |
| HasOrHasDoneQuest | function | C_Quest:HasOrHasDoneQuest(arg1) | return C_Quest:HasOrHasDoneQuest(self.questID) |
| IsFelforgedChallenge | function | C_Quest:IsFelforgedChallenge(arg1) | function C_Quest:IsFelforgedChallenge(questId) |
| IsOnQuestID | function | C_Quest:IsOnQuestID(arg1) | if (C_Quest:IsOnQuestID(quest)) then |
| IsQuerying | function | C_Quest:IsQuerying() | function C_Quest:IsQuerying() |
| IsQuestCachedByID | function | C_Quest:IsQuestCachedByID(arg1) | return C_Quest:IsQuestCachedByID(self.questID) |
| IsQuestComplete | function | C_Quest:IsQuestComplete(arg1) | --condition = function() return (C_Quest:IsQuestComplete(7) or not(C_Quest:IsOnQuestID(7))) end, |
| IsQuestTurnedIn | function | C_Quest:IsQuestTurnedIn(arg1) | if not(C_Quest:IsQuestTurnedIn(questID)) then |
| PLAYER_LOGIN | function | C_Quest:PLAYER_LOGIN() | function C_Quest:PLAYER_LOGIN() |
| QUEST_ACCEPTED | function | C_Quest:QUEST_ACCEPTED(arg1) | function C_Quest:QUEST_ACCEPTED(index) |
| QUEST_LOG_UPDATE | function | C_Quest:QUEST_LOG_UPDATE() | function C_Quest:QUEST_LOG_UPDATE() |
| QUEST_QUERY_COMPLETE | function | C_Quest:QUEST_QUERY_COMPLETE() | function C_Quest:QUEST_QUERY_COMPLETE() |
| SendPathToAscensionEvent | function | C_Quest:SendPathToAscensionEvent(arg1) | C_Quest:SendPathToAscensionEvent("ACTION_OPEN_HERO_ARCHITECT") |
| felforgedChallenges.<truncated> | note | C_Quest.felforgedChallenges.<truncated> |  |
| lastQuery | number | C_Quest.lastQuery |  |
| PortraitData | table | C_Quest.PortraitData | C_Quest.PortraitData = { -- TODO: Support for multiple creatures |
| activeQuests | table | C_Quest.activeQuests |  |
| completedQuests | table | C_Quest.completedQuests |  |
| felforgedChallenges | table | C_Quest.felforgedChallenges | C_Quest.felforgedChallenges = { |
| queryIds | table | C_Quest.queryIds |  |
| titles | table | C_Quest.titles | C_Quest.titles = { |
| turnedInQuests | table | C_Quest.turnedInQuests |  |
