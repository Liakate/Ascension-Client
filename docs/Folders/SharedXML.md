# Interface/SharedXML



## Summary


`Interface/SharedXML` contains **shared UI templates, mixins, and utilities** used by both:


- `FrameXML` (in-game UI)
- `GlueXML` (login/realm/character screens)


This folder is also where Ascension ships some key cross-cutting systems:


- `C_Hook` (event dispatch + bucketed/throttled handlers)
- networking helpers (`C_Comm`, JSON cache helpers)
- compression/serialization helpers (`C_Deflate`, `C_Serialize`)
- compatibility stubs for missing natives on some realms/builds



## Subfolders



| Folder | Purpose | Files |
| --- | --- | --- |
| ErrorHandler | Shared error display/handling UI. | 2 |
| Scroll | Scroll box / scroll frame templates and helpers. | 9 |
| Settings | Shared settings UI framework (panels, categories, widgets). | 18 |
| TabSystem | Tabbed UI templates and mixins. | 4 |
| TypeExtensions | Shared type helpers/extensions (tables, numbers, strings). | 15 |
| Util | Shared utilities, compatibility layers, and Ascension helper namespaces (e.g., comms, deflate, timers). | 38 |



## Notable root files (examples)


- `CallbackRegistryMixin.lua` — callback registry pattern used widely in modern UI code
- `Enum.lua` — shared enums
- `Pools.lua` — object pooling patterns
- `NineSlice.*` — nine-slice textures/layouts
- `UIDropDownMenu.*` — dropdown menu implementation



SharedXML is large by design; this page documents structure and intent rather than enumerating every file.
