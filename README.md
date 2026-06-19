# Compensation-System https://steamcommunity.com/sharedfiles/filedetails/?id=3742107004
The compensation system for your DayZ server. Easily provide compensation to players—either individually for specific players or globally for the entire community (e.g., after a crash, as compensation, or as an event prize).


✨ Features:
- Individual & Global Refunds: Distribute gifts/refunds to specific Steam IDs or enable a refund for all players.
- Abuse Protection: The system automatically records players’ SteamIDs during global refunds. Each player can claim only once!
- Multi-Item Support: You can pack as many items as you like into a single entry. They spawn neatly spaced next to each other on the ground.
- Crash Protection: This mod is completely error-tolerant. Even if you make a small mistake while editing the JSON, the server won't crash and players won't be kicked.
- Convenient In-Game Claim: Players are notified when they connect and can collect their items with a single keystroke (default: '0'). The items then spawn in front of the player, slightly offset from one another rather than all piled together.
- Discord Log: Get an instant webhook notification as soon as someone claims their compensation.

✨ Config.json
- SteamID: The player's 17-digit SteamID64 (only relevant when IsGlobal: false).
- IsGlobal: Set to true if every player on the server is allowed to pick up these items. Set to false for single-player mode.
- ClaimedSteamIDs: Do NOT enter anything here! The server automatically populates this field with the IDs of players who have already claimed the global refund.
- Items: The exact class names of the items that should spawn.
- IsClaimed: Set automatically to true by the server for single-player games as soon as the item has been claimed.

⚠️ Important tip: If you want to start a new global refund for everyone (e.g., a new event), simply clear the list under "ClaimedSteamIDs": [], so that everyone is eligible again!

Entries are saved immediately, but the server won't load them until after a restart.

🔄 Repacks are allowed
👆 If you have any questions, are experiencing issues, or need help, feel free to message me on Discord -> @kowatacc

