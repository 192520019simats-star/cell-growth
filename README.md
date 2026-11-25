# Cell Growth Explorer (dashboard)
Evaluation of Extracellular Matrix and Cytoskeletal Interactions in Cell Growth.
HTML5 + CSS3 + vanilla JavaScript on Node.js + Express. No React, database or API keys. Works offline.

## Run (Windows, VS Code)
1. File > Open Folder: choose the folder that directly contains `package.json` and `server.js`.
2. Terminal > New Terminal. If PowerShell blocks npm, switch to Command Prompt (arrow next to +).
3. `npm install`
4. `node server.js`
5. Open http://localhost:3000 in Chrome. Stop with Ctrl+C.

## Files
- `server.js`: Express server for `public/`
- `public/index.html`: sidebar app shell and five views
- `public/style.css`: light dashboard theme, responsive layout
- `public/script.js`: navigation, tilting cell simulation, explorer, stiffness simulation
Educational visualization only; no experimental values are claimed.
