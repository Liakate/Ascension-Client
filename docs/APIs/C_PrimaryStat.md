# C_PrimaryStat



**Members:** 12  •  **Functions:** 8  •  **Interface calls:** 43 (across up to 14 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_PrimaryStat.lua` line 2




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetActivePrimaryStat | function | C_PrimaryStat:GetActivePrimaryStat() | local primaryStat = C_PrimaryStat:GetActivePrimaryStat() |
| GetInternalID | function | C_PrimaryStat:GetInternalID(arg1) | local selectedStat = stat and C_PrimaryStat:GetInternalID(stat) or nil |
| GetPrimaryStatAura | function | C_PrimaryStat:GetPrimaryStatAura(arg1) | function C_PrimaryStat:GetPrimaryStatAura(id) |
| GetPrimaryStatID | function | C_PrimaryStat:GetPrimaryStatID(arg1) | function C_PrimaryStat:GetPrimaryStatID(spellId) |
| GetPrimaryStatInfo | function | C_PrimaryStat:GetPrimaryStatInfo(arg1) | local statSpellID = C_PrimaryStat:GetPrimaryStatInfo(statID) |
| GetPrimaryStatSpell | function | C_PrimaryStat:GetPrimaryStatSpell(arg1) | function C_PrimaryStat:GetPrimaryStatSpell(id) |
| GetUnitPrimaryStat | function | C_PrimaryStat:GetUnitPrimaryStat(arg1) | function C_PrimaryStat:GetUnitPrimaryStat(unit) |
| SetPrimaryStat | function | C_PrimaryStat:SetPrimaryStat(arg1) | function C_PrimaryStat:SetPrimaryStat(id) |
| AuraToID | table | C_PrimaryStat.AuraToID | C_PrimaryStat.AuraToID = { |
| Auras | table | C_PrimaryStat.Auras | C_PrimaryStat.Auras = { |
| SpellToID | table | C_PrimaryStat.SpellToID | C_PrimaryStat.SpellToID = { |
| internalIds | table | C_PrimaryStat.internalIds | for _, statInternalID in pairs(C_PrimaryStat.internalIds) do |
