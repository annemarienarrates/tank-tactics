# Tank Tactics

A slow, sneaky multiplayer grid war for friends. Adapted from Luke Muscat's Tank Turn Tactics.

- One AP a day, banked forever. Move, attack, give AP, or extend your range.
- Your hearts are secret. Hits are seen only by attacker and target. Kills are public.
- Comms to everyone, or privately to one player.
- Online rooms with 5-character codes, or pass-and-play on one screen.

## Files

- `index.html` is the whole game.
- `firebase-config.js` holds the Firebase settings for online rooms.
- `firestore.rules` is the database security rules, pasted into the Firebase console.

Pass-and-play works without Firebase. Online rooms need `firebase-config.js` filled in.
