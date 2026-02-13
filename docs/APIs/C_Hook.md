# C_Hook



**Members:** 103  •  **Functions:** 10  •  **Interface calls:** 209 (across up to 46 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `SharedXML/C_Hook.lua` line 4




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| DumpProfiling | function | C_Hook:DumpProfiling() | function C_Hook:DumpProfiling() |
| IsRegistered | function | C_Hook:IsRegistered(arg1, arg2) | function C_Hook:IsRegistered(ref, event) |
| Register | function | C_Hook:Register(arg1, arg2) | C_Hook:Register(self, "MYTHIC_PLUS_COMPLETE") |
| RegisterAllEvents | function | C_Hook:RegisterAllEvents(arg1, arg2) | C_Hook:RegisterAllEvents(self, "OnEvent") |
| RegisterBucket | function | C_Hook:RegisterBucket(arg1, arg2, arg3, arg4) | C_Hook:RegisterBucket(self, {"UNIT_SPELLCAST_STOP", "UNIT_SPELLCAST_FAILED", "UNIT_SPELLCAST_INTE... |
| SendBlizzardEvent | function | C_Hook:SendBlizzardEvent(arg1, arg2) | C_Hook:SendBlizzardEvent(unpack(data)) |
| SendEvent | function | C_Hook:SendEvent(arg1, arg2) | C_Hook:SendEvent("ENCHANTCOLLECTION_LOADED") |
| StartProfiling | function | C_Hook:StartProfiling() | function C_Hook:StartProfiling() |
| StopProfiling | function | C_Hook:StopProfiling() | function C_Hook:StopProfiling() |
| Unregister | function | C_Hook:Unregister(arg1, arg2) | C_Hook:Unregister(self) |
| allListener | table | C_Hook.allListener | if C_Hook.allListener[DevConsole] then |
| buckets | table | C_Hook.buckets | local bucket = C_Hook.buckets[ref] |
| events | table | C_Hook.events | for event in pairs(C_Hook.events) do |
| events.ADDON_LOADED | table | C_Hook.events.ADDON_LOADED |  |
| events.AREA_POI_PAYLOAD | table | C_Hook.events.AREA_POI_PAYLOAD |  |
| events.ARENA_TEAM_UPDATE | table | C_Hook.events.ARENA_TEAM_UPDATE |  |
| events.ASCENSION_BG_QUEUE_ALERT | table | C_Hook.events.ASCENSION_BG_QUEUE_ALERT |  |
| events.ASCENSION_CUSTOM_GAME_MODE_CHANGED | table | C_Hook.events.ASCENSION_CUSTOM_GAME_MODE_CHANGED |  |
| events.ASCENSION_CUSTOM_POINTS_SEASONAL_POINTS_VALUE_CHANGED | table | C_Hook.events.ASCENSION_CUSTOM_POINTS_SEASONAL_POINTS_VALUE_CHANGED |  |
| events.ASCENSION_CUSTOM_PVP_REWARD_INFO_AVAILABLE | table | C_Hook.events.ASCENSION_CUSTOM_PVP_REWARD_INFO_AVAILABLE |  |
| events.ASCENSION_CUSTOM_QUEST_REWARDED | table | C_Hook.events.ASCENSION_CUSTOM_QUEST_REWARDED |  |
| events.ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED | table | C_Hook.events.ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED |  |
| events.ASCENSION_STORE_COLLECTION_ITEM_LEARNED | table | C_Hook.events.ASCENSION_STORE_COLLECTION_ITEM_LEARNED |  |
| events.ASC_MISC | table | C_Hook.events.ASC_MISC |  |
| events.BAG_UPDATE | table | C_Hook.events.BAG_UPDATE |  |
| events.BUILD_DRAFT_PICK_PROMPT | table | C_Hook.events.BUILD_DRAFT_PICK_PROMPT |  |
| events.BUILD_DRAFT_ROLE_PROMPT | table | C_Hook.events.BUILD_DRAFT_ROLE_PROMPT |  |
| events.BUILD_DRAFT_SELECT_ROLE_RESULT | table | C_Hook.events.BUILD_DRAFT_SELECT_ROLE_RESULT |  |
| events.CHALLENGE_COMPLETED | table | C_Hook.events.CHALLENGE_COMPLETED |  |
| events.CHALLENGE_CRITERIA_COMPLETED | table | C_Hook.events.CHALLENGE_CRITERIA_COMPLETED |  |
| events.CHALLENGE_CRITERIA_FAILED | table | C_Hook.events.CHALLENGE_CRITERIA_FAILED |  |
| events.CHALLENGE_DEATH_UPDATE | table | C_Hook.events.CHALLENGE_DEATH_UPDATE |  |
| events.CHALLENGE_FAILURE_ADDED | table | C_Hook.events.CHALLENGE_FAILURE_ADDED |  |
| events.CHARACTER_ADVANCEMENT_LOADOUT_ACTIVE_PAYLOAD | table | C_Hook.events.CHARACTER_ADVANCEMENT_LOADOUT_ACTIVE_PAYLOAD |  |
| events.CHARACTER_ADVANCEMENT_LOADOUT_OWNED_PAYLOAD | table | C_Hook.events.CHARACTER_ADVANCEMENT_LOADOUT_OWNED_PAYLOAD |  |
| events.CHAT_MSG_WHISPER | table | C_Hook.events.CHAT_MSG_WHISPER |  |
| events.CLAIM_SKILL_CARD_RESULT | table | C_Hook.events.CLAIM_SKILL_CARD_RESULT |  |
| events.COMBAT_LOG_EVENT_UNFILTERED | table | C_Hook.events.COMBAT_LOG_EVENT_UNFILTERED |  |
| events.CROWD_CONTROL_ADDED | table | C_Hook.events.CROWD_CONTROL_ADDED |  |
| events.CROWD_CONTROL_REMOVED | table | C_Hook.events.CROWD_CONTROL_REMOVED |  |
| events.CROWD_CONTROL_UPDATED | table | C_Hook.events.CROWD_CONTROL_UPDATED |  |
| events.CURRENCY_DISPLAY_UPDATE | table | C_Hook.events.CURRENCY_DISPLAY_UPDATE |  |
| events.CVAR_UPDATE | table | C_Hook.events.CVAR_UPDATE |  |
| events.EDIT_BOX_MODIFIER_CHANGED | table | C_Hook.events.EDIT_BOX_MODIFIER_CHANGED |  |
| events.FRIEND_METADATA_CHANGED | table | C_Hook.events.FRIEND_METADATA_CHANGED |  |
| events.GAME_EVENT_ENDED | table | C_Hook.events.GAME_EVENT_ENDED |  |
| events.GAME_EVENT_STARTED | table | C_Hook.events.GAME_EVENT_STARTED |  |
| events.GAME_MODE_UPDATE | table | C_Hook.events.GAME_MODE_UPDATE |  |
| events.GMRESPONSE_RECEIVED | table | C_Hook.events.GMRESPONSE_RECEIVED |  |
| events.GOSSIP_CLOSED | table | C_Hook.events.GOSSIP_CLOSED |  |
| events.GOSSIP_SHOW | table | C_Hook.events.GOSSIP_SHOW |  |
| events.HONORABLE_COMBAT_ZONES_PAYLOAD | table | C_Hook.events.HONORABLE_COMBAT_ZONES_PAYLOAD |  |
| events.ITEM_PUSH | table | C_Hook.events.ITEM_PUSH |  |
| events.ITEM_USED_PAYLOAD | table | C_Hook.events.ITEM_USED_PAYLOAD |  |
| events.LFG_COMPLETION_REWARD | table | C_Hook.events.LFG_COMPLETION_REWARD |  |
| events.LFG_PROPOSAL_SHOW | table | C_Hook.events.LFG_PROPOSAL_SHOW |  |
| events.MIRROR_TIMER_START | table | C_Hook.events.MIRROR_TIMER_START |  |
| events.MYSTIC_ALTAR_CLOSED | table | C_Hook.events.MYSTIC_ALTAR_CLOSED |  |
| events.MYSTIC_ALTAR_USED | table | C_Hook.events.MYSTIC_ALTAR_USED |  |
| events.MYSTIC_ENCHANT_LEARNED | table | C_Hook.events.MYSTIC_ENCHANT_LEARNED |  |
| events.MYSTIC_ENCHANT_PROGRESS_UPDATE | table | C_Hook.events.MYSTIC_ENCHANT_PROGRESS_UPDATE |  |
| events.MYSTIC_ENCHANT_UNLOCK_PRESET_USED | table | C_Hook.events.MYSTIC_ENCHANT_UNLOCK_PRESET_USED |  |
| events.MYSTIC_SCROLL_USED | table | C_Hook.events.MYSTIC_SCROLL_USED |  |
| events.MYTHIC_PLUS_COMPLETE | table | C_Hook.events.MYTHIC_PLUS_COMPLETE |  |
| events.MYTHIC_PLUS_COUNTDOWN_STARTED | table | C_Hook.events.MYTHIC_PLUS_COUNTDOWN_STARTED |  |
| events.MYTHIC_PLUS_STARTED | table | C_Hook.events.MYTHIC_PLUS_STARTED |  |
| events.NAME_PLATE_UNIT_ADDED | table | C_Hook.events.NAME_PLATE_UNIT_ADDED |  |
| events.NAME_PLATE_UNIT_REMOVED | table | C_Hook.events.NAME_PLATE_UNIT_REMOVED |  |
| events.NPC_PVPQUEUE_ANYWHERE | table | C_Hook.events.NPC_PVPQUEUE_ANYWHERE |  |
| events.PARTY_LEADER_CHANGED | table | C_Hook.events.PARTY_LEADER_CHANGED |  |
| events.PENDING_SKILL_CARD_ADDED | table | C_Hook.events.PENDING_SKILL_CARD_ADDED |  |
| events.PENDING_SKILL_CARD_REMOVED | table | C_Hook.events.PENDING_SKILL_CARD_REMOVED |  |
| events.PETITION_VENDOR_CLOSED | table | C_Hook.events.PETITION_VENDOR_CLOSED |  |
| events.PETITION_VENDOR_SHOW | table | C_Hook.events.PETITION_VENDOR_SHOW |  |
| events.PLAYER_ENTERED_WORLD | table | C_Hook.events.PLAYER_ENTERED_WORLD |  |
| events.PLAYER_ENTERING_WORLD | table | C_Hook.events.PLAYER_ENTERING_WORLD |  |
| events.PLAYER_EQUIPMENT_CHANGED | table | C_Hook.events.PLAYER_EQUIPMENT_CHANGED |  |
| events.PLAYER_LEVEL_UP | table | C_Hook.events.PLAYER_LEVEL_UP |  |
| events.PLAYER_LOGIN | table | C_Hook.events.PLAYER_LOGIN |  |
| events.PLAYER_LOGOUT | table | C_Hook.events.PLAYER_LOGOUT |  |
| events.PLAYER_REGEN_DISABLED | table | C_Hook.events.PLAYER_REGEN_DISABLED |  |
| events.PVPQUEUE_ANYWHERE_UPDATE_AVAILABLE | table | C_Hook.events.PVPQUEUE_ANYWHERE_UPDATE_AVAILABLE |  |
| events.QUEST_ACCEPTED | table | C_Hook.events.QUEST_ACCEPTED |  |
| events.QUEST_AUTO_OFFER | table | C_Hook.events.QUEST_AUTO_OFFER |  |
| events.QUEST_LOG_UPDATE | table | C_Hook.events.QUEST_LOG_UPDATE |  |
| events.QUEST_QUERY_COMPLETE | table | C_Hook.events.QUEST_QUERY_COMPLETE |  |
| events.READY_CHECK | table | C_Hook.events.READY_CHECK |  |
| events.SEND_ACTION_BUTTONS_PAYLOAD | table | C_Hook.events.SEND_ACTION_BUTTONS_PAYLOAD |  |
| events.SET_ACTION_BUTTON_SPELL_PAYLOAD | table | C_Hook.events.SET_ACTION_BUTTON_SPELL_PAYLOAD |  |
| events.SET_SKILL_CARD_RESULT | table | C_Hook.events.SET_SKILL_CARD_RESULT |  |
| events.SKILL_CARD_AUTO_REVEALED | table | C_Hook.events.SKILL_CARD_AUTO_REVEALED |  |
| events.SKILL_CARD_COLLECTION_ITEM_USED | table | C_Hook.events.SKILL_CARD_COLLECTION_ITEM_USED |  |
| events.SPELLS_CHANGED | table | C_Hook.events.SPELLS_CHANGED |  |
| events.TAXIMAP_CLOSED | table | C_Hook.events.TAXIMAP_CLOSED |  |
| events.TRADE_SHOW | table | C_Hook.events.TRADE_SHOW |  |
| events.UNIT_AURA | table | C_Hook.events.UNIT_AURA |  |
| events.UNIT_INVENTORY_CHANGED | table | C_Hook.events.UNIT_INVENTORY_CHANGED |  |
| events.UPDATE_BATTLEFIELD_STATUS | table | C_Hook.events.UPDATE_BATTLEFIELD_STATUS |  |
| events.VARIABLES_LOADED | table | C_Hook.events.VARIABLES_LOADED |  |
| events.WORLD_MAP_UPDATE | table | C_Hook.events.WORLD_MAP_UPDATE |  |
| events.ZONE_CHANGED_NEW_AREA | table | C_Hook.events.ZONE_CHANGED_NEW_AREA |  |
| refs | table | C_Hook.refs | elseif C_Hook.refs[self] then |
| refs.TamePet | table | C_Hook.refs.TamePet |  |
