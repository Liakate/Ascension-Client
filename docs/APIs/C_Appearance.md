# C_Appearance



**Members:** 24  •  **Functions:** 24  •  **Interface calls:** 69 (across up to 7 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ApplyPendingAppearances | function | C_Appearance.ApplyPendingAppearances(arg1) |  |
| CanApplyPendingAppearances | function | C_Appearance.CanApplyPendingAppearances() | local canApply, reason = C_Appearance.CanApplyPendingAppearances() |
| CanSeeAppearances | function | C_Appearance.CanSeeAppearances() | local canSeeItemTransmog, canSeeSpellTransmog = C_Appearance.CanSeeAppearances() |
| CanSetAppearance | function | C_Appearance.CanSetAppearance(arg1, arg2) | canApply = showPendingUndo or C_Appearance.CanSetAppearance(self.categoryID, pendingAppearanceID) |
| ClearInvalidPendingAppearances | function | C_Appearance.ClearInvalidPendingAppearances() |  |
| ClearPendingAppearance | function | C_Appearance.ClearPendingAppearance(arg1) | C_Appearance.ClearPendingAppearance(self.categoryID) |
| ClearPendingAppearances | function | C_Appearance.ClearPendingAppearances() |  |
| GetActiveDiscount | function | C_Appearance.GetActiveDiscount(arg1) | local discount, url = C_Appearance.GetActiveDiscount(self.appearanceID) |
| GetAlternativeIDs | function | C_Appearance.GetAlternativeIDs(arg1, arg2) | local alternativeIDs = C_Appearance.GetAlternativeIDs(self.appearanceID, self.entry) |
| GetAppearanceDetails | function | C_Appearance.GetAppearanceDetails(arg1) | local additionalTooltip = C_Appearance.GetAppearanceDetails(self.appearanceID) |
| GetAppearanceDisplayInfo | function | C_Appearance.GetAppearanceDisplayInfo(arg1) | local displayType, displayID, _, displayName = C_Appearance.GetAppearanceDisplayInfo(appearanceID) |
| GetAppearanceForCategory | function | C_Appearance.GetAppearanceForCategory(arg1) | if C_Appearance.GetAppearanceForCategory(self.categoryID) then |
| GetAppearanceItemSet | function | C_Appearance.GetAppearanceItemSet(arg1) | local setName = C_Appearance.GetAppearanceItemSet(self.appearanceID) |
| GetAppearanceWebURL | function | C_Appearance.GetAppearanceWebURL(arg1) | local url = C_Appearance.GetAppearanceWebURL(pendingAppearanceID) |
| GetCreatureDisplayItems | function | C_Appearance.GetCreatureDisplayItems(arg1) | local displayItems = C_Appearance.GetCreatureDisplayItems(self.appearanceID) |
| GetEtherealBazaarWebURL | function | C_Appearance.GetEtherealBazaarWebURL() | self.Textures.BazaarButton.url = C_Appearance.GetEtherealBazaarWebURL() |
| GetItemAppearanceID | function | C_Appearance.GetItemAppearanceID(arg1) | currentEquipped = currentEquipped and C_Appearance.GetItemAppearanceID(currentEquipped) |
| GetItemSetAppearanceID | function | C_Appearance.GetItemSetAppearanceID(...) |  |
| GetPendingAppearance | function | C_Appearance.GetPendingAppearance(arg1) | local pendingAppearanceID = C_Appearance.GetPendingAppearance(self.categoryID) |
| HasPendingAppearances | function | C_Appearance.HasPendingAppearances() | local hasPending = C_Appearance.HasPendingAppearances() |
| IsEtherealBazaarAppearance | function | C_Appearance.IsEtherealBazaarAppearance(arg1) | if C_Appearance.IsEtherealBazaarAppearance(pendingAppearanceID) then |
| IsTransmogable | function | C_Appearance.IsTransmogable(arg1, arg2) | if C_Appearance.IsTransmogable(self.categoryID, self.appearanceID) then |
| SetCanSeeAppearances | function | C_Appearance.SetCanSeeAppearances(arg1, arg2) | C_Appearance.SetCanSeeAppearances(canSeeItemTransmog, canSeeSpellTransmog) |
| SetPendingAppearance | function | C_Appearance.SetPendingAppearance(arg1, arg2) | C_Appearance.SetPendingAppearance(self.categoryID, 0) |
