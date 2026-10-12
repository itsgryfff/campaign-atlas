# Campaign Atlas

Maps, places, NPCs, connections, DM-only character sheets and secrets, and a player view for a D&D campaign.

The atlas runs as a Claude artifact: https://claude.ai/artifact/PaxWd1yWAy6o1hT5Ddb2YB
Campaign data (maps, pins, NPCs, sheets) is stored in Claude, not in this repository.

## Layout

- `index.html`: landing page for GitHub Pages that links to the atlas.
- `atlas/index.html`: source of the Campaign Atlas artifact. It uses the Claude artifact runtime (`window.claude`) for storage and uploads, so it only works when opened as a claude.ai artifact.
- `atlas/sample-maps/`: the example world and town maps.
- `initiative/index.html`: Initiative Ledger, a standalone combat tracker that saves to the browser. It shares no files with the atlas, so the `initiative/` folder can be deleted without affecting anything else.
