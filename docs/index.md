# Interface (Ascension client) — extracted from interface.zip



**Interface number:** 30300 (WotLK 3.3.5-era client with Ascension patches)  

**Source archive SHA-1:** `0ad56577357a0ba4c63ed6e80390d611e0a6ff81`  

**Generated:** 2026-02-13 (Europe/Amsterdam)




## What this is


This document set describes the **Ascension client UI package** shipped as `Interface/`:


- Blizzard-era UI (FrameXML / GlueXML) with Ascension additions and overrides.
- Shipped AddOns (Ascension and Blizzard_ modules).
- Shared libraries and utility code.


It is written in a “wiki-style API reference” format (syntax → arguments → returns → examples), similar to the documentation style used by Warcraft wiki.



## Top-level folders



| Folder | Purpose | Files |
| --- | --- | --- |
| Interface/AddOns | AddOn packages loaded by the in-game AddOn loader (per .toc ) | 532 |
| Interface/FrameXML | In-game UI (“logged in”) core frames, templates, utilities | 539 |
| Interface/GlueXML | Login / character select / realm list UI (“glue screens”) | 94 |
| Interface/LCDXML | LCD device layouts (e.g., Logitech-style LCD panels) | 2 |
| Interface/LibraryXML | Shipped libraries (Ace3, LibDeflate, LibSharedMedia, etc.) | 141 |
| Interface/SharedXML | Shared UI templates + utility mixins used by both GlueXML & FrameXML | 134 |



## Loading model (high level)



### 1) AddOns


- The game loads `Interface/AddOns/<AddonName>/<AddonName>.toc`.
- `.toc` lists files to load (Lua and XML).
- AddOns can be **LoadOnDemand** and loaded at runtime (e.g., when opening a panel).



### 2) GlueXML (login screens)


- Loaded before you enter the world.
- Uses its own global frames and scripts (e.g., realm list, character select).
- Uses a subset of SharedXML + its own utility layer (see `Interface/GlueXML/Util`).



### 3) FrameXML (in-game UI)


- Loaded after you enter the world and `UIParent` is created.
- The file `Interface/FrameXML/FrameXML.toc` is the primary in-game load list.



### 4) SharedXML


- Shared templates and mixins used by both GlueXML and FrameXML.
- Ascension also ships several “client-side helper” namespaces here (notably `C_Hook`, `C_Comm`, serializers/deflate, and compatibility stubs).



## What counts as “Ascension APIs”


In this documentation set, **Ascension APIs** includes:


- **Native client APIs** exposed to Lua (mostly `C_*` namespaces and a small list of global functions).
- **Lua-defined client namespaces** shipped in the UI (e.g., `C_Hook`, `C_Comm`, `C_Keystones`, etc.).
- **Utility modules** shipped with the client UI that are intended to be used by UI code and AddOns (e.g., `ChallengeUtil`, `GameEventUtil`, `MysticEnchantManagerUtil`, ...).


See: [`APIs/index.md`](APIs/index.md).



## Navigation


- [Runtime scan](RuntimeScan/index.md)
- Folder & structure docs:

[`Folders/AddOns.md`](Folders/AddOns.md)
[`Folders/FrameXML.md`](Folders/FrameXML.md)
[`Folders/GlueXML.md`](Folders/GlueXML.md)
[`Folders/LCDXML.md`](Folders/LCDXML.md)
[`Folders/LibraryXML.md`](Folders/LibraryXML.md)
[`Folders/SharedXML.md`](Folders/SharedXML.md)
  - [`Folders/AddOns.md`](Folders/AddOns.md)
  - [`Folders/FrameXML.md`](Folders/FrameXML.md)
  - [`Folders/GlueXML.md`](Folders/GlueXML.md)
  - [`Folders/LCDXML.md`](Folders/LCDXML.md)
  - [`Folders/LibraryXML.md`](Folders/LibraryXML.md)
  - [`Folders/SharedXML.md`](Folders/SharedXML.md)
- API reference:

[`APIs/index.md`](APIs/index.md)
  - [`APIs/index.md`](APIs/index.md)
- [`Events.md`](Events.md)
- [`Enums.md`](Enums.md)
- [`Templates.md`](Templates.md)
- [`JsonMessaging.md`](JsonMessaging.md)
