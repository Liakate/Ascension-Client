# C_VanityCollection



**Members:** 10  •  **Functions:** 10  •  **Interface calls:** 22 (across up to 4 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetAllItems | function | C_VanityCollection.GetAllItems() | for _, data in ipairs(C_VanityCollection.GetAllItems()) do |
| GetDPPrice | function | C_VanityCollection.GetDPPrice(arg1) | local ItemDPCost = C_VanityCollection.GetDPPrice(itemID) |
| GetItem | function | C_VanityCollection.GetItem(arg1) | local data = C_VanityCollection.GetItem(itemID) |
| GetNum | function | C_VanityCollection.GetNum(...) |  |
| GetVPPrice | function | C_VanityCollection.GetVPPrice(...) |  |
| IsCollectionItemOwned | function | C_VanityCollection.IsCollectionItemOwned(arg1) | if C_VanityCollection.IsCollectionItemOwned(ItemData.DEALERS_DRAFT_DECK) then |
| IsConsolidatedVanityBuff | function | C_VanityCollection.IsConsolidatedVanityBuff(arg1) |  |
| IsPurchaseInProgress | function | C_VanityCollection.IsPurchaseInProgress() | if C_VanityCollection.IsPurchaseInProgress() then |
| PurchaseCollectionItem | function | C_VanityCollection.PurchaseCollectionItem(arg1, arg2) | C_VanityCollection.PurchaseCollectionItem(Store.ItemInternal, costType) |
| PurchaseWebShopItem | function | C_VanityCollection.PurchaseWebShopItem(arg1) | if C_VanityCollection.PurchaseWebShopItem(Store.ItemInternal) then |



## Notes


- 2 member(s) had a runtime probe marked `ok` in the scan data.
