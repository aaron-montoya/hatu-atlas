# Hatu Atlas

A planning walkthrough for a Zelda-style action adventure set in the world of Hatu. It's written like a fan guide for a game that doesn't exist yet, so the puzzles, side quests and collectibles can be planned before they're built.

**Live site:** https://aaron-montoya.github.io/hatu-atlas/

## What's inside

- 13 walkthrough chapters in story order
- Interactive 3D maps of all four temples: pick a floor, tap a room to read its step
- Bestiary, characters, items and story pages, linked from every mention
- Checklists for Mystic Fireflies, Totems of Strength, Enchanted Scrolls and Map Pieces
- An Open Questions page that collects every undecided design choice

## How it's built

Everything is in one file, `index.html`: no build step, no dependencies besides Google Fonts. Edit it and push, and GitHub Pages republishes in a minute or two.

- Temple map data: search for `const MAP3D` (rooms, floors, shapes, features, doors and stairs)
- Monsters, characters and items: search for `const ENTITIES`
- Chapter text: the `<article class="page" data-page="ch1">` blocks
