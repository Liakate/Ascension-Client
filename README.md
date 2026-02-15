# Ascension Client documentation (GitHub-friendly)

This repository combines:

1) **Interface wiki** (generated from the shipped `Interface/` package)
2) **Runtime scan results** (captured in-game and annotated)

## Start here

- [Docs index (HTML)](docs/index.html)
- [Interface overview (HTML)](docs/README.html)

## Runtime scan (HTML)

The `docs/RuntimeScan/` docs are the human-readable, GitHub-friendly write-ups of what was observed at runtime.

- [Runtime scan index (HTML)](docs/RuntimeScan/index.html)

## Bronzebeard Scan folder (HTML + raw exports)

The `Bronzebeard Scan/` folder contains the **Bronzebeard Scan exports** (HTML indexes + raw JSON exports)
so you can browse the runtime surface quickly.

Entry points:

- [Bronzebeard Scan - API index (HTML)](Bronzebeard%20Scan/index.html)
- [Bronzebeard Scan - Globals/UI objects index (HTML)](Bronzebeard%20Scan/globals_index.html)

Extra indexes:

- [Known spells (HTML)](Bronzebeard%20Scan/spells.html)
- [Known items (HTML)](Bronzebeard%20Scan/items.html)
- [Known talents (HTML)](Bronzebeard%20Scan/talents.html)
- [Known mystic enchants (HTML)](Bronzebeard%20Scan/mysticenchants.html)

Raw exports:

- [API documentation](Bronzebeard%20Scan/API_DOCUMENTATION.html)
- [Runtime objects](Bronzebeard%20Scan/API_DOCUMENTATION_RUNTIME_OBJECTS.html)
- [Global UI objects](Bronzebeard%20Scan/GLOBAL_UI_OBJECTS.html)
- [Object graph fields](Bronzebeard%20Scan/OBJECT_GRAPH_FIELDS.html)
- [Evidence index (JSON)](Bronzebeard%20Scan/EvidenceIndex.json)
- [Evidence verification report (HTML)](Bronzebeard%20Scan/EvidenceIndex_VerificationReport.html)
- [Globals index (JSON)](Bronzebeard%20Scan/GlobalsIndex.json)

> Tip: GitHub may not render local HTML reliably in the file viewer. If the HTML links don't display, download the repo
> and open the `index.html` files locally, or view them via GitHub Pages.

## Interface wiki indexes

- [docs/Events.html](docs/Events.html)
- [docs/Enums.html](docs/Enums.html)
- [docs/Templates.html](docs/Templates.html)
- [docs/JsonMessaging.html](docs/JsonMessaging.html)
- [docs/APIs/index.html](docs/APIs/index.html)
## Source archives (same as the Bronzebeard ruleset)

This repo includes the original source archives used to generate the documentation:

- `interface.zip` — the Bronzebeard **Interface** package (code-only `Interface\*` rip: FrameXML/SharedXML + bundled UI).
- `DBFiles.zip` — the Bronzebeard **DBFilesClient** content pack (DBC tables; offline content evidence).

> Note: These are the **same** `interface.zip` and `DBFiles.zip` referenced by the Bronzebeard ruleset.

## File inventory (Ascension Client.zip)

Below is the complete file list from `Ascension Client.zip` (sorted, 130 files). Git/VCS-only files like `.gitignore` are intentionally not listed.

<details>
<summary>Click to expand the full file list</summary>

