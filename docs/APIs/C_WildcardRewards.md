# C_WildcardRewards



**Members:** 8  •  **Functions:** 8  •  **Interface calls:** 10 (across up to 2 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanClaimScrollOfFortuneRewards | function | C_WildcardRewards.CanClaimScrollOfFortuneRewards(arg1, arg2, arg3) | return C_WildcardRewards.CanClaimScrollOfFortuneRewards(specialization, numRewards, leveling) |
| ClaimScrollOfFortuneRewards | function | C_WildcardRewards.ClaimScrollOfFortuneRewards(arg1, arg2, arg3) | C_WildcardRewards.ClaimScrollOfFortuneRewards(specialization, numRewards, leveling) |
| GetLevelingInfo | function | C_WildcardRewards.GetLevelingInfo(arg1) | return C_WildcardRewards.GetLevelingInfo(specialization) |
| GetMarkOfAscensionCost | function | C_WildcardRewards.GetMarkOfAscensionCost(arg1, arg2, arg3) | return C_WildcardRewards.GetMarkOfAscensionCost(specialization, numRewards, leveling) |
| GetNumClaimableScrollOfFortuneRewards | function | C_WildcardRewards.GetNumClaimableScrollOfFortuneRewards(arg1, arg2) | return C_WildcardRewards.GetNumClaimableScrollOfFortuneRewards(self.index, true) > 0 |
| GetNumClaimedScrollOfFortuneRewards | function | C_WildcardRewards.GetNumClaimedScrollOfFortuneRewards(arg1, arg2) | return C_WildcardRewards.GetNumClaimedScrollOfFortuneRewards(specialization, leveling) |
| GetRewards | function | C_WildcardRewards.GetRewards(arg1, arg2, arg3) | return C_WildcardRewards.GetRewards(specialization, numRewards, leveling) |
| GetScrollOfFortuneRewardsReleaseInfo | function | C_WildcardRewards.GetScrollOfFortuneRewardsReleaseInfo(arg1) | return C_WildcardRewards.GetScrollOfFortuneRewardsReleaseInfo(specialization) |
