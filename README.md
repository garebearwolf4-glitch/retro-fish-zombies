# Retro Fish Zombies

**Play it: https://mrhattmadethat.github.io/retro-fish-zombies/**

A pixel-art arcade shooter built from a class whiteboard brainstorm (Sept. 22). The whole game is one file — `index.html` — with no build step, no libraries and no image files. Every sprite is drawn in code with rectangles.

## The brainstorm, and where each idea ended up

| On the board | In the game |
| --- | --- |
| Retro fish zombies | Four kinds shamble at you: guppies, cod, bloatfish that split in two when popped, and a Trawler Hulk boss every 5th wave |
| Abandoned city | The skyline behind the fence, with a few windows that still flicker |
| Dump | The arena — tire stacks, a dead fridge, a TV still showing static, trash bags, a leaking barrel. All solid, so you fight around them |
| Cat-Seal → hairball weapon | You. Coughing a hairball shoves you backward a little, so firing is also movement |
| Fish bone collector | Bones drop from every kill and are the currency at the **Bone Exchange** between waves |

## Controls

| | |
| --- | --- |
| Move | `WASD` or arrow keys |
| Aim | mouse |
| Hork a hairball | click, or `space` |
| Pause | `P` |

Keyboard-only works: if the mouse never moves, you hork in whatever direction you are swimming. On a tablet, drag anywhere to swim and it fires at the nearest fish automatically.

## Upgrades at the Bone Exchange

Denser Hairball (damage) · Cough Reflex (fire rate) · Flipper Wax (speed) · Blubber Layer (hearts) · Double Hork (extra hairballs) · Bone Whiskers (pickup reach)

## Notes for the classroom

- The high score is saved in the browser, so on a **shared lab machine everyone shares one best score**.
- Nothing is sent anywhere. The page works offline once it has loaded.
- Want to tinker? Open `index.html` in a text editor. The tuning numbers are near the top of the script: `UPG` is the upgrade shop, `ZTYPE` is the fish zombie stats, and `startWave` decides how many show up.

## Running it locally

No server needed — double-click `index.html`. Or serve the folder:

```bash
python -m http.server 5630
```

Pushing to `main` deploys to GitHub Pages.
