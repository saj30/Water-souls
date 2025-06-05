# Water-souls
Making a water based dark souls game for a my career program, similar 2d gameplay loop to dark souls with simple rooms to traverse.
Purify: The Flow Within – Game Logic 
1. Game Start:
The game loads with a title screen and a “Start” button.


Player starts in a central hub with basic stats.

On-screen: HP bar, XP bar, mini-map, and zone purity meter.

2. Player Actions:
Player can move, jump, dash, and attack.

They can also interact with objects or NPCs and return to the hub.

Game responds by damaging enemies, collecting XP, or opening paths.

3. Game Logic:
The game checks:

If the player or enemy takes damage

If the player dies (respawn at checkpoint)

If a zone is cleared (unlock next area)

Beating enemies or bosses gives XP.

Death results in losing some XP and restarting at the last checkpoint.

4. Score/Feedback:
Score = XP (Purity Points) from enemies and exploration.

Visual feedback: splashes when hit, screen glow when upgrading.

Audio feedback: hit sounds, zone-cleared fanfare, upgrade chimes.

5. Win/Lose Conditions:
Win: Defeat the final boss and purify all zones.

Shows ending scene and real-world clean water message.

Lose: Player dies → respawn at checkpoint with small XP penalty.

6. Reset/Replay:
Player can restart the game or replay zones from the pause menu.

Replay includes harder modes and optional challenges.
