# C_InventoryState



**Members:** 11  •  **Functions:** 7  •  **Interface calls:** 9 (across up to 2 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_InventoryState.lua` line 11




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ClearAllNewItems | function | C_InventoryState:ClearAllNewItems() | function C_InventoryState:ClearAllNewItems() |
| ITEM_PUSH | function | C_InventoryState:ITEM_PUSH(arg1, arg2) | function C_InventoryState:ITEM_PUSH(bag, icon) |
| IsNewItem | function | C_InventoryState:IsNewItem(arg1, arg2) | function C_InventoryState:IsNewItem(bag, slot) |
| ItemUpdate | function | C_InventoryState:ItemUpdate() | function C_InventoryState:ItemUpdate() |
| PLAYER_ENTERED_WORLD | function | C_InventoryState:PLAYER_ENTERED_WORLD() | function C_InventoryState:PLAYER_ENTERED_WORLD() |
| RemoveNewItem | function | C_InventoryState:RemoveNewItem(arg1, arg2) | function C_InventoryState:RemoveNewItem(bag, slot) |
| UpdateCurrentItems | function | C_InventoryState:UpdateCurrentItems() | function C_InventoryState:UpdateCurrentItems() |
| Equipped | table | C_InventoryState.Equipped |  |
| Inventory | table | C_InventoryState.Inventory | for bag, bagData in pairs(C_InventoryState.Inventory) do |
| NewItems | table | C_InventoryState.NewItems |  |
| RecentPush | table | C_InventoryState.RecentPush |  |
