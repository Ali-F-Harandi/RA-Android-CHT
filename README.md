# RA CHT Editor

RetroArch Cheat File Editor — a responsive web app for creating and editing `.cht` cheat files compatible with RetroArch.

## Live App
**https://ali-f-harandi.github.io/RA-Android-CHT/**

## Guides
- **[RetroArch .cht Guide](https://ali-f-harandi.github.io/RA-Android-CHT/guide.html)** — the .cht cheat file format: fields, cheat types, handlers, memory sizes, endianness, repeat, Game Genie / GameShark codes
- **[RA Cheat — Config & Cheat Guide](https://ali-f-harandi.github.io/RA-Android-CHT/cfg-guide.html)** — the updated RA-BP cheat system guide: the two cheat types (Cheat Table + RetroArch cheats with RETRO/EMU handlers), every config file (.cfg, .racheats.json, racheat_settings.json, side files), all 20 .cfg fields, freeze modes, hotkeys, multi-write cheats, range lock, and cheat-creation workflows for RA Cheat v1.9.1

## Features
- Create, edit, delete cheats with full RetroArch `.cht` compatibility
- All cheat types: Set, Increase, Decrease, If Equal/NotEqual/Less/Greater
- Both RETRO (memory write) and EMU (emulator code) handlers
- Memory sizes: 1-bit, 2-bit, 4-bit, 8-bit, 16-bit, 32-bit
- Big-endian support (e.g. Genesis/68000)
- Repeat count / add to value / add to address
- Enable/disable (freeze) toggle per cheat
- Import existing `.cht` files via file upload
- Export to `.cht` files via download
- Fully responsive (works on desktop, tablet, mobile)
- No installation needed — runs in any modern browser

## Usage
1. Open the live app
2. Add cheats using the form
3. Click "Export .cht" to download the file
4. Copy the `.cht` file to RetroArch's cheat directory
5. Load it from RetroArch's cheat manager

## Tech
- Single-file HTML/CSS/JS (no build step needed)
- Dark theme with green accent
- Deployed via GitHub Pages Actions
