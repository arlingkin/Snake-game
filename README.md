# Snake-game
A modern clasical retro game with scores and color changes when ate food

## Files
→ `index.html`: game, scoring, and leaderboard
→ `audio/`: sound assets

## Leaderboard setup (Firestore)
→ Firebase Console: create a project (use a dedicated one, publishing rules replaces all rules of a project), then Build → Firestore Database → Create database
→ Rules tab: paste `firestore.rules` → Publish
→ Project settings → Your apps → Web app: copy `projectId` and `apiKey` into `RemoteDB` in `index.html`
→ Until both are set the game runs in offline mode with the local leaderboard only
