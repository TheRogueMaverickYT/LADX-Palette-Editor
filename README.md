# LADX Palette Editor

A browser-based colour palette editor for **The Legend of Zelda: Link's Awakening DX** (Game Boy Color, English v1.2).

**Open the editor:** this repository's GitHub Pages site (index.html).

## What it does
- Edit all 1,571 colour palettes the game uses (Link, NPCs, enemies, overworld, interiors, dungeons, HUD, intro, ending…) with Final Fantasy-style R/G/B sliders (0–31, the GBC's native scale)
- Sprite preview, live while you edit
- Screen preview from SameBoy save states (BESS format) — click any pixel to edit that colour
- Map viewer for a map pack (see below)
- Colour grading (hue / saturation / lightness / contrast / tint), "replace every identical colour", undo/redo
- Export a patched `.gbc` or an `.ips` patch; save/load project files

Everything runs locally in your browser. **No ROM or game data is included or uploaded** — you load your own legally dumped ROM, and it never leaves your computer.

## Requirements
- Your own dump of *Link's Awakening DX (USA) v1.2*  
  SHA-1 `1c091225688d966928cc74336dbef2e07d12a47c`
- A modern browser (Safari, Chrome, Firefox)

## Credits
Palette locations and names come from the [zladx/LADX-Disassembly](https://github.com/zladx/LADX-Disassembly) project. Save-state support follows SameBoy's [BESS specification](https://github.com/LIJI32/SameBoy/blob/master/BESS.md).

Not affiliated with or endorsed by Nintendo.
