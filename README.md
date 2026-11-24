# Hotel Master

A strategy / simulation game: start with a single room on your own land and
build it into a hotel empire. 2D isometric, painterly style, tap-first and
phone-friendly.

Play it live (GitHub Pages): https://pete1450.github.io/hotel-manager/

## How to play

- Open `index.html` in a browser, or serve the folder with any static server.
- Start with one room and no lobby. Guests walk a dirt path straight to the
  room door.
- Build rooms, hallways, a lobby and a breakfast/dining area on the freeform
  80×48 grid. Tap to preview, hold 1 second to place. Rooms need a hallway
  path from the lobby (or a stairwell / elevator for upper floors) or no one
  can reach them.
- Lobby and breakfast/dining are movable, resizable containers — place a
  fountain inside the lobby, a buffet inside the dining area.
- Set prices per room type, hire staff (housekeepers walk to dirty rooms and
  take 2 seconds to clean each one), upgrade rooms — every upgrade is
  visible in the room and size-gated.
- Your hotel saves automatically in the browser's local storage. Continue
  where you left off, or start a new game from the Menu drawer.
- Menu drawer: toggle unlimited cash on/off (limited cash is the default,
  starting at $1,500). There is no rent — you own the property; upkeep and
  wages are the monthly pressure.

## Files

- `index.html` — the whole game, single file
- `assets/` — painterly isometric art: fountains, beds, floor/wall tiles,
  and the painted character sprite strips (maid, backpacker, tourist,
  business traveller, VIP, affluent, receptionist, chef)

## Deploy

GitHub Pages serves this repo from `main` (root). Push to `main` and the
live site updates.
