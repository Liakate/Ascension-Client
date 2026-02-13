# C_BuildDraft



**Members:** 8  •  **Functions:** 8  •  **Interface calls:** 11 (across up to 2 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetDraftableBuild | function | C_BuildDraft.GetDraftableBuild(arg1) | card:SetBuild(C_BuildDraft.GetDraftableBuild(buildCount), buildCount) |
| GetDraftedBuild | function | C_BuildDraft.GetDraftedBuild() | local draftedBuildID = C_BuildDraft.GetDraftedBuild() |
| GetNumDraftableBuilds | function | C_BuildDraft.GetNumDraftableBuilds() | local buildCount = C_BuildDraft.GetNumDraftableBuilds() |
| IsAwaitingRolePrompt | function | C_BuildDraft.IsAwaitingRolePrompt() | if C_BuildDraft.IsAwaitingRolePrompt() then |
| IsCompletedBuild | function | C_BuildDraft.IsCompletedBuild(arg1) | local completedBuild = C_BuildDraft.IsCompletedBuild(self.data.ID) |
| IsDraftableBuild | function | C_BuildDraft.IsDraftableBuild(...) |  |
| IsDraftedBuild | function | C_BuildDraft.IsDraftedBuild(...) |  |
| SelectRole | function | C_BuildDraft.SelectRole(arg1) | C_BuildDraft.SelectRole(buildRole) |



## Notes


- 2 member(s) had a runtime probe marked `ok` in the scan data.
