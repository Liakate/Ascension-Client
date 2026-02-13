# C_AddonPanel



**Members:** 24  •  **Functions:** 20  •  **Interface calls:** 57 (across up to 4 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `SharedXML/Util/C_AddonPanel.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| DeleteSaveState | function | C_AddonPanel:DeleteSaveState(arg1) | function C_AddonPanel:DeleteSaveState(id) |
| EnableHiddenAddons | function | C_AddonPanel:EnableHiddenAddons() | function C_AddonPanel:EnableHiddenAddons() |
| EnumerateAddOns | function | C_AddonPanel:EnumerateAddOns() | for _, addon in C_AddonPanel:EnumerateAddOns() do |
| GetAddonDisabledBy | function | C_AddonPanel:GetAddonDisabledBy(arg1) | local disabledChars = C_AddonPanel:GetAddonDisabledBy(addon) |
| GetAddonIndex | function | C_AddonPanel:GetAddonIndex(arg1, arg2) | local selectedIndex = C_AddonPanel:GetAddonIndex(self.selectedAddon, addons) |
| GetAddonIndexRaw | function | C_AddonPanel:GetAddonIndexRaw(arg1) | function C_AddonPanel:GetAddonIndexRaw(addonToFind) |
| GetAddonObject | function | C_AddonPanel:GetAddonObject(arg1) | function C_AddonPanel:GetAddonObject(name) |
| GetNumInsecureAddons | function | C_AddonPanel:GetNumInsecureAddons() | function C_AddonPanel:GetNumInsecureAddons() |
| GetSaveState | function | C_AddonPanel:GetSaveState(arg1) | local preset = C_AddonPanel:GetSaveState(id) |
| GetSaveStateIDs | function | C_AddonPanel:GetSaveStateIDs() | for i, id in ipairs(C_AddonPanel:GetSaveStateIDs()) do |
| GetSearchedAddons | function | C_AddonPanel:GetSearchedAddons(arg1) | local addons = C_AddonPanel:GetSearchedAddons(self.searchText) |
| HasConfigurableAddons | function | C_AddonPanel:HasConfigurableAddons() | function C_AddonPanel:HasConfigurableAddons() |
| InitializeAddonList | function | C_AddonPanel:InitializeAddonList() | function C_AddonPanel:InitializeAddonList() |
| IsAddonSearched | function | C_AddonPanel:IsAddonSearched(arg1, arg2) | function C_AddonPanel:IsAddonSearched(addon, searchText) |
| IsSecureAddon | function | C_AddonPanel:IsSecureAddon(arg1) | function C_AddonPanel:IsSecureAddon(id) |
| MakeSaveState | function | C_AddonPanel:MakeSaveState() | self.saveState = C_AddonPanel:MakeSaveState() |
| RefreshAddonData | function | C_AddonPanel:RefreshAddonData() | function C_AddonPanel:RefreshAddonData() |
| RestoreSaveState | function | C_AddonPanel:RestoreSaveState(arg1) | C_AddonPanel:RestoreSaveState(self.saveState) |
| UpdateAddonList | function | C_AddonPanel:UpdateAddonList() | function C_AddonPanel:UpdateAddonList() |
| WriteSaveState | function | C_AddonPanel:WriteSaveState(arg1, arg2, arg3) | function C_AddonPanel:WriteSaveState(id, state, write) |
| saveFile | string | C_AddonPanel.saveFile | local compressed = ReadCustomWTF(C_AddonPanel.saveFile) |
| addons | table | C_AddonPanel.addons |  |
| addonsByIndex | table | C_AddonPanel.addonsByIndex |  |
| addonsByName | table | C_AddonPanel.addonsByName |  |
