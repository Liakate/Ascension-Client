# C_TrialCreator



**Members:** 21  •  **Functions:** 21  •  **Interface calls:** 25 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ActivateTrial | function | C_TrialCreator.ActivateTrial(arg1) | return C_TrialCreator.ActivateTrial(self.challenge.ID) |
| CanActivateTrial | function | C_TrialCreator.CanActivateTrial(arg1) | return C_TrialCreator.CanActivateTrial(self.challenge.ID) |
| CanDeactivateTrial | function | C_TrialCreator.CanDeactivateTrial() | return C_TrialCreator.CanDeactivateTrial() |
| CanEditTrial | function | C_TrialCreator.CanEditTrial(arg1) | local canEdit = C_TrialCreator.CanEditTrial(self.challenge.ID) |
| CanSaveTrial | function | C_TrialCreator.CanSaveTrial(arg1, arg2, arg3, arg4, arg5, arg6, arg7) | return C_TrialCreator.CanSaveTrial(self.trialID or "", trial.title, trial.about, trial.icon, chal... |
| DeactivateTrial | function | C_TrialCreator.DeactivateTrial() | return C_TrialCreator.DeactivateTrial() |
| DeleteTrial | function | C_TrialCreator.DeleteTrial(arg1) | C_TrialCreator.DeleteTrial(self.challenge.ID) |
| GetActiveTrial | function | C_TrialCreator.GetActiveTrial() | return C_TrialCreator.GetActiveTrial() == self.challenge.ID |
| GetAllTrials | function | C_TrialCreator.GetAllTrials(...) |  |
| GetNumTrials | function | C_TrialCreator.GetNumTrials(...) | self.Challenges:SetGetNumResultsFunction(C_TrialCreator.GetNumTrials) |
| GetOwnedTrials | function | C_TrialCreator.GetOwnedTrials(...) |  |
| GetTrialAtIndex | function | C_TrialCreator.GetTrialAtIndex(arg1, arg2) | return C_TrialCreator.GetTrialAtIndex(index, isExpanded) |
| GetTrialCompletion | function | C_TrialCreator.GetTrialCompletion(arg1, arg2) | if not C_TrialCreator.GetTrialCompletion(self.challenge.ID, 1) then |
| GetTrialCompletions | function | C_TrialCreator.GetTrialCompletions(arg1, arg2) | entries = C_TrialCreator.GetTrialCompletions(challengeID, 50) |
| GetTrialIDByIndex | function | C_TrialCreator.GetTrialIDByIndex(arg1) | return C_TrialCreator.GetTrialIDByIndex(index) |
| GetTrialInfo | function | C_TrialCreator.GetTrialInfo(arg1) | local trialInfo = C_TrialCreator.GetTrialInfo(self.challenge.ID) |
| QueryTrialCompletions | function | C_TrialCreator.QueryTrialCompletions(arg1) | C_TrialCreator.QueryTrialCompletions(self.challenge.ID) |
| QueryTrials | function | C_TrialCreator.QueryTrials() | C_TrialCreator.QueryTrials() |
| RateTrial | function | C_TrialCreator.RateTrial(arg1, arg2, arg3) | C_TrialCreator.RateTrial(self.challenge.ID, upvote, false) |
| SaveTrial | function | C_TrialCreator.SaveTrial(arg1, arg2, arg3, arg4, arg5, arg6, arg7) | C_TrialCreator.SaveTrial(self.trialID or "", trial.title, trial.about, trial.icon, challengeIDs, ... |
| SetTrialFilter | function | C_TrialCreator.SetTrialFilter(arg1, arg2) | C_TrialCreator.SetTrialFilter(searchText, self.filters) |



## Notes


- 3 member(s) had a runtime probe marked `ok` in the scan data.
