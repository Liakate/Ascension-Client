# C_Tutorial



**Members:** 40  •  **Functions:** 40  •  **Interface calls:** 70 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| AddMentorSpecialization | function | C_Tutorial.AddMentorSpecialization(arg1) |  |
| AnyUnclaimedRewards | function | C_Tutorial.AnyUnclaimedRewards() |  |
| CanCollectReward | function | C_Tutorial.CanCollectReward(arg1) | if C_Tutorial.CanCollectReward(self.tutorialID) then |
| CanToggleMentorStatus | function | C_Tutorial.CanToggleMentorStatus(arg1) | local canChangeMentor, reason = C_Tutorial.CanToggleMentorStatus(not isMentor) |
| CollectReward | function | C_Tutorial.CollectReward(arg1) | C_Tutorial.CollectReward(self.tutorialID) |
| DebugTutorialAppliccability | function | C_Tutorial.DebugTutorialAppliccability(...) |  |
| GetAvailableMentorAtIndex | function | C_Tutorial.GetAvailableMentorAtIndex(arg1) | local name, level, class, specializations, race, sex = C_Tutorial.GetAvailableMentorAtIndex(self.... |
| GetCategories | function | C_Tutorial.GetCategories() | local categories = C_Tutorial.GetCategories() |
| GetCategoryInfo | function | C_Tutorial.GetCategoryInfo(arg1) | local name = C_Tutorial.GetCategoryInfo(categoryID) |
| GetCategoryProgress | function | C_Tutorial.GetCategoryProgress(arg1) | local _, numRewarded, total = C_Tutorial.GetCategoryProgress(tab.categoryID) |
| GetIndexByKeywordID | function | C_Tutorial.GetIndexByKeywordID(arg1) | local keywordIndex = C_Tutorial.GetIndexByKeywordID and C_Tutorial.GetIndexByKeywordID(keywordID)... |
| GetKeywordAtIndex | function | C_Tutorial.GetKeywordAtIndex(arg1) | local keyword = C_Tutorial.GetKeywordAtIndex(self.index) |
| GetKeywordID | function | C_Tutorial.GetKeywordID(arg1) | keyword = C_Tutorial.GetKeywordID(keyword) |
| GetKeywordInfo | function | C_Tutorial.GetKeywordInfo(arg1) | local keywordName, keywordTooltip = C_Tutorial.GetKeywordInfo(keyword) |
| GetMentorSpecializationActive | function | C_Tutorial.GetMentorSpecializationActive(arg1) | button:SetChecked(C_Tutorial.GetMentorSpecializationActive(specID)) |
| GetMentorSpecializationInfo | function | C_Tutorial.GetMentorSpecializationInfo(arg1) | name, atlas = C_Tutorial.GetMentorSpecializationInfo(specID) |
| GetMentorSpecializations | function | C_Tutorial.GetMentorSpecializations() | local specializations = C_Tutorial.GetMentorSpecializations() |
| GetNumAvailableMentors | function | C_Tutorial.GetNumAvailableMentors(...) | self.AvailableMentors:SetGetNumResultsFunction(C_Tutorial.GetNumAvailableMentors) |
| GetNumKeywords | function | C_Tutorial.GetNumKeywords(...) | self.Keywords:SetGetNumResultsFunction(C_Tutorial.GetNumKeywords) |
| GetNumTutorials | function | C_Tutorial.GetNumTutorials() | self.Objectives:SetGetNumResultsFunction(C_Tutorial.GetNumTutorials) |
| GetObjectiveInfo | function | C_Tutorial.GetObjectiveInfo(arg1) | local objectiveName = C_Tutorial.GetObjectiveInfo(objectiveID) |
| GetObjectives | function | C_Tutorial.GetObjectives(arg1) | for _, objectiveID in ipairs(C_Tutorial.GetObjectives(self.tutorialID)) do |
| GetRewards | function | C_Tutorial.GetRewards(arg1) | local rewards = C_Tutorial.GetRewards(self.tutorialID) |
| GetTutorialAtIndex | function | C_Tutorial.GetTutorialAtIndex(arg1) | self.tutorialID, self.name, self.questID, self.suggestedLevel, self.icon, self.achievementID, sel... |
| GetTutorialByID | function | C_Tutorial.GetTutorialByID(arg1) | local _, _, _, questID = C_Tutorial.GetTutorialByID(self.tutorialID) |
| GetTutorialDisplay | function | C_Tutorial.GetTutorialDisplay(arg1) | self.name, self.description, self.questID = C_Tutorial.GetTutorialDisplay(tutorialID) |
| GetTutorialsRequiredForMentorStatus | function | C_Tutorial.GetTutorialsRequiredForMentorStatus() | local incompleteTutorials = C_Tutorial.GetTutorialsRequiredForMentorStatus() |
| IsCategoryEnabled | function | C_Tutorial.IsCategoryEnabled(arg1) | local tabEnabled = C_Tutorial.IsCategoryEnabled(categoryID) |
| IsMentorStatusActive | function | C_Tutorial.IsMentorStatusActive() | local isMentor = C_Tutorial.IsMentorStatusActive() |
| IsRewardCollected | function | C_Tutorial.IsRewardCollected(arg1) | if C_Tutorial.IsRewardCollected(self.tutorialID) then |
| IsTutorialAvailable | function | C_Tutorial.IsTutorialAvailable(arg1) | self.isAvailable, self.notAvailableReason = C_Tutorial.IsTutorialAvailable(self.tutorialID) |
| IsTutorialComplete | function | C_Tutorial.IsTutorialComplete(arg1) | if C_Tutorial.IsTutorialComplete(self.tutorialID) then |
| IsTutorialRequiredForMentorStatus | function | C_Tutorial.IsTutorialRequiredForMentorStatus(arg1) | self.isMentorTutorial = C_Tutorial.IsTutorialRequiredForMentorStatus(self.tutorialID) |
| QueryActiveMentors | function | C_Tutorial.QueryActiveMentors() | C_Tutorial.QueryActiveMentors() |
| RemoveMentorSpecialization | function | C_Tutorial.RemoveMentorSpecialization(arg1) |  |
| SetAvailableMentorFilter | function | C_Tutorial.SetAvailableMentorFilter(arg1, arg2) | C_Tutorial.SetAvailableMentorFilter(self.SearchBox:GetText(), filter) |
| SetKeywordFilter | function | C_Tutorial.SetKeywordFilter(arg1) | C_Tutorial.SetKeywordFilter(searchText) |
| SetTutorialFilter | function | C_Tutorial.SetTutorialFilter(arg1, arg2) | C_Tutorial.SetTutorialFilter(self.selectedCategoryID, searchText) |
| StartQuest | function | C_Tutorial.StartQuest(arg1) | C_Tutorial.StartQuest(self.questID) |
| ToggleMentorStatus | function | C_Tutorial.ToggleMentorStatus(arg1) | C_Tutorial.ToggleMentorStatus(not C_Tutorial.IsMentorStatusActive()) |



## Notes


- 2 member(s) had a runtime probe marked `ok` in the scan data.
