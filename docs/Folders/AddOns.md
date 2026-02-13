# Interface/AddOns



## Summary


`Interface/AddOns` contains packaged AddOns loaded by the client’s AddOn loader.  

Each AddOn folder typically contains:


- `<AddonName>.toc` — metadata + file load list
- Lua/XML files listed in the `.toc`
- Optional assets (textures, fonts, etc.)



## Key mechanics



### .toc metadata (common fields)


- `## Interface:` client interface number this AddOn targets (here typically `30300`)
- `## Title:` display name
- `## Notes:` short description
- `## Dependencies:` hard dependencies that must load first
- `## OptionalDeps:` optional dependencies (loaded first if present)
- `## LoadOnDemand:` if `1`, the AddOn is not loaded at login and must be loaded later



### Load order


- Dependencies load before dependents.
- Non-LoadOnDemand AddOns load at login.
- LoadOnDemand AddOns can be loaded by UI code or by the user opening a feature panel.



## Shipped AddOn catalog (from .toc )



| Folder | TitlePlain | LoadOnDemand | Dependencies | OptionalDeps | Version |
| --- | --- | --- | --- | --- | --- |
| AscensionResources | Ascension Resources For Custom UI |  |  |  |  |
| AscensionUI | Ascension UI |  | Ascension_Collections |  |  |
| Ascension_AddonPanel | Ascension Addon Panel | 1 |  |  | 1.0.0 |
| Ascension_AppearanceUI | Ascension Appearance UI | 1 | Ascension_Collections |  | 1.0.0 |
| Ascension_BuildCreator | Ascension Build Creator | 1 |  |  | 1.0 |
| Ascension_ChallengesUI | Ascension Challenges UI | 1 |  |  | 1.0.0 |
| Ascension_CharacterAdvancement | Ascension Character Advancement | 1 | Ascension_Collections |  | 1.0.0 |
| Ascension_CharacterAdvancementSeason9 | Ascension Character Advancement | 1 | Ascension_Collections |  | 1.0.0 |
| Ascension_CoATalents | Ascension CoA Talents | 1 | Ascension TalentUI, Ascension Collections |  | 1.0.0 |
| Ascension_Collections | Ascension Collections | 1 |  |  | 1.0.0 |
| Ascension_CompactRaidFrames | Ascension Compact Raid Frames | 0 |  |  | 1.0.0 |
| Ascension_Draft | Ascension Draft UI | 1 | AscensionUI |  | 1.0.0 |
| Ascension_EnchantCollection | Ascension Enchant Collection | 1 | Ascension_Collections, AscensionUI |  | 1.0.0 |
| Ascension_ForcedPrimaryStat | Ascension Forced Primary Stat | 1 |  |  | 1.0.0 |
| Ascension_HelpUI | Ascension Help UI | 1 |  |  | 1.0.0 |
| Ascension_InspectUI | Ascension Inspect UI | 1 |  |  | 1.0.0 |
| Ascension_Manastorm | Ascension Manastorm | 1 |  |  | 1.0.0 |
| Ascension_MythicPlus | Ascension Mythic Plus | 1 |  |  | 1.0.0 |
| Ascension_NamePlates | Ascension Ascension NamePlates | 1 |  |  | 1.0 |
| Ascension_NewPlayerExperience | Ascension New Player Experience | 1 |  |  | 1.0 |
| Ascension_PTRFeedback | Ascension PTR Feedback |  |  |  | 1.0.0 |
| Ascension_PathToAscension | Ascension Path to Ascension | 1 |  |  | 1.0.0 |
| Ascension_Poll | Ascension Poll | 1 |  |  | 1.0.0 |
| Ascension_RandomModeShared | Ascension Random Mode Shared | 1 |  |  | 1.0.0 |
| Ascension_RotationStudio |  |  |  |  |  |
| Ascension_SeasonCollection | Ascension Seasonal UI | 1 |  |  | 1.0.0 |
| Ascension_SkillCards | Ascension Skill Cards | 1 | Ascension_Collections |  | 1.0.0 |
| Ascension_TalentUI | Ascension Talent UI |  |  |  | 1.0.0 |
| Ascension_TicketUI | Ascension Ticket UI | 1 |  |  | 1.0.0 |
| Ascension_UIDevelopmentTools | Ascension UI Development Tools | 1 |  |  | 1.1.0 |
| Ascension_Warmode | Ascension War Mode | 1 |  |  | 1.0.0 |
| Ascension_WarmodeLegacy | Ascension War Mode Legacy | 1 |  |  | 1.0.0 |
| Ascension_WildCard | Ascension WildCard | 1 | AscensionUI, Ascension_Collections |  | 1.0.0 |
| BagSearch | Bag Search |  |  |  |  |
| BagSort | Bag Sort |  |  |  |  |
| Blizzard_AchievementUI | Blizzard_AchievementUI | 1 |  |  | 1.0 |
| Blizzard_ArenaUI | Blizzard Arena UI | 1 |  |  |  |
| Blizzard_AuctionUI | Blizzard Auction UI | 1 |  |  |  |
| Blizzard_BarbershopUI | Blizzard Barber Shop UI | 1 |  |  | 1.0 |
| Blizzard_BattlefieldMinimap | Blizzard Battlefield Minimap | 1 |  |  |  |
| Blizzard_BindingUI | Blizzard Key Binding UI | 1 |  |  |  |
| Blizzard_Calendar | Blizzard Calendar | 1 |  |  |  |
| Blizzard_CombatLog | Blizzard CombatLog | 1 |  |  |  |
| Blizzard_CombatText | Blizzard CombatText | 1 |  |  |  |
| Blizzard_DebugTools | Blizzard UI Debug Tools | 1 |  |  | 1.0 |
| Blizzard_GMChatUI | Blizzard_GMChatUI | 1 |  |  |  |
| Blizzard_GMSurveyUI | Blizzard GM Survey UI | 1 |  |  |  |
| Blizzard_GlyphUI | Blizzard Glyph UI | 1 |  |  | 1.0 |
| Blizzard_GuildBankUI | Blizzard Guild Bank UI | 1 |  |  |  |
| Blizzard_InspectUI | Blizzard Inspect UI | 1 |  |  |  |
| Blizzard_ItemSocketingUI | Blizzard Item Socketing UI | 1 |  |  |  |
| Blizzard_MacroUI | Blizzard Macro UI | 1 |  |  |  |
| Blizzard_RaidUI | Blizzard Raid UI | 1 |  |  |  |
| Blizzard_TalentUI | Blizzard Talent UI | 1 |  |  |  |
| Blizzard_TimeManager | Blizzard Time Manager | 1 |  |  |  |
| Blizzard_TokenUI | Blizzard_TokenUI |  |  |  |  |
| Blizzard_TradeSkillUI | Blizzard Trade Skill UI | 1 |  |  |  |
| Blizzard_TrainerUI | Blizzard Trainer UI | 1 |  |  |  |
| Blizzard_VehicleUI | Blizzard_VehicleUI |  |  |  |  |
| Postal | Postal |  |  | Ace3, !BlizzBugsSuck, !ClassColors | 3.5.1 |



Titles were de-colored (WoW color codes stripped) for readability.
