# C_Challenge



**Members:** 35  •  **Functions:** 35  •  **Interface calls:** 54 (across up to 7 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanActivateChallenge | function | C_Challenge.CanActivateChallenge(arg1) | return C_Challenge.CanActivateChallenge(self.challenge.ID, self:GetSelectedLevel()) |
| CanDeactivateChallenge | function | C_Challenge.CanDeactivateChallenge(arg1) | return C_Challenge.CanDeactivateChallenge(self.challenge.ID) |
| CanResurrect | function | C_Challenge.CanResurrect() | if not C_Challenge.CanResurrect() and GetItemCount(ItemData.IRON_SOUL) == 0 then |
| GetActiveChallenges | function | C_Challenge.GetActiveChallenges(...) |  |
| GetAllChallenges | function | C_Challenge.GetAllChallenges(...) |  |
| GetAllTrials | function | C_Challenge.GetAllTrials(...) |  |
| GetBrokenChallengeRules | function | C_Challenge.GetBrokenChallengeRules(...) |  |
| GetChallengeAtIndex | function | C_Challenge.GetChallengeAtIndex(arg1, arg2) | return C_Challenge.GetChallengeAtIndex(index, isExpanded) |
| GetChallengeCompletion | function | C_Challenge.GetChallengeCompletion(arg1, arg2, arg3) | if not C_Challenge.GetChallengeCompletion(self.challenge.ID, self:GetSelectedLevel(), 1) then |
| GetChallengeCompletions | function | C_Challenge.GetChallengeCompletions(arg1, arg2, arg3) | entries = C_Challenge.GetChallengeCompletions(challengeID, level, 50) |
| GetChallengeCriteriaInfo | function | C_Challenge.GetChallengeCriteriaInfo(...) |  |
| GetChallengeCriterias | function | C_Challenge.GetChallengeCriterias(...) |  |
| GetChallengeFailure | function | C_Challenge.GetChallengeFailure(...) |  |
| GetChallengeFailures | function | C_Challenge.GetChallengeFailures(arg1, arg2) |  |
| GetChallengeIDByIndex | function | C_Challenge.GetChallengeIDByIndex(arg1) | return C_Challenge.GetChallengeIDByIndex(index) |
| GetChallengeInfo | function | C_Challenge.GetChallengeInfo(arg1) | local challengeName = C_Challenge.GetChallengeInfo(value1).Name |
| GetChallengeInfoByLevel | function | C_Challenge.GetChallengeInfoByLevel(arg1, arg2) | local challenge = C_Challenge.GetChallengeInfoByLevel(challengeID, level) |
| GetChallengeLevels | function | C_Challenge.GetChallengeLevels(arg1) | return C_Challenge.GetChallengeLevels(self.challenge.ID) |
| GetChallengesWithGroupID | function | C_Challenge.GetChallengesWithGroupID(arg1) | local challenges = C_Challenge.GetChallengesWithGroupID(value1) |
| GetCompletedChallenges | function | C_Challenge.GetCompletedChallenges(...) |  |
| GetConditionLocalization | function | C_Challenge.GetConditionLocalization(arg1) | local name, description, negativeName, negativeDescription = C_Challenge.GetConditionLocalization... |
| GetModifierLocalization | function | C_Challenge.GetModifierLocalization(arg1) | tooltipTitle, tooltipText, icon = C_Challenge.GetModifierLocalization(modifier) |
| GetNumChallenges | function | C_Challenge.GetNumChallenges(...) | self.Challenges:SetGetNumResultsFunction(C_Challenge.GetNumChallenges) |
| GetPendingChallenges | function | C_Challenge.GetPendingChallenges() |  |
| GetRequirementLocalization | function | C_Challenge.GetRequirementLocalization(arg1) | local name, description, atlas, altAtlas, formatter1, formatter2, formatter3 = C_Challenge.GetReq... |
| GetRuleLocalization | function | C_Challenge.GetRuleLocalization(arg1) | local name, description = C_Challenge.GetRuleLocalization(data) |
| HasBrokenChallengeRule | function | C_Challenge.HasBrokenChallengeRule(arg1) | if C_Challenge.HasBrokenChallengeRule(data) then |
| HasChallengeRule | function | C_Challenge.HasChallengeRule(arg1) | return not C_Challenge.HasChallengeRule("CHALLENGE_RULES_TYPE_NO_GROUP") |
| IsChallengeActive | function | C_Challenge.IsChallengeActive(arg1) | return C_Challenge.IsChallengeActive(self.challenge.ID) |
| QueryChallengeCompletions | function | C_Challenge.QueryChallengeCompletions(arg1, arg2) | C_Challenge.QueryChallengeCompletions(self.challenge.ID, self:GetSelectedLevel()) |
| QueryChallengeFailures | function | C_Challenge.QueryChallengeFailures() |  |
| SendChallengeSyncResponse | function | C_Challenge.SendChallengeSyncResponse(arg1) |  |
| SetChallengeFilter | function | C_Challenge.SetChallengeFilter(arg1, arg2) | C_Challenge.SetChallengeFilter(searchText, self.filters) |
| StartChallenge | function | C_Challenge.StartChallenge(arg1, arg2) | return C_Challenge.StartChallenge(self.challenge.ID, self:GetSelectedLevel()) |
| StopChallenge | function | C_Challenge.StopChallenge(arg1) | return C_Challenge.StopChallenge(self.challenge.ID) |



## Notes


- 9 member(s) had a runtime probe marked `ok` in the scan data.
