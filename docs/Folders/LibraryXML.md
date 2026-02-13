# Interface/LibraryXML



## Summary


`Interface/LibraryXML` ships **third-party Lua libraries** bundled with the client/UI.


These libraries are primarily used by:


- Shipped Ascension AddOns
- Shipped Blizzard_ AddOns
- In some cases, GlueXML / FrameXML scripts



## Included libraries (folder list)


- `AceAddon-3.0`
- `AceComm-3.0`
- `AceConfig-3.0`
- `AceConsole-3.0`
- `AceDB-3.0`
- `AceDBOptions-3.0`
- `AceEvent-3.0`
- `AceGUI-3.0`
- `AceGUI-3.0-SharedMediaWidgets`
- `AceHook-3.0`
- `AceLocale-3.0`
- `AceSerializer-3.0`
- `AceTimer-3.0`
- `Astrolabe-0.4`
- `CallbackHandler-1.0`
- `LibAboutPanel`
- `LibAceConfigHelper`
- `LibActionButton-1.0`
- `LibAscensionConfig`
- `LibBetterBlizzOptions-1.0`
- `LibCompress`
- `LibCustomGlow-1.0`
- `LibDBIcon-1.0`
- `LibDataBroker-1.1`
- `LibDeflate`
- `LibGetFrame-1.0`
- `LibGraph-2.0`
- `LibGroupTalents-1.0`
- `LibKeyBound-1.0`
- `LibRangeCheck-2.0`
- `LibSerialize`
- `LibSharedMedia-3.0`
- `LibSpellRange-1.0`
- `LibStatLogic-1.1`
- `LibTalentQuery-1.0`
- `LibTranslit-1.0`
- `LibWindow-1.1`
- `NickTag-1.0`



## Common patterns



### LibStub / embedded libs


Many libraries use `LibStub` to register versions. An AddOn can either:


- Embed the library inside its own folder (and load it first in the `.toc`), or
- Depend on the shipped copy in `LibraryXML` (if the client loads it before your AddOn).



### Ace3 suite


Ace3 libraries provide common AddOn infrastructure:


- addon/module system (AceAddon)
- saved variables (AceDB)
- configuration UIs (AceConfig, AceGUI)
- comms (AceComm)
- events (AceEvent), timers (AceTimer), hooks (AceHook)



### Compression & serialization


Ascension also ships deflate + serialization libraries:


- `LibDeflate`
- `LibSerialize`
- `LibCompress`


These are often used to transport structured data efficiently (e.g., via addon messages).
