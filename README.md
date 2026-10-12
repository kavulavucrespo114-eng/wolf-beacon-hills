# Wolf: Beacon Hills

A 3D supernatural action game that runs in the browser (Three.js + cannon-es). Play as a teen who can transform into a werewolf, fight hunters and creatures across five missions. Works on desktop and phones, and can be installed to the home screen.

**Created by Crespo Kavulavu**  
Copyright (c) 2026 Crespo Kavulavu. All rights reserved. See `COPYRIGHT.txt`.

## Play online
After publishing with GitHub Pages (below) your game is at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Controls
| Action | Keyboard | Phone |
|---|---|---|
| Move | WASD | d-pad or drag the left side |
| Look | mouse / arrow keys | drag the right side, or the turn buttons |
| Run | Shift | Run |
| Jump | J | Jump |
| Attack | Space | Claw |
| Transform | T | Change |
| Howl / Pack call | H / C | Howl / Pack |
| Interact | E | Use |

## Files
- `index.html` - the whole game (code + page)
- `manifest.webmanifest`, `sw.js`, `icons/`, `favicon.ico` - install-to-home-screen support and icons
- `COPYRIGHT.txt`, `THIRD-PARTY-NOTICES.txt` - ownership and open-source credits

## Run it locally
```
python3 -m http.server 8080
```
then open http://localhost:8080 (opening index.html by double-click will not work because the game uses modules).

## Publish on GitHub Pages
1. Create a repository on github.com and upload all files in this folder (index.html must be at the top level).
2. Repository **Settings > Pages > Build and deployment**: Source "Deploy from a branch", Branch `main`, folder `/ (root)`, Save.
3. Wait a minute, then open the address GitHub shows.

## Optional models
Players can load their own character (.glb, not Draco-compressed) and animation clips from the start screen. No third-party character models are included.
