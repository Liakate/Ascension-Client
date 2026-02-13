# C_Item



**Members:** 12  •  **Functions:** 10  •  **Interface calls:** 12 (across up to 2 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_Item.lua` line 5




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanBind | function | C_Item.CanBind(...) |  |
| GetCacheTooltip | function | C_Item:GetCacheTooltip() | local tooltip = C_Item:GetCacheTooltip() |
| GetColoredItemName | function | C_Item.GetColoredItemName(arg1) | function C_Item.GetColoredItemName(itemID) |
| GetLastUsedItemID | function | C_Item:GetLastUsedItemID() | local itemID, timeSinceUsed = C_Item:GetLastUsedItemID() |
| GetMerchantItemRatingRequirement | function | C_Item:GetMerchantItemRatingRequirement(arg1) | function C_Item:GetMerchantItemRatingRequirement(itemIndex) |
| GetNameAndID | function | C_Item:GetNameAndID(arg1) | local name, itemID = C_Item:GetNameAndID(self:GetText():trim()) |
| GetScalingLevel | function | C_Item.GetScalingLevel(...) |  |
| GetSlotItemPower | function | C_Item:GetSlotItemPower(arg1) | function C_Item:GetSlotItemPower(slot) |
| ITEM_USED_PAYLOAD | function | C_Item:ITEM_USED_PAYLOAD(arg1) | function C_Item:ITEM_USED_PAYLOAD(json) |
| IsBound | function | C_Item.IsBound(...) |  |
| lastUsedItem | table | C_Item.lastUsedItem | C_Item.lastUsedItem = { time = TimeSince:Now() } |
| lastUsedItem.time | table | C_Item.lastUsedItem.time |  |



## Notes


- 3 member(s) had a runtime probe marked `ok` in the scan data.
