# Risk of Rain 2 Card Game (online)

Static single-file game. Multiplayer is peer-to-peer WebRTC (PeerJS handles the handshake); the host's browser runs the game.

## Deploy on GitHub Pages
1. Create a repo and add `index.html` (and this README) to the main branch.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Open `https://<you>.github.io/<repo>/`.

## Play
- Host: enter a name, press **Host game**, share the 4-letter room code.
- Others: open the same URL, enter a name and the code, press **Join**.
- Host presses **Start game** (2–6 players). Players take turns on their own devices; only the host can finish the round or override scores.
- If someone drops, they can rejoin with the exact same name. If the host closes the tab, the game ends.
- Very strict networks may need a TURN server; PeerJS's free cloud broker is used for matchmaking.
