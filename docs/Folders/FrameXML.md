# Interface/FrameXML



## Summary


`Interface/FrameXML` is the **in-game UI** (loaded after login) and contains:


- Core Blizzard-era UI frames and templates (action bars, character frame, chat, tooltips, etc.)
- Ascension additions (folders prefixed `Ascension_...`)
- Utility modules (notably `FrameXML/Util/`)


The main load list is `FrameXML.toc`, which enumerates the Lua/XML files loaded for the in-game UI.



## Subfolders



| Folder | Purpose | Files | Key files (examples) |
| --- | --- | --- | --- |
| AddonCompat | Compatibility shims for popular third-party AddOns. | 4 | AddonCompat.lua, AddonCompat.xml, ArkInventory.lua, ElvUI.lua |
| Ascension_BuildDraft | UI for Ascension 'build draft' features (draft/selection panels). | 6 | Ascension BuildDraft.lua, Ascension BuildDraft.xml, BuildDraftArrowMixin.lua, BuildDraftCardMixin.lua, BuildDraftRole... |
| Ascension_CharacterFrame | Ascension extensions/overrides to the character frame. | 26 | CharacterFrame.lua, CharacterFrame.xml |
| Ascension_CoAResources | Resource displays for Conquest of Azeroth (CoA) archetypes and custom resources. | 21 | Ascension BarbarianResource.lua, Ascension ChronomancerResource.lua, Ascension CoAMultiCast.lua, Ascension CoAMultiCa... |
| Ascension_CustomResources | Framework + templates for custom resource bars/segments. | 4 | Ascension_CustomResources.xml, CustomResourceContainer.lua, CustomResourceDefinitions.lua, CustomResourceSegment.lua |
| Ascension_DebugTools | Ascension-specific debug and developer utilities. | 4 | Ascension_DebugTools.xml, CommandHyperlinks.lua, SoundKitBrowser.lua, SoundKitBrowser.xml |
| Ascension_LFG | Ascension group finder / LFG UI extensions. | 10 | Ascension LFG.lua, Ascension LFG.xml, Ascension PVE.lua, Ascension PVE.xml, Ascension PVP.lua, Ascension PVP.xml, Asc... |
| Ascension_LoseControl | Crowd control / loss-of-control UI elements (timers, alerts). | 2 | Ascension LoseControl.lua, Ascension LoseControl.xml |
| Ascension_MythicalBoons | UI for Mythical Boons system. | 3 | Ascension MythicalBoons.lua, Ascension MythicalBoons.xml, DynamicRadialMenu.lua |
| Ascension_POI | Points-of-interest / world map POI overlays and related payload handling. | 8 | MapPoiPin.lua, PoiTemplates.xml, StaticPOIs.xml |
| Ascension_Spellbook | Ascension spellbook extensions (classless abilities, filters). | 3 | Ascension ProfessionBook.lua, Ascension Spellbook.lua, Ascension_Spellbook.xml |
| Ascension_TrackerHeader | Quest/objective tracker header customization. | 2 | Ascension TrackerHeader.lua, Ascension TrackerHeader.xml |
| CharacterAdvancement | Character Advancement (CA) UI and helpers (talents/spells progression). | 7 | CAConnectionBaseMixin.lua, CAGateBaseMixin.lua, CALineConnectionMixin.lua, CATalentBaseMixin.lua, CATalentChoiceBaseM... |
| Data | Client-side data tables used by Ascension UI (IDs, enums, constants). | 10 | C_ContentLoader.lua, CharacterAdvancement.lua, CrowdControl.lua, HandOfFateQuests.lua, Items.lua, LiveUpdate.lua, Map... |
| Notifications | Toast/alert notification systems used by Ascension UI. | 5 | NotificationsTemplates.xml, ToastContainer.lua, ToastContainer.xml, ToastMixin.lua, ToastNotificationSystem.lua |
| Objects | Reusable UI object classes/mixins (buttons, list items, etc.). | 7 | AsyncCallbackHandler.lua, Creature.lua, GameObject.lua, Item.lua, ItemLocation.lua, Quest.lua, Spell.lua |
| Scenario | Scenario UI (objective tracker / scenario frames). | 4 | ScenarioObjectiveTracker.lua, ScenarioObjectiveTracker.xml, ScenarioTemplates.lua, ScenarioTemplates.xml |
| Settings | Settings UI framework (panels, categories, toggles). | 3 | InterfaceOptions.lua, InterfaceOptionsFrame.lua, InterfaceOptionsFrame.xml |
| Util | Utility modules used across FrameXML (helpers, wrappers, utilities). | 56 | ActionBarUtil.lua, AppearanceUtil.lua, AuraUtil.lua, BindingUtil.lua, BuildCreatorUtil.lua, C Cache.lua, C CrowdContr... |



## Notes for AddOn authors



### Secure/protected UI & combat lockdown


Many FrameXML elements use secure templates (action buttons, unit frames, secure state drivers).  

Do not change protected attributes or secure handler state in combat; guard with `InCombatLockdown()`.



### Ascension additions


Ascension ships extra systems (builds, CA, Mystic Enchants, seasonal features, etc.). Most of those are implemented as:


- Extra `Ascension_...` modules in FrameXML and AddOns
- Native `C_*` namespaces exposed by the client (documented in `APIs/`)
