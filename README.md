![GitHub Release](https://img.shields.io/github/v/release/Liakate/Ascension-Client)  ![GitHub repo size](https://img.shields.io/github/repo-size/Liakate/Ascension-Client)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/Liakate/Ascension-Client/total) ![Static Badge](https://img.shields.io/badge/100%25-ChatGPT-blue?style=flat-square&logo=ChatGPT)

# Ascension Client evidence pack (GitHub-friendly)

This repository is a **slimmed-down artifact dump** for Bronzebeard/WotLK 3.3.5a research.  
It’s meant for **browsing/grepping** (HTML/JSON/CSV + source archives), not for building anything directly.

It contains:

1) **Runtime scan output** (`Output/`) — HTML indexes + raw exports (JSON/CSV)  
2) **Zipped runtime output** (`Output.zip`) — same content as `Output/`  
3) **Interface source archive** (`interface.zip`) — code-only `Interface\*` rip (FrameXML/SharedXML + bundled UI)  
4) **DBFiles archive** (`DBFiles.zip`) — `DBFilesClient/*.dbc` tables (offline content evidence)  
5) **Convenience exports** (root `*.csv` / `*.xlsx`) — quick-to-open copies of commonly used tables

## Start here (HTML)

- **API index:** `Output/index.html`
- **Globals/UI objects:** `Output/globals_index.html`

Extra indexes:

- `Output/spells.html`
- `Output/items.html`
- `Output/recipes.html`
- `Output/talents.html`
- `Output/mysticenchants.html`

Raw exports (machine-readable):

- `Output/EvidenceIndex.json`
- `Output/GlobalsIndex.json`
- `Output/API_DOCUMENTATION.html`
- `Output/API_DOCUMENTATION_RUNTIME_OBJECTS.html`
- `Output/OBJECT_GRAPH_FIELDS.html`

> Tip: GitHub doesn’t always render local HTML reliably in the file viewer.  
> If the HTML links don’t display, clone/download the repo and open the `index.html` files locally.

## Rebuilding / regenerating these files

Rebuilding the client-derived files (Interface/DBFiles/runtime-scan artifacts) is **not fully proven yet** because we’re not 100% sure about the **exact MPQ patch order** being applied by the launcher/client.

Current process is a **best guess**, and notably we **do not include**:

- `E:\Ascension Launcher\resources\client\Data\Bronzebeard\patch-D.MPQ`

…because we see **no evidence** of it being accessed when tracing file activity with **ProcMon (Process Monitor)**:
https://learn.microsoft.com/en-us/sysinternals/downloads/procmon

Process Monitor is an advanced monitoring tool for Windows that shows real-time **file system**, **Registry**, and **process/thread** activity.

If you’re reproducing this on your machine, please verify patch reads on your system (filters: your WoW client process + `Path` contains `\Data\Bronzebeard\patch-`).

## Source archives

- `interface.zip` — the Bronzebeard **Interface** package (code-only).
- `DBFiles.zip` — the Bronzebeard **DBFilesClient** content pack (DBC tables).
- `Output.zip` — zipped copy of `Output/` (runtime scan artifacts).

## File inventory

Below is the complete file list for this repo snapshot (sorted). Git/VCS-only files like `.gitignore` are intentionally not listed.

<details>
<summary>Click to expand the full file list</summary>

```text
DBFiles.zip
ITEMS.csv
MYSTIC_ENCHANTS.csv
MysticEnchants.xlsx
Output.zip
Output/API_DOCUMENTATION.html
Output/API_DOCUMENTATION_RUNTIME_OBJECTS.html
Output/EvidenceIndex.json
Output/EvidenceIndex_VerificationReport.html
Output/GLOBAL_UI_OBJECTS.html
Output/GlobalsIndex.json
Output/ITEMS.csv
Output/MYSTIC_ENCHANTS.csv
Output/OBJECT_GRAPH_FIELDS.html
Output/RECIPES.csv
Output/SPELLS.csv
Output/TALENTS.csv
Output/globals_index.html
Output/index.html
Output/items.html
Output/mysticenchants.html
Output/recipes.html
Output/spells.html
Output/talents.html
README.md
RECIPES.csv
SPELLS.csv
Talents.csv
Talents.xlsx
interface.zip