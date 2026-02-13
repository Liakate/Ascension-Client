# Interface/GlueXML



## Summary


`Interface/GlueXML` contains the **login / character selection / realm selection** UI (“glue screens”).  

This environment differs from in-game UI:


- Some APIs differ or are unavailable until after entering the world.
- Many scripts gate behavior behind `InGlue()` checks.
- SharedXML is still used for common mixins/templates.


Primary load list: `GlueXML.toc`.



## Subfolders



| Folder | Purpose | Files | Key files (examples) |
| --- | --- | --- | --- |
| RealmList | Realm list / realm wizard UI pieces. | 6 | Realm.lua, RealmInfo.lua, RealmList.lua, RealmList.xml, RealmListTemplates.xml, RealmTab.lua |
| Util | Glue-side utility modules used during login screens. | 1 | CharacterCreateUtil.lua |



## Notable components


- `AccountLogin.*` — login flow
- `RealmList.*` / `RealmWizard.*` — realm selection flow
- `CharacterSelect.*` / `CharacterCreate.*` — character selection/creation
- `AddonList.*` — enable/disable AddOns at login
- `GlueOverwrites.lua` — glue-specific overrides/patches



## Ascension-specific behavior


Ascension commonly uses the glue screens to:


- Present custom realm selection workflows
- Show patch/extension error handling
- Gate features behind config or account state
