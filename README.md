# Maruf's Arena

Editable browser FPS multiplayer starter. Five-player room, Socket.IO position sync, arena map, M416/AKM/AWM/MP5/UZI, scope toggle, reload/ammo UI, health and kill counter.

## Run locally
- Install Node.js 18+
- In this folder run `npm install`
- Run `npm start`
- Open `http://localhost:3000`
- Open the address in up to five browser tabs/devices to test.

## Publish a shareable online link
This needs a Node.js server; static hosting alone will not run multiplayer. Push this folder to GitHub, create a Node Web Service on Render, set Build Command `npm install` and Start Command `npm start`. Share the resulting HTTPS URL.

## Customize
- Player cap: `MAX` in `server.js`
- Guns: `weapons` array in `public/game.js`
- Arena: `box(...)` calls in `public/game.js`
- Colors/UI: `public/style.css` and `public/index.html`

## Prototype notice
This is a starter prototype, not a finished competitive shooter. It has simple capsule player models and placeholder gun geometry. Add proper matchmaking, robust server-side movement/hit validation, accounts, persistent stats, sound, animations, polished touch controls and production security before public competitive release. The requested win/lose legacy screens are not yet implemented in this prototype.
