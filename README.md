# D&D table tools

Two single-file web apps for running a 5e game.

- `index.html` — **Initiative Ledger**: combat tracker with turn order, HP and temp HP, conditions, death saves, concentration checks, and a dice roller. Saves to the browser.
- `atlas.html` — **Campaign Atlas**: upload campaign maps, pin places and NPCs, nest detailed maps inside places, track NPC connections, and keep DM-only character sheets, secrets, and hidden pins. Built as a Claude artifact: it uses the artifact runtime (`window.claude`) for storage and uploads, so it only works fully when opened as a claude.ai artifact.
- `maps/` — sample world and town map images.
