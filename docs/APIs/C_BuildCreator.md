# C_BuildCreator



**Members:** 21  •  **Functions:** 21  •  **Interface calls:** 59 (across up to 6 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ActivateBuild | function | C_BuildCreator.ActivateBuild(arg1, arg2, arg3) | C_BuildCreator.ActivateBuild(self.build.ID, true, true) |
| BookmarkBuild | function | C_BuildCreator.BookmarkBuild(arg1) | C_BuildCreator.BookmarkBuild(self.data.ID) |
| CanActivateBuild | function | C_BuildCreator.CanActivateBuild(arg1) | local canActivate, reasons = C_BuildCreator.CanActivateBuild(self.data.ID) |
| CanDeactivateBuild | function | C_BuildCreator.CanDeactivateBuild(...) |  |
| DeactivateBuild | function | C_BuildCreator.DeactivateBuild(arg1) |  |
| DeleteBuild | function | C_BuildCreator.DeleteBuild(arg1) | local success, failReason = C_BuildCreator.DeleteBuild(buildID) |
| ExportBuild | function | C_BuildCreator.ExportBuild(...) |  |
| GetActiveBuild | function | C_BuildCreator.GetActiveBuild(arg1) | local activeBuild = C_BuildCreator.GetActiveBuild(specID) |
| GetActiveSpecForBuild | function | C_BuildCreator.GetActiveSpecForBuild(...) |  |
| GetBookmarkedBuildAtIndex | function | C_BuildCreator.GetBookmarkedBuildAtIndex(arg1) | local id = C_BuildCreator.GetBookmarkedBuildAtIndex(self.index) |
| GetBuild | function | C_BuildCreator.GetBuild(arg1) | local build = C_BuildCreator.GetBuild(buildID) |
| GetBuildAtIndex | function | C_BuildCreator.GetBuildAtIndex(arg1) | self.data = C_BuildCreator.GetBuildAtIndex(self.index) |
| GetNumBookmarkedBuilds | function | C_BuildCreator.GetNumBookmarkedBuilds() | self.BuildScroll:SetGetNumResultsFunction(C_BuildCreator.GetNumBookmarkedBuilds) |
| GetNumBuilds | function | C_BuildCreator.GetNumBuilds() | self.BuildScroll:SetGetNumResultsFunction(C_BuildCreator.GetNumBuilds) |
| GetSpell | function | C_BuildCreator.GetSpell(arg1, arg2) | local spell = C_BuildCreator.GetSpell(WildCardRapidRollingFrame.savedBuild.ID, self:GetSpellID()) |
| IsOwnedBuild | function | C_BuildCreator.IsOwnedBuild(arg1) | local canEdit = C_BuildCreator.IsOwnedBuild(self.build.ID) |
| IsUpvotedBuild | function | C_BuildCreator.IsUpvotedBuild(arg1) | self.LikeButton:SetChecked(C_BuildCreator.IsUpvotedBuild(self.data.ID)) |
| QueryAllBuilds | function | C_BuildCreator.QueryAllBuilds(arg1) | C_BuildCreator.QueryAllBuilds(category) |
| QueryBuild | function | C_BuildCreator.QueryBuild(arg1) | C_BuildCreator.QueryBuild(buildID) |
| RateBuild | function | C_BuildCreator.RateBuild(arg1, arg2) | C_BuildCreator.RateBuild(self.data.ID, false) |
| UpdateFilter | function | C_BuildCreator.UpdateFilter(arg1, arg2, arg3) | C_BuildCreator.UpdateFilter(text, self:ApplyDefaultClassFilter(), self.sort) |



## Notes


- 1 member(s) had a runtime probe marked `ok` in the scan data.
