# API Documentation v2 - runtime objects

- generated_at: `2026-02-15T08:13:21Z`
- bbscan_version: `0.3.92`
- client_build: `12340`

| API | kind | op | argc | argcSrc | retc | conf | runtime | iface | trace | probe | examples | hint_keys |
|---|---:|:--:|---:|:--:|---:|:--:|:--:|:--:|---:|:--:|---|---|
| `C_AccountInfo` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AddonPanel` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AddonPanel.addons` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AddonPanel.addonsByIndex` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AddonPanel.addonsByName` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AddonPanel.saveFile` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Appearance` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AppearanceCollection` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AppearanceOutfit` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_AssetQueryService` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Aura` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Aura.UnitAura` | unknown | . | 2 |  |  |  |  | Y | 0 |  |  |  |
| `C_BugTracker` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_BuildCreator` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_BuildDraft` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_BuildEditor` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.SpellActivationOverlayAlpha` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.camerafov` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.lootToastMaximum` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.lossOfControlScale` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.nameplateAngle` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.nameplateDistance` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.nameplateHeight` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.nameplateOverlapV` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.nameplateVerticalOffset` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.nameplateWidth` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.tabTargetAngle` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Maximums.tabTargetRange` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.SpellActivationOverlayAlpha` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.camerafov` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.lootToastMaximum` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.lossOfControlScale` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.nameplateAngle` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.nameplateDistance` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.nameplateHeight` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.nameplateOverlapV` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.nameplateVerticalOffset` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.nameplateWidth` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.tabTargetAngle` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CVar.Minimums.tabTargetRange` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Cache` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Cache.LastStatQuery` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Cache.Queried` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CallboardCache` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Challenge` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CharacterAdvancement.IsTraitID` | unknown | . | 1 |  |  |  |  | Y | 0 |  |  |  |
| `C_CharacterCreate` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Chat` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ClassInfo` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CollectorCache` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm` | frame |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.HardThrottleStart` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.LastAvailableUpdate` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.Priority` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.Priority.BULK` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.Priority.NORMAL` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.Priority.URGENT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.SetAttribute` | unknown | : | 2 |  |  |  | Y | Y | 0 |  |  |  |
| `C_Comm.available` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Comm.elapsed` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Config` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ContentLoader` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ContentLoader.Runner` | frame |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CrowdControl` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CrowdControl.Active` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CrowdControl.HasControl` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_CustomStore` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Deflate` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Deflate.internals` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Deflate.internals._6bit_to_byte` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Deflate.internals._byte_to_6bit_char` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_DraftRewards` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_EquipmentSet` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ExtraActionButton` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Flipbook` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Flipbook.Updater` | frame |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Flipbook.Updater.activeFlipbooks` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Format` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GM` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GMTicket` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GameMode` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GameMode.Event` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GameMode.Event.OnGameModeChanged` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GameMode.callbackTables` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._hookItem` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._hookItem.hide` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._hookItem.show` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._hookNPC` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._hookNPC.hide` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._hookNPC.show` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._redirectItem` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._redirectItem.hide` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._redirectItem.show` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._redirectNPC` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._redirectNPC.hide` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Gossip._redirectNPC.show` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_GroupFinder` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_HighRisk` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.allListener` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.buckets` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ADDON_LOADED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.AREA_POI_PAYLOAD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ARENA_TEAM_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASCENSION_BG_QUEUE_ALERT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASCENSION_CUSTOM_GAME_MODE_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASCENSION_CUSTOM_POINTS_SEASONAL_POINTS_VALUE_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASCENSION_CUSTOM_PVP_REWARD_INFO_AVAILABLE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASCENSION_CUSTOM_QUEST_REWARDED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASCENSION_STORE_COLLECTION_ITEM_LEARNED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ASC_MISC` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.BAG_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.BUILD_DRAFT_PICK_PROMPT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.BUILD_DRAFT_ROLE_PROMPT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.BUILD_DRAFT_SELECT_ROLE_RESULT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHALLENGE_COMPLETED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHALLENGE_CRITERIA_COMPLETED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHALLENGE_CRITERIA_FAILED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHALLENGE_DEATH_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHALLENGE_FAILURE_ADDED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHARACTER_ADVANCEMENT_LOADOUT_ACTIVE_PAYLOAD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHARACTER_ADVANCEMENT_LOADOUT_OWNED_PAYLOAD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CHAT_MSG_WHISPER` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CLAIM_SKILL_CARD_RESULT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.COMBAT_LOG_EVENT_UNFILTERED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CROWD_CONTROL_ADDED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CROWD_CONTROL_REMOVED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CROWD_CONTROL_UPDATED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CURRENCY_DISPLAY_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.CVAR_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.EDIT_BOX_MODIFIER_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.FRIEND_METADATA_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.GAME_EVENT_ENDED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.GAME_EVENT_STARTED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.GAME_MODE_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.GMRESPONSE_RECEIVED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.GOSSIP_CLOSED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.GOSSIP_SHOW` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.HONORABLE_COMBAT_ZONES_PAYLOAD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ITEM_PUSH` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ITEM_USED_PAYLOAD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.LFG_COMPLETION_REWARD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.LFG_PROPOSAL_SHOW` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MIRROR_TIMER_START` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYSTIC_ALTAR_CLOSED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYSTIC_ALTAR_USED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYSTIC_ENCHANT_LEARNED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYSTIC_ENCHANT_PROGRESS_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYSTIC_ENCHANT_UNLOCK_PRESET_USED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYSTIC_SCROLL_USED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYTHIC_PLUS_COMPLETE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYTHIC_PLUS_COUNTDOWN_STARTED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.MYTHIC_PLUS_STARTED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.NPC_PVPQUEUE_ANYWHERE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PARTY_LEADER_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PENDING_SKILL_CARD_ADDED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PENDING_SKILL_CARD_REMOVED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PETITION_VENDOR_CLOSED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PETITION_VENDOR_SHOW` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PLAYER_ENTERED_WORLD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PLAYER_ENTERING_WORLD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PLAYER_EQUIPMENT_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PLAYER_LEVEL_UP` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PLAYER_LOGIN` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PLAYER_LOGOUT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PLAYER_REGEN_DISABLED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.PVPQUEUE_ANYWHERE_UPDATE_AVAILABLE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.QUEST_ACCEPTED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.QUEST_AUTO_OFFER` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.QUEST_LOG_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.QUEST_QUERY_COMPLETE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.READY_CHECK` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.SEND_ACTION_BUTTONS_PAYLOAD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.SET_ACTION_BUTTON_SPELL_PAYLOAD` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.SET_SKILL_CARD_RESULT` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.SKILL_CARD_AUTO_REVEALED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.SKILL_CARD_COLLECTION_ITEM_USED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.SPELLS_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.TAXIMAP_CLOSED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.TRADE_SHOW` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.UNIT_AURA` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.UNIT_INVENTORY_CHANGED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.UPDATE_BATTLEFIELD_STATUS` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.VARIABLES_LOADED` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.WORLD_MAP_UPDATE` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.events.ZONE_CHANGED_NEW_AREA` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.refs` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Hook.refs.TamePet` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Instance` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_InventoryState` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_InventoryState.Equipped` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_InventoryState.Inventory` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_InventoryState.NewItems` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_InventoryState.RecentPush` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Item` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Item.lastUsedItem` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Item.lastUsedItem.time` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ItemSet` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_ItemSet.GetItemSetName` | unknown | . | 1 |  | 1 |  |  | Y | 0 |  |  |  |
| `C_Keystones` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LFG` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LFG.RequiredExpansion` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LFG.RequiredRandomItemLevel` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LFG.RequiredRandomPVEPower` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LFG.RequiresGameEvent` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LFG.ScalingDungeons` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Logger` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LootLockout` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_LoyaltyPass` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Manastorm` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Map` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_MysticEnchant` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_MysticEnchantPreset` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_MythicPlus` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_NamePlate` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_NamePlateManager` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_NoviceNetwork` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PVP` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PVP.InHighRisk` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Player` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Player.currentLevel` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PlayerPoll` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PlayerTicket` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PopupQueue` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PopupQueue.Achievements` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PopupQueue.Frame` | frame |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PopupQueue.Queue` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PrimaryStat` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PrimaryStat.AuraToID` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PrimaryStat.Auras` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PrimaryStat.SpellToID` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_PrimaryStat.internalIds` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.PortraitData` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.activeQuests` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.completedQuests` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.felforgedChallenges` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.felforgedChallenges.<truncated>` | note |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.isQuerying` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.lastQuery` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.queryIds` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.titles` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Quest.turnedInQuests` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_QuestLog` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Realm` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_RealmMerge.GetAvailableOptions` | unknown | . |  |  | 1 |  |  |  | 0 |  |  |  |
| `C_RealmMerge.GetTargetRealm` | unknown | . |  |  | 1 |  |  |  | 0 |  |  |  |
| `C_RealmMerge.IsMergeAvailable` | unknown | . |  |  |  |  |  |  | 0 |  |  |  |
| `C_RealmMerge.NeedsSetTargetRealm` | unknown | . |  |  |  |  |  |  | 0 |  |  |  |
| `C_RealmMerge.SetTargetRealm` | unknown | . | 1 |  |  |  |  |  | 0 |  |  |  |
| `C_RealmSelect` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_RecoveryService` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Scenario` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Scenario.GetScenarioInfo` | unknown | . |  |  | 3 |  |  | Y | 0 |  |  |  |
| `C_Serialize` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Serialize.DeserializeCompressForPrint` | unknown | : | 1 |  | 2 |  |  | Y | 0 |  |  |  |
| `C_SkillCard` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SkillCardCollection` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Social` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.AutoPlaceIgnored` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Alchemy` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Ambush` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Auto Attack` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Backstab` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Basic Campfire` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Beast Slaying` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Berserking` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Block` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Bow Specialization` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Cooking` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Crimson Tempest` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Crippling Poison` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Da Voodoo Shuffle` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Disenchant` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Dismantle` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Dodge` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Dual Wield` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Enchanting` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Evasion` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Eviscerate` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Expose Armor` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Feint` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Find Herbs` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Find Minerals` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Find Trees` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.First Aid` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Fishing` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.For the Horde!` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Garrote` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Gouge` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.High-Risk (PvP)` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Instant Poison` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Kick` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Leatherworking` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Mercenary for Hire!` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Parry` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Pick Lock` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Pick Pocket` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.PvE Mode` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Regeneration` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Resilient Constitution` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Rupture` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Sap` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Shoot` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Sinister Strike` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Skinning` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Slice and Dice` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Smelting` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Specialization I` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Specialization II` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Specialization III` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Sprint` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Stealth` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Throw` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Throwing Specialization` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.War Mode (PvP)` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Wildcard Flying Mount` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Wildcard Mount` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Spell.knownSpellNames.Woodcutting` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SpellActivationOverlay` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Sun` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_SuperTrack` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Taxi` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TemporalContracts` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Timer` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Timer.After` | unknown | . | 2 |  |  |  | Y | Y | 0 |  |  |  |
| `C_Timer.NewTicker` | unknown | . | 3 |  | 1 |  | Y | Y | 0 |  |  |  |
| `C_Token` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.Alliance` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.Alliance.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCompleted` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCompleted.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCompleted.subTextY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCompleted.titleY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaFailed` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaFailed.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaFailed.subTextY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaFailed.titleY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaSuccess` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaSuccess.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaSuccess.subTextY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeCriteriaSuccess.titleY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeDeath` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeDeath.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeDeath.subTextY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeDeath.titleY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeFailed` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeFailed.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeFailed.subTextY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeFailed.titleY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeRedemption` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeRedemption.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeRedemption.subTextY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.ChallengeRedemption.titleY` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.Horde` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrackerHeader.Horde.Banner` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TradeSkill` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrialCreator` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrinityCore` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrinityCore.index` | field |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_TrinityCore.listeningFor` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Tutorial` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_UICamera` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_VanityCollection` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_Wildcard` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_WildcardRewards` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
| `C_WorldMap` | table |  |  |  |  |  | Y |  | 0 |  |  |  |
