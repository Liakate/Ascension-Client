# C_TemporalContracts



**Members:** 16  •  **Functions:** 16  •  **Interface calls:** 20 (across up to 1 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ActivateAllTemporalContracts | function | C_TemporalContracts.ActivateAllTemporalContracts(...) |  |
| ActivateAllTemporalContractsByContentType | function | C_TemporalContracts.ActivateAllTemporalContractsByContentType(arg1, arg2) | C_TemporalContracts.ActivateAllTemporalContractsByContentType(parent.category, true) |
| ActivateTemporalContract | function | C_TemporalContracts.ActivateTemporalContract(arg1, arg2) | C_TemporalContracts.ActivateTemporalContract(category, true) |
| GetCategoryData | function | C_TemporalContracts.GetCategoryData(arg1) | local serverData = C_TemporalContracts.GetCategoryData(subCategory) |
| GetCategoryName | function | C_TemporalContracts.GetCategoryName(arg1) | self.title:SetText("\|cffFFFFFF"..C_TemporalContracts.GetCategoryName(self.name) or self.name) |
| GetCompletableQuestsByCategory | function | C_TemporalContracts.GetCompletableQuestsByCategory(...) |  |
| GetCompletableTemporalContracts | function | C_TemporalContracts.GetCompletableTemporalContracts() | local temporalContractsInfo = C_TemporalContracts.GetCompletableTemporalContracts() or {} |
| GetQuestCategory | function | C_TemporalContracts.GetQuestCategory(arg1) | local subCatagory = C_TemporalContracts.GetQuestCategory(questID) |
| GetQuestSortIDs | function | C_TemporalContracts.GetQuestSortIDs(arg1, arg2) | local questSortIds = C_TemporalContracts.GetQuestSortIDs(questData.ID, false) |
| GetQuestSortText | function | C_TemporalContracts.GetQuestSortText(arg1) | self.categorizedQuestList[questSortId] = self.categorizedQuestList[questSortId] or {name = C_Temp... |
| GetTemporalContractInfo | function | C_TemporalContracts.GetTemporalContractInfo(...) |  |
| GetTemporalContractTypes | function | C_TemporalContracts.GetTemporalContractTypes() | for category, subCategoryData in pairs(C_TemporalContracts.GetTemporalContractTypes()) do |
| GetTotalContentTypeCost | function | C_TemporalContracts.GetTotalContentTypeCost(arg1) | local totalCostInfo = C_TemporalContracts.GetTotalContentTypeCost(category) or {} |
| GetTotalContentTypeRewards | function | C_TemporalContracts.GetTotalContentTypeRewards(arg1) | subCategoryData["TOTAL"] = {rewards = C_TemporalContracts.GetTotalContentTypeRewards(category), r... |
| GetTotalContractTypeCost | function | C_TemporalContracts.GetTotalContractTypeCost(arg1) | local costInfo = C_TemporalContracts.GetTotalContractTypeCost(subCategory) or {} |
| GetTotalContractTypeRewards | function | C_TemporalContracts.GetTotalContractTypeRewards(arg1) | data.rewards = C_TemporalContracts.GetTotalContractTypeRewards(subCategory) |



## Notes


- 2 member(s) had a runtime probe marked `ok` in the scan data.
