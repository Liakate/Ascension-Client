# C_CVar



**Members:** 48  •  **Functions:** 22  •  **Interface calls:** 432 (across up to 63 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `SharedXML/Util/C_CVar.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| Exists | function | C_CVar.Exists(arg1) | if not C_CVar.Exists(cvar) then |
| Get | function | C_CVar.Get(arg1) | local lastClass = C_CVar.Get("caLastClass") |
| GetBitfield | function | C_CVar.GetBitfield(arg1, arg2) | local result = C_CVar.GetBitfield(cvar, bit) |
| GetBool | function | C_CVar.GetBool(arg1) | if C_CVar.GetBool("ShowFullBuildCreator") then |
| GetByteString | function | C_CVar.GetByteString(arg1) | function C_CVar.GetByteString(cvar) |
| GetCVarBitfield | function | C_CVar.GetCVarBitfield(...) |  |
| GetDefault | function | C_CVar.GetDefault(arg1) | function C_CVar.GetDefault(cvar) |
| GetDefaultBitfield | function | C_CVar.GetDefaultBitfield(arg1, arg2) | function C_CVar.GetDefaultBitfield(cvar, index) |
| GetDefaultBool | function | C_CVar.GetDefaultBool(arg1) | function C_CVar.GetDefaultBool(cvar) |
| GetDefaultNumber | function | C_CVar.GetDefaultNumber(arg1) | sizeGroup:AddChild("height", LAC:Range("Clickable-Height", "Controls the clickable area of the Na... |
| GetFlag | function | C_CVar.GetFlag(arg1, arg2) | function C_CVar.GetFlag(cvar, flag) |
| GetMax | function | C_CVar.GetMax(arg1) | sizeGroup:AddChild("height", LAC:Range("Clickable-Height", "Controls the clickable area of the Na... |
| GetMin | function | C_CVar.GetMin(arg1) | sizeGroup:AddChild("height", LAC:Range("Clickable-Height", "Controls the clickable area of the Na... |
| GetNumber | function | C_CVar.GetNumber(arg1) | if clickableHeight ~= C_CVar.GetNumber("nameplateWidth") or clickableWidth ~= C_CVar.GetNumber("n... |
| RegisterSavedCVar | function | C_CVar.RegisterSavedCVar(arg1, arg2) | C_CVar.RegisterSavedCVar("SpellActivationOverlayAlpha", "0.8", 0, 1) |
| RegisterSavedCharacterCVar | function | C_CVar.RegisterSavedCharacterCVar(arg1, arg2) | C_CVar.RegisterSavedCharacterCVar("COA_MULTICAST1", "0") |
| ResetToDefault | function | C_CVar.ResetToDefault(arg1) | function C_CVar.ResetToDefault(cvar) |
| Set | function | C_CVar.Set(arg1, arg2) | C_CVar.Set("previewCharacterAdvancementChanges", "0") |
| SetBitfield | function | C_CVar.SetBitfield(arg1, arg2, arg3) | C_CVar.SetBitfield("SkillCardExchangeSkip", ExchangeCVarBits.Normal, true) |
| SetCVarBitfield | function | C_CVar.SetCVarBitfield(...) |  |
| SetCVarSave | function | C_CVar.SetCVarSave(arg1, arg2) | C_CVar.SetCVarSave("Sound_MusicVolume", true) |
| SetFlag | function | C_CVar.SetFlag(arg1, arg2, arg3) | function C_CVar.SetFlag(cvar, flag, value) |
| Maximums.SpellActivationOverlayAlpha | number | C_CVar.Maximums.SpellActivationOverlayAlpha |  |
| Maximums.camerafov | number | C_CVar.Maximums.camerafov |  |
| Maximums.lootToastMaximum | number | C_CVar.Maximums.lootToastMaximum |  |
| Maximums.lossOfControlScale | number | C_CVar.Maximums.lossOfControlScale |  |
| Maximums.nameplateAngle | number | C_CVar.Maximums.nameplateAngle |  |
| Maximums.nameplateDistance | number | C_CVar.Maximums.nameplateDistance |  |
| Maximums.nameplateHeight | number | C_CVar.Maximums.nameplateHeight |  |
| Maximums.nameplateOverlapV | number | C_CVar.Maximums.nameplateOverlapV |  |
| Maximums.nameplateVerticalOffset | number | C_CVar.Maximums.nameplateVerticalOffset |  |
| Maximums.nameplateWidth | number | C_CVar.Maximums.nameplateWidth |  |
| Maximums.tabTargetAngle | number | C_CVar.Maximums.tabTargetAngle |  |
| Maximums.tabTargetRange | number | C_CVar.Maximums.tabTargetRange |  |
| Minimums.SpellActivationOverlayAlpha | number | C_CVar.Minimums.SpellActivationOverlayAlpha |  |
| Minimums.camerafov | number | C_CVar.Minimums.camerafov |  |
| Minimums.lootToastMaximum | number | C_CVar.Minimums.lootToastMaximum |  |
| Minimums.lossOfControlScale | number | C_CVar.Minimums.lossOfControlScale |  |
| Minimums.nameplateAngle | number | C_CVar.Minimums.nameplateAngle |  |
| Minimums.nameplateDistance | number | C_CVar.Minimums.nameplateDistance |  |
| Minimums.nameplateHeight | number | C_CVar.Minimums.nameplateHeight |  |
| Minimums.nameplateOverlapV | number | C_CVar.Minimums.nameplateOverlapV |  |
| Minimums.nameplateVerticalOffset | number | C_CVar.Minimums.nameplateVerticalOffset |  |
| Minimums.nameplateWidth | number | C_CVar.Minimums.nameplateWidth |  |
| Minimums.tabTargetAngle | number | C_CVar.Minimums.tabTargetAngle |  |
| Minimums.tabTargetRange | number | C_CVar.Minimums.tabTargetRange |  |
| Maximums | table | C_CVar.Maximums | C_CVar.Maximums = { |
| Minimums | table | C_CVar.Minimums | C_CVar.Minimums = { |
