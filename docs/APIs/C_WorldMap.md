# C_WorldMap



**Members:** 15  •  **Functions:** 15  •  **Interface calls:** 33 (across up to 2 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_WorldMap.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanShowPOI | function | C_WorldMap.CanShowPOI(arg1) | if not C_WorldMap.CanShowPOI then |
| GetCurrentMapID | function | C_WorldMap.GetCurrentMapID() | local currentMapID = C_WorldMap.GetCurrentMapID() |
| GetMapFileByAreaID | function | C_WorldMap.GetMapFileByAreaID(arg1) | local fileName = C_WorldMap.GetMapFileByAreaID(areaID) |
| GetMapFileByZoneID | function | C_WorldMap.GetMapFileByZoneID(arg1) |  |
| GetMapIDByAreaID | function | C_WorldMap.GetMapIDByAreaID(arg1) | return currentAreaID and C_WorldMap.GetMapIDByAreaID(currentAreaID) or -1 |
| GetMapIDByZoneID | function | C_WorldMap.GetMapIDByZoneID(arg1) | local mapID = C_WorldMap.GetMapIDByZoneID(obj.ZoneId) |
| GetMapPosition | function | C_WorldMap.GetMapPosition(arg1, arg2, arg3, arg4) | return C_WorldMap.GetMapPosition(C_WorldMap.GetMapIDByAreaID(Z), worldX, worldY, 0) |
| GetPOIFilter | function | C_WorldMap.GetPOIFilter(arg1) | if not C_WorldMap.GetPOIFilter then |
| GetVisiblePOI | function | C_WorldMap.GetVisiblePOI() | if not C_WorldMap.GetVisiblePOI then |
| GetWorldPosition | function | C_WorldMap.GetWorldPosition(arg1, arg2, arg3) | local worldX1, worldY1 = C_WorldMap.GetWorldPosition(z1, x1, y1) |
| GetZoneIDByAreaID | function | C_WorldMap.GetZoneIDByAreaID(arg1) |  |
| IsOnCityMap | function | C_WorldMap.IsOnCityMap() | if bit.contains(poi.Flags, Enum.POIFlags.OnlyInCity) and not C_WorldMap.IsOnCityMap() then |
| IsOnContinentMap | function | C_WorldMap.IsOnContinentMap() | if C_WorldMap.IsOnContinentMap() then |
| SetPOIFilter | function | C_WorldMap.SetPOIFilter(arg1, arg2) | if not C_WorldMap.SetPOIFilter then |
| SetPOIFilters | function | C_WorldMap.SetPOIFilters(arg1) | if not C_WorldMap.SetPOIFilters then |
