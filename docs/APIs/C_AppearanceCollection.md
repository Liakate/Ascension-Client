# C_AppearanceCollection



**Members:** 12  •  **Functions:** 12  •  **Interface calls:** 27 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ApplyCategoryFilter | function | C_AppearanceCollection.ApplyCategoryFilter(arg1, arg2, arg3, arg4) | C_AppearanceCollection.ApplyCategoryFilter(self.categoryID, self.SearchBox:GetText():trim(), filt... |
| CollectItemAppearance | function | C_AppearanceCollection.CollectItemAppearance(arg1) |  |
| GetAppearanceTypes | function | C_AppearanceCollection.GetAppearanceTypes() | for index, appearanceType in ipairs(C_AppearanceCollection.GetAppearanceTypes()) do |
| GetAvailableChapters | function | C_AppearanceCollection.GetAvailableChapters(arg1) | local chapter = C_AppearanceCollection.GetAvailableChapters(season) |
| GetAvailableSeasons | function | C_AppearanceCollection.GetAvailableSeasons() | local season = C_AppearanceCollection.GetAvailableSeasons() |
| GetCategoriesForType | function | C_AppearanceCollection.GetCategoriesForType(arg1) | categories = C_AppearanceCollection.GetCategoriesForType("APPEARANCE_TYPE_ITEM") |
| GetCategoryAppearances | function | C_AppearanceCollection.GetCategoryAppearances(arg1) | local appearanceIDs = C_AppearanceCollection.GetCategoryAppearances(self.page) |
| GetCategoryInfo | function | C_AppearanceCollection.GetCategoryInfo(arg1) | local _, icon = C_AppearanceCollection.GetCategoryInfo(categoryID) |
| GetCategoryMaxPages | function | C_AppearanceCollection.GetCategoryMaxPages() | self.maxPages = C_AppearanceCollection.GetCategoryMaxPages() |
| GetCollectedCount | function | C_AppearanceCollection.GetCollectedCount(arg1) | local collected, numAppearances = C_AppearanceCollection.GetCollectedCount(self.categoryID) |
| GetSeasonalItems | function | C_AppearanceCollection.GetSeasonalItems(arg1, arg2) | local appearanceIDs = C_AppearanceCollection.GetSeasonalItems(season, chapter) |
| IsAppearanceCollected | function | C_AppearanceCollection.IsAppearanceCollected(arg1) | self.isCollected = C_AppearanceCollection.IsAppearanceCollected(self.appearanceID) and 1 or 0 |