```text
Bronzebeard Scan/API_DOCUMENTATION.html
Bronzebeard Scan/API_DOCUMENTATION_RUNTIME_OBJECTS.html
Bronzebeard Scan/EvidenceIndex.json
Bronzebeard Scan/EvidenceIndex_VerificationReport.html
Bronzebeard Scan/GLOBAL_UI_OBJECTS.html
Bronzebeard Scan/globals_index.html
Bronzebeard Scan/GlobalsIndex.json
Bronzebeard Scan/index.html
Bronzebeard Scan/items.html
Bronzebeard Scan/mysticenchants.html
Bronzebeard Scan/OBJECT_GRAPH_FIELDS.html
Bronzebeard Scan/spells.html
Bronzebeard Scan/talents.html
DBFiles.zip
docs/.nojekyll
docs/APIs/C_AccountInfo.html
docs/APIs/C_AddonPanel.html
docs/APIs/C_Appearance.html
docs/APIs/C_AppearanceCollection.html
docs/APIs/C_AppearanceOutfit.html
docs/APIs/C_AssetQueryService.html
docs/APIs/C_Aura.html
docs/APIs/C_BugTracker.html
docs/APIs/C_BuildCreator.html
docs/APIs/C_BuildDraft.html
docs/APIs/C_BuildEditor.html
docs/APIs/C_Cache.html
docs/APIs/C_CallboardCache.html
docs/APIs/C_Challenge.html
docs/APIs/C_CharacterAdvancement.html
docs/APIs/C_CharacterCreate.html
docs/APIs/C_Chat.html
docs/APIs/C_ClassInfo.html
docs/APIs/C_CollectorCache.html
docs/APIs/C_Comm.html
docs/APIs/C_Config.html
docs/APIs/C_ContentLoader.html
docs/APIs/C_CrowdControl.html
docs/APIs/C_CustomStore.html
docs/APIs/C_CVar.html
docs/APIs/C_Deflate.html
docs/APIs/C_DraftRewards.html
docs/APIs/C_EquipmentSet.html
docs/APIs/C_ExtraActionButton.html
docs/APIs/C_Flipbook.html
docs/APIs/C_Format.html
docs/APIs/C_GameMode.html
docs/APIs/C_GM.html
docs/APIs/C_GMTicket.html
docs/APIs/C_Gossip.html
docs/APIs/C_GroupFinder.html
docs/APIs/C_HighRisk.html
docs/APIs/C_Hook.html
docs/APIs/C_Instance.html
docs/APIs/C_InventoryState.html
docs/APIs/C_Item.html
docs/APIs/C_ItemSet.html
docs/APIs/C_Keystones.html
docs/APIs/C_LFG.html
docs/APIs/C_Logger.html
docs/APIs/C_LootLockout.html
docs/APIs/C_LoyaltyPass.html
docs/APIs/C_Manastorm.html
docs/APIs/C_Map.html
docs/APIs/C_MysticEnchant.html
docs/APIs/C_MysticEnchantPreset.html
docs/APIs/C_MythicPlus.html
docs/APIs/C_NamePlate.html
docs/APIs/C_NamePlateManager.html
docs/APIs/C_NoviceNetwork.html
docs/APIs/C_Player.html
docs/APIs/C_PlayerPoll.html
docs/APIs/C_PlayerTicket.html
docs/APIs/C_PopupQueue.html
docs/APIs/C_PrimaryStat.html
docs/APIs/C_PVP.html
docs/APIs/C_Quest.html
docs/APIs/C_QuestLog.html
docs/APIs/C_Realm.html
docs/APIs/C_RealmSelect.html
docs/APIs/C_RecoveryService.html
docs/APIs/C_Scenario.html
docs/APIs/C_Seasons.html
docs/APIs/C_Serialize.html
docs/APIs/C_SkillCard.html
docs/APIs/C_SkillCardCollection.html
docs/APIs/C_Social.html
docs/APIs/C_Spell.html
docs/APIs/C_SpellActivationOverlay.html
docs/APIs/C_Sun.html
docs/APIs/C_SuperTrack.html
docs/APIs/C_Taxi.html
docs/APIs/C_TemporalContracts.html
docs/APIs/C_Token.html
docs/APIs/C_TrackerHeader.html
docs/APIs/C_TradeSkill.html
docs/APIs/C_TrialCreator.html
docs/APIs/C_TrinityCore.html
docs/APIs/C_Tutorial.html
docs/APIs/C_UICamera.html
docs/APIs/C_VanityCollection.html
docs/APIs/C_Wildcard.html
docs/APIs/C_WildcardRewards.html
docs/APIs/C_WorldMap.html
docs/APIs/GlobalFunctions.html
docs/APIs/index.html
docs/APIs/InterfaceLuaUtilities.html
docs/Enums.html
docs/Events.html
docs/Folders/AddOns.html
docs/Folders/FrameXML.html
docs/Folders/GlueXML.html
docs/Folders/LCDXML.html
docs/Folders/LibraryXML.html
docs/Folders/SharedXML.html
docs/index.html
docs/Interface.html
docs/JsonMessaging.html
docs/README.html
docs/RuntimeScan/API_Documentation_RuntimeScan.html
docs/RuntimeScan/API_Runtime_Objects.html
docs/RuntimeScan/EvidenceIndex.json
docs/RuntimeScan/EvidenceIndex_VerificationReport.html
docs/RuntimeScan/Global_UI_Objects.html
docs/RuntimeScan/GlobalsIndex.json
docs/RuntimeScan/index.html
docs/RuntimeScan/Object_Graph_Fields.html
docs/Templates.html
interface.zip
README.md
```

</details>
