# C_Config



**Members:** 6  •  **Functions:** 6  •  **Interface calls:** 46 (across up to 24 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetBoolConfig | function | C_Config.GetBoolConfig(arg1) | return IsRangedCategory() and C_Config.GetBoolConfig("CONFIG_THROWN_WEAPON_APPEARANCES_ENABLED") |
| GetFloatConfig | function | C_Config.GetFloatConfig(...) |  |
| GetFloatVectorConfig | function | C_Config.GetFloatVectorConfig(...) |  |
| GetIntConfig | function | C_Config.GetIntConfig(arg1) | itemID = C_Config.GetIntConfig(reward.configItemID) |
| GetIntVectorConfig | function | C_Config.GetIntVectorConfig(...) |  |
| GetRateConfig | function | C_Config.GetRateConfig(arg1) | depositMulti = C_Config.GetRateConfig("RATE_AUCTION_DEPOSIT_VANITY") or 0.0833 |



## Notes


- 3 member(s) had a runtime probe marked `ok` in the scan data.
