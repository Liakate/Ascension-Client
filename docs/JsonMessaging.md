# JSON messaging index


This page indexes JSON messaging usage in the shipped Interface.

- **Outgoing**: `SendJsonMessage("CATEGORY", jsonString[, priority])` call sites.
- **Incoming update pattern**: handled by `C_Hook` using sub-events that match `ASCENSION_CUSTOM_JSON_(.*)_UPDATE`.



## Outgoing categories (string literal)

**Categories found:** 4



| Category | Call sites |
| --- | --- |
| BUILD_CREATOR_DATA_REQUEST | Interface/FrameXML/Ascension_BuildDraft/Ascension_BuildDraft.lua @ 40 |
| CHARACTER_ADVANCEMENT_LOADOUT_ACTIVATE_REQUEST | Interface/FrameXML/Util/TalentLoadoutUtil.lua @ 18, 24 |
| CHARACTER_ADVANCEMENT_LOADOUT_SET_NAME_REQUEST | Interface/FrameXML/Util/TalentLoadoutUtil.lua @ 44, 61 |
| STATISTIC_QUERY_REQUEST | Interface/FrameXML/Util/C_Cache.lua @ 26, 39 |




## Outgoing categories (dynamic)

These calls pass a variable/expression as the first argument instead of a string literal.



| Category expression | Call sites |
| --- | --- |
| category | Interface/SharedXML/Util/C_Comm.lua @ 83, 106, 114 |
| self:GetAttribute("category") | Interface/SharedXML/Util/C_Comm.lua @ 102 |




## Incoming update events

The Interface does not hard-code specific update event names. Instead, the hook system recognizes update sub-events by pattern:


```text
ASCENSION_CUSTOM_JSON_(.*)_UPDATE
```

When a matching sub-event is received, the category portion is extracted and used to read cached JSON payload data:


```text
HasJsonCacheData(category, id)
GetJsonCacheData(category, id)
```

**Handler locations:**

- `Interface/FrameXML/Data/LiveUpdate.lua` @ 88
- `Interface/SharedXML/C_Hook.lua` @ 130
- `Interface/SharedXML/C_Hook.lua` @ 132


In this client build, sub-events are processed under `COMMENTATOR_SKIRMISH_QUEUE_REQUEST` (see `SharedXML/C_Hook.lua`).




## Direct JSON cache API calls (string literal)



### HasJsonCacheData("CATEGORY", ...)

- `MISC_PLAYER_DATA_PAYLOAD` — Interface/FrameXML/Util/C_NoviceNetwork.lua @ 8



### GetJsonCacheData("CATEGORY", ...)

- `CHARACTER_ADVANCEMENT_LOADOUT_ACTIVE_PAYLOAD` — Interface/FrameXML/Util/TalentLoadoutUtil.lua @ 121
- `CHARACTER_ADVANCEMENT_LOADOUT_OWNED_PAYLOAD` — Interface/FrameXML/Util/TalentLoadoutUtil.lua @ 120
- `CHECKPOINTS_ENABLED_PAYLOAD` — Interface/FrameXML/Util/C_Instance.lua @ 56
- `MISC_PLAYER_DATA_PAYLOAD` — Interface/FrameXML/Util/C_NoviceNetwork.lua @ 9



Build time: 2026-02-13 22:21:51.
