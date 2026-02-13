# Interface/LCDXML



## Summary


`Interface/LCDXML` contains XML layouts for **LCD device displays** (historically used by devices like Logitech G-series keyboards with LCD panels).



## Files


- `LCDLayout.xml` — monochrome layout definitions for several “screens” (title, player info, etc.)
- `LCDColorLayout.xml` — color layout definitions (backgrounds + bitmap resources)



## How it works (high level)


- These XML files define `<Screen>` elements composed of LCD primitives (text, bitmaps).
- The client’s LCD subsystem selects which screen is active and supplies values for dynamic fields.
- If you’re not targeting LCD hardware, you can usually ignore this folder.
