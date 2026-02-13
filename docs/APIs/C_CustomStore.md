# C_CustomStore



**Members:** 11  •  **Functions:** 11  •  **Interface calls:** 14 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ApplyCustomStoreFilter | function | C_CustomStore.ApplyCustomStoreFilter(arg1, arg2, arg3, arg4) | C_CustomStore.ApplyCustomStoreFilter(self:GetSearch(), self:GetFilter(), self.sorting or table.em... |
| CanPurchaseCustomStoreItem | function | C_CustomStore.CanPurchaseCustomStoreItem(...) |  |
| CanQueryCustomStore | function | C_CustomStore.CanQueryCustomStore(...) |  |
| GetCustomStoreData | function | C_CustomStore.GetCustomStoreData(arg1) | return #C_CustomStore.GetCustomStoreData(self.page) |
| GetCustomStoreItemInfo | function | C_CustomStore.GetCustomStoreItemInfo(arg1) | local itemID, moneyCost, requiredItems, requiredItemCosts, requiredGameEvent, requiredAchievement... |
| GetCustomStoreMaxPages | function | C_CustomStore.GetCustomStoreMaxPages() | return C_CustomStore.GetCustomStoreMaxPages() |
| GetCustomStoreTypeInfo | function | C_CustomStore.GetCustomStoreTypeInfo(arg1) | local trialMasterStoreName = C_CustomStore.GetCustomStoreTypeInfo(Enum.CustomStores.TrialMasters) |
| IsItemLockedDueToAchievement | function | C_CustomStore.IsItemLockedDueToAchievement(arg1) | return C_CustomStore.IsItemLockedDueToAchievement(self.customStore:GetStoreItemAtIndex(self:GetIn... |
| IsItemLockedDueToGameEvent | function | C_CustomStore.IsItemLockedDueToGameEvent(arg1) | return C_CustomStore.IsItemLockedDueToGameEvent(self.customStore:GetStoreItemAtIndex(self:GetInde... |
| PurchaseCustomStoreItem | function | C_CustomStore.PurchaseCustomStoreItem(arg1, arg2) |  |
| QueryCustomStore | function | C_CustomStore.QueryCustomStore(arg1) | C_CustomStore.QueryCustomStore(self.storeID) |
