# C_MysticEnchant



**Members:** 56  •  **Functions:** 56  •  **Interface calls:** 74 (across up to 14 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ApplyItem | function | C_MysticEnchant.ApplyItem(...) |  |
| ApplySlot | function | C_MysticEnchant.ApplySlot(...) |  |
| CanApplyAnySlot | function | C_MysticEnchant.CanApplyAnySlot(...) |  |
| CanApplyItem | function | C_MysticEnchant.CanApplyItem(...) |  |
| CanApplySlot | function | C_MysticEnchant.CanApplySlot(...) |  |
| CanCollectionReforgeAnySlot | function | C_MysticEnchant.CanCollectionReforgeAnySlot(...) |  |
| CanCollectionReforgeItem | function | C_MysticEnchant.CanCollectionReforgeItem(...) |  |
| CanCollectionReforgeSlot | function | C_MysticEnchant.CanCollectionReforgeSlot(...) |  |
| CanDestroy | function | C_MysticEnchant.CanDestroy(...) |  |
| CanDisenchantItem | function | C_MysticEnchant.CanDisenchantItem(...) |  |
| CanDisenchantSlot | function | C_MysticEnchant.CanDisenchantSlot(...) |  |
| CanEquipEnchant | function | C_MysticEnchant.CanEquipEnchant(...) |  |
| CanEquipItem | function | C_MysticEnchant.CanEquipItem(...) |  |
| CanEquipSlot | function | C_MysticEnchant.CanEquipSlot(arg1) | safeCheckResult, errorMessages = C_MysticEnchant.CanEquipSlot(EnchantCollectionUtil:GetRealSlotID... |
| CanInspect | function | C_MysticEnchant.CanInspect(arg1) | if C_MysticEnchant.CanInspect(self.unit) then |
| CanPurchaseMysticExtract | function | C_MysticEnchant.CanPurchaseMysticExtract() | if C_MysticEnchant.CanPurchaseMysticExtract() then |
| CanPurchaseMysticScroll | function | C_MysticEnchant.CanPurchaseMysticScroll(...) |  |
| CanReforgeItem | function | C_MysticEnchant.CanReforgeItem(...) |  |
| CanReforgeSlot | function | C_MysticEnchant.CanReforgeSlot(...) |  |
| CanSaveApply | function | C_MysticEnchant.CanSaveApply(...) |  |
| CanSaveCollectionReforge | function | C_MysticEnchant.CanSaveCollectionReforge(...) |  |
| CollectionReforgeItem | function | C_MysticEnchant.CollectionReforgeItem(...) |  |
| CollectionReforgeSlot | function | C_MysticEnchant.CollectionReforgeSlot(...) |  |
| Destroy | function | C_MysticEnchant.Destroy(...) |  |
| DisenchantItem | function | C_MysticEnchant.DisenchantItem(...) |  |
| DisenchantSlot | function | C_MysticEnchant.DisenchantSlot(...) |  |
| GetAppliedEnchant | function | C_MysticEnchant.GetAppliedEnchant(arg1, arg2) | return self:GetTempSlotData(slot) or C_MysticEnchant.GetAppliedEnchant("player", slot) |
| GetApplyChanges | function | C_MysticEnchant.GetApplyChanges() | self.tempSlotData = C_MysticEnchant.GetApplyChanges() |
| GetApplyItemCost | function | C_MysticEnchant.GetApplyItemCost(...) |  |
| GetCollectionReforgeChanges | function | C_MysticEnchant.GetCollectionReforgeChanges() | self.tempSlotData = C_MysticEnchant.GetCollectionReforgeChanges() |
| GetCollectionReforgeItemCost | function | C_MysticEnchant.GetCollectionReforgeItemCost(arg1) | local tokenCost, moneyCost = C_MysticEnchant.GetCollectionReforgeItemCost(spellID) |
| GetCollectionReforgeSlotCost | function | C_MysticEnchant.GetCollectionReforgeSlotCost(arg1) | local tokenCost, moneyCost = C_MysticEnchant.GetCollectionReforgeSlotCost(spellID) |
| GetDisenchantCost | function | C_MysticEnchant.GetDisenchantCost(arg1, arg2) | local tokenCost, markCost = C_MysticEnchant.GetDisenchantCost(SpellID, MysticEnchantUtil.NeedsToP... |
| GetEnchantInfoByItem | function | C_MysticEnchant.GetEnchantInfoByItem(arg1) | local REData = C_MysticEnchant.GetEnchantInfoByItem(itemID) or (itemID == ItemData.UNTARNISHED_MY... |
| GetEnchantInfoBySpell | function | C_MysticEnchant.GetEnchantInfoBySpell(arg1) | local enchantInfo = C_MysticEnchant.GetEnchantInfoBySpell(spellID) |
| GetMysticScrollCost | function | C_MysticEnchant.GetMysticScrollCost() | self.MysticScrollCost = C_MysticEnchant.GetMysticScrollCost() |
| GetMysticScrolls | function | C_MysticEnchant.GetMysticScrolls() | self.scrolls = C_MysticEnchant.GetMysticScrolls() |
| GetProgress | function | C_MysticEnchant.GetProgress() | progress, level = C_MysticEnchant.GetProgress() |
| GetReforgeCost | function | C_MysticEnchant.GetReforgeCost() | local tokenCost = C_MysticEnchant.GetReforgeCost() |
| GetSaveCollectionReforgeSlotCost | function | C_MysticEnchant.GetSaveCollectionReforgeSlotCost(...) |  |
| HasAnyCollected | function | C_MysticEnchant.HasAnyCollected() | local hasAnyEnchants = C_MysticEnchant.HasAnyCollected() or C_MysticEnchant.HasAnyScroll() |
| HasAnyScroll | function | C_MysticEnchant.HasAnyScroll() | local hasAnyEnchants = C_MysticEnchant.HasAnyCollected() or C_MysticEnchant.HasAnyScroll() |
| HasAnySlotEnchanted | function | C_MysticEnchant.HasAnySlotEnchanted(...) |  |
| HasNearbyMysticAltar | function | C_MysticEnchant.HasNearbyMysticAltar() | return C_MysticEnchant.HasNearbyMysticAltar() |
| Inspect | function | C_MysticEnchant.Inspect(arg1, arg2) | C_MysticEnchant.Inspect(self.unit, true) |
| PurchaseMysticExtract | function | C_MysticEnchant.PurchaseMysticExtract() | C_MysticEnchant.PurchaseMysticExtract() |
| PurchaseMysticScroll | function | C_MysticEnchant.PurchaseMysticScroll(...) |  |
| QueryEnchants | function | C_MysticEnchant.QueryEnchants(arg1, arg2, arg3, arg4) | local _, totalKnownEnchants = C_MysticEnchant.QueryEnchants(1, 1, "", {Enum.ECFilters.RE_FILTER_K... |
| ReforgeItem | function | C_MysticEnchant.ReforgeItem(...) |  |
| ReforgeSlot | function | C_MysticEnchant.ReforgeSlot(...) |  |
| SaveApply | function | C_MysticEnchant.SaveApply(...) |  |
| SaveCollectionReforge | function | C_MysticEnchant.SaveCollectionReforge(...) |  |
| UndoApply | function | C_MysticEnchant.UndoApply(arg1) | C_MysticEnchant.UndoApply(slot) |
| UndoCollectionReforge | function | C_MysticEnchant.UndoCollectionReforge(arg1) | C_MysticEnchant.UndoCollectionReforge(slot) |
| UndoLastApply | function | C_MysticEnchant.UndoLastApply(...) |  |
| UndoLastCollectionReforge | function | C_MysticEnchant.UndoLastCollectionReforge(...) |  |



## Notes


- 9 member(s) had a runtime probe marked `ok` in the scan data.
