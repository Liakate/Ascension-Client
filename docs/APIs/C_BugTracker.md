# C_BugTracker



**Members:** 12  •  **Functions:** 12  •  **Interface calls:** 7 (across up to 1 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ClearReport | function | C_BugTracker.ClearReport() | C_BugTracker.ClearReport() |
| GetReportCategory | function | C_BugTracker.GetReportCategory(...) |  |
| GetReportDescription | function | C_BugTracker.GetReportDescription(...) |  |
| GetReportPriority | function | C_BugTracker.GetReportPriority(...) |  |
| GetReportTitle | function | C_BugTracker.GetReportTitle(...) |  |
| IsReportPublic | function | C_BugTracker.IsReportPublic(...) |  |
| SetReportCategory | function | C_BugTracker.SetReportCategory(arg1) | C_BugTracker.SetReportCategory(category) |
| SetReportDescription | function | C_BugTracker.SetReportDescription(arg1) | C_BugTracker.SetReportDescription(body) |
| SetReportPriority | function | C_BugTracker.SetReportPriority(arg1) | C_BugTracker.SetReportPriority(priority) |
| SetReportPublic | function | C_BugTracker.SetReportPublic(arg1) | C_BugTracker.SetReportPublic(isPublic) |
| SetReportTitle | function | C_BugTracker.SetReportTitle(arg1) | C_BugTracker.SetReportTitle(title) |
| SubmitReport | function | C_BugTracker.SubmitReport() | local success = C_BugTracker.SubmitReport() |
