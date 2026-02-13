# Global functions (Ascension)


These functions are exposed globally (not under a `C_*` namespace) according to the API surface scan.



## AscensionChallenges_LoadUI



### Syntax




```text
AscensionChallenges_LoadUI
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example


- No call site found in the shipped Interface Lua (may be glue-only, server-driven, or for external AddOns).



## AscensionHelpUI_LoadUI



### Syntax




```text
AscensionHelpUI_LoadUI
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example (from Interface)




```text
AscensionHelpUI_LoadUI
()
```



*Seen in*: `AddOns/Ascension_PTRFeedback/PTRFeedbackMixin.lua` line 17.



## AscensionInspectFrame_LoadUI



### Syntax




```text
AscensionInspectFrame_LoadUI
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example


- No call site found in the shipped Interface Lua (may be glue-only, server-driven, or for external AddOns).



## Ascension_GetArenaBracketCutoffs



### Syntax




```text
Ascension_GetArenaBracketCutoffs
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example (from Interface)




```text
tierInfo
[
i
].
rating
 
=
 
select
(
i
 
-
 
1
,
 
Ascension_GetArenaBracketCutoffs
())
 
or
 
tierInfo
[
i
].
rating
```



*Seen in*: `FrameXML/Util/C_PVP.lua` line 160.



## Ascension_GetArenaRewardInfo



### Syntax




```text
Ascension_GetArenaRewardInfo
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example (from Interface)




```text
local
 
currAP
,
 
maxAP
 
=
 
Ascension_GetArenaRewardInfo
()
```



*Seen in*: `AddOns/AscensionUI/Gossips/CallBoard.lua` line 316.



## Ascension_QueryArenaRewardInfo



### Syntax




```text
Ascension_QueryArenaRewardInfo
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example (from Interface)




```text
Ascension_QueryArenaRewardInfo
()
```



*Seen in*: `FrameXML/Ascension_LFG/Ascension_LFG.lua` line 36.



## CA_GetCreditAmount



### Syntax




```text
CA_GetCreditAmount
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example (from Interface)




```text
abilityUnlearns
 
=
 
abilityUnlearns
 
or
 
CA_GetCreditAmount
(
Enum
.
ResetCreditType
.
AbilityUnlearn
)
```



*Seen in*: `FrameXML/Util/CharacterAdvancementCostUtil.lua` line 70.



## CA_IsSpellKnown



### Syntax




```text
CA_IsSpellKnown
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example (from Interface)




```text
local
 
canLearn
 
=
 
maxSpellID
 
and
 
not
 
IsSpellKnown
(
maxSpellID
)
 
and
 
not
 
CA_IsSpellKnown
(
maxSpellID
)
```



*Seen in*: `AddOns/Ascension_CharacterAdvancementSeason9/Templates/CASpellButton.lua` line 124.



## Custom_HandleTerrainClick



### Syntax




```text
Custom_HandleTerrainClick
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example


- No call site found in the shipped Interface Lua (may be glue-only, server-driven, or for external AddOns).



## Custom_HandleTerrainClick_PlayerPos



### Syntax




```text
Custom_HandleTerrainClick_PlayerPos
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example


- No call site found in the shipped Interface Lua (may be glue-only, server-driven, or for external AddOns).



## Custom_HandleTerrainClick_TargetPos



### Syntax




```text
Custom_HandleTerrainClick_TargetPos
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example


- No call site found in the shipped Interface Lua (may be glue-only, server-driven, or for external AddOns).



## Custom_SendAutoQuestAccept



### Syntax




```text
Custom_SendAutoQuestAccept
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example


- No call site found in the shipped Interface Lua (may be glue-only, server-driven, or for external AddOns).



## Draft_LoadUI



### Syntax




```text
Draft_LoadUI
(...)
```




### Arguments / returns


- Unknown (native) unless otherwise observed.



### Example (from Interface)




```text
Draft_LoadUI
()
```



*Seen in*: `FrameXML/Util/DraftUtil.lua` line 140.
