# Interface Lua utilities (Ascension)


These APIs are implemented in the shipped Interface Lua. Some are also referenced by AddOns.



## JSON cache helpers


Ascension UI code uses a JSON cache pattern for server/client payloads.


*Defined in*: `SharedXML/Util/CustomFunctionChecks.lua`



### Functions



#### ClearJsonCache(category)


- Used to clear/query cached JSON payloads by category (+ optional index).



#### GetJsonCacheData(category, index)


- Used to clear/query cached JSON payloads by category (+ optional index).



#### HasJsonCacheData(category, index)


- Used to clear/query cached JSON payloads by category (+ optional index).



## SendJsonMessage


*Defined in*: `SharedXML/Util/C_Comm.lua`



### Syntax




```text
SendJsonMessage
(
eventName
,
 
jsonString
,
 
channel
)
```




### Notes


- Used by FrameXML modules to request/query data from the server (e.g., stats, payloads).
- Common `channel` values observed: `"BULK"`.



## Timers



## Timer


*Defined in*: `SharedXML/Util/Timer.lua`



### Members



#### Timer.After(duration, callback)



#### Timer.AfterCombat(callback)



#### Timer.NewTimer(duration, callback)



#### Timer.NewTicker(duration, callback, iterations)



#### Timer.WaitFor(duration, condition, callback, maxWaitSeconds)



#### Timer.AfterEvent(event, callback, count)



#### Timer.NextFrame(callback)



## C_Timer


*Defined in*: `SharedXML/Util/Timer.lua`


- No explicit function definitions detected by simple pattern scan (may be locals or mixins).



## Network opcode utilities



## OpcodeUtil


*Defined in*: `SharedXML/Util/OpcodeUtil.lua`



### Members



#### OpcodeUtil.RegisterOpcodeEvent(opcode, event, handler)


Registers an opcode event.  

When an opcode is received, the event will be triggered, using Handler to process the packet into args.  

first return value should be if the event should fire or not



#### OpcodeUtil.RemoveOpcodeEvent(opcode, event)


Removes an opcode event.



## Challenge and Trial creator utilities



## ChallengeUtil


*Defined in*: `FrameXML/Util/ChallengeUtil.lua`



### Members



#### ChallengeUtil.GetRequirementLocalization(RequirementType)



#### ChallengeUtil.ApplyMiscValueFormatting(miscValue1, miscValue2, miscValue3, formatter1, formatter2, formatter3)



#### ChallengeUtil.AreConditionsEqual(conditionA, conditionB)



#### ChallengeUtil.CanGroup()



#### ChallengeUtil.CanUseGroupFinder()



#### ChallengeUtil.CanQueueBattlegrounds()



#### ChallengeUtil.CanQueueArenas()



## TrialCreatorUtil


*Defined in*: `FrameXML/Util/ChallengeUtil.lua`



### Members



#### TrialCreatorUtil.ContinueOnLoad(trialID, callback)



## Game event utilities



## GameEventUtil


*Defined in*: `FrameXML/Util/GameEventUtil.lua`



### Members



#### GameEventUtil.IsEventActive(eventID)



#### GameEventUtil.IsAnyEventActive(...)



#### GameEventUtil.GetTimeRemaining(eventID)



#### GameEventUtil.GetTimeUntil(eventID)



#### GameEventUtil.GetState(eventID)



## Mystic Enchant manager utilities



## MysticEnchantManagerUtil


*Defined in*: `FrameXML/Util/MysticEnchantManagerUtil.lua`



### Members



#### MysticEnchantManagerUtil.GetEditablePreset()



#### MysticEnchantManagerUtil.SetEditablePreset(index)



#### MysticEnchantManagerUtil.GetPresetUnlockItem()



#### MysticEnchantManagerUtil.GetMaxPresets()



#### MysticEnchantManagerUtil.GetFreePresets()



#### MysticEnchantManagerUtil.HasUnlockItem()



#### MysticEnchantManagerUtil.GetNumPresets()



#### MysticEnchantManagerUtil.GetPresetData(index)



#### MysticEnchantManagerUtil.GetActualPresetName(index)



#### MysticEnchantManagerUtil.GetPresetName(index)



#### MysticEnchantManagerUtil.GetActivePreset()



#### MysticEnchantManagerUtil.GetActualPresetIcon(index)



#### MysticEnchantManagerUtil.GetPresetIcon(index)



#### MysticEnchantManagerUtil.UpdatePresetSlotMap(index, slotMap)



#### MysticEnchantManagerUtil.GetPresetSlotMap(index)



#### MysticEnchantManagerUtil.GetPresetInfo(index)



#### MysticEnchantManagerUtil.SaveCurrentAndActivateIndex(index)



#### MysticEnchantManagerUtil.WritePresets()



#### MysticEnchantManagerUtil.UpdatePresetData(name, icon)



#### MysticEnchantManagerUtil.AttemptOperation(func, checkFunc, ...)



## Token utilities



## TokenUtil


*Defined in*: `FrameXML/Util/TokenUtil.lua`



### Members



#### TokenUtil.GetTokenCount(tokenType)



#### TokenUtil.CreateFromTokenType(tokenType)



#### TokenUtil.GetTokenLink(tokenType)



#### TokenUtil.GetScrollOfFortuneTalentsForSpec(specID)



#### TokenUtil.GetScrollOfFortuneAbilitiesForSpec(specID)



#### TokenUtil.GetScrollOfFortuneForSpec(specID)



#### TokenUtil.GetSpecIDByToken(tokenType)



#### TokenUtil.RecentlyUsedCaseOfFortune()



#### TokenUtil:TOKEN_UPDATED(tokenType, oldAmount, newAmount)



#### TokenUtil:SCROLL_OF_FORTUNE_USED()



#### TokenUtil:CASE_OF_FORTUNE_USED()



## Character Advancement reset cost utilities



## CACostUtil


*Defined in*: `FrameXML/Util/CharacterAdvancementCostUtil.lua`



### Members



#### CACostUtil:GetUnlearnMarksCost(level)



#### CACostUtil:GetUnlearnCostPerLevel(level)



#### CACostUtil:GetUnlearnMoneyCost(level, abilityUnlearns, talentUnlearns, talentRank)



#### CACostUtil:GetResetCost(resetCreditType, purgeIndexTable)


TODO: Probably get rid of next reset cost?



#### CACostUtil:GetSingleAbilityResetCost()



#### CACostUtil:GetSingleTalentResetCost()



#### CACostUtil:GetSingleUnlearnCost(internalID, abilityUnlearns, talentUnlearns)



#### CACostUtil:GetWildcardIndexTableForInternalID(internalID)



#### CACostUtil:GetSpellsResetCostWildCard(unlearnList)



#### CACostUtil:GetSpellsResetCost(unlearnList)



#### CACostUtil:GetAbilityResetCost(items, indexTable)



---



## Full Resets                                --



#### CACostUtil:GetTalentResetCost(items, indexTable)



#### CACostUtil:GetAbilityAndTalentResetCost()


this method combines actual cost of talent/ability reset



#### CACostUtil:ResetCheck()
