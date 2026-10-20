# Counter-Strike 1.6 Web

A complete browser-based tactical FPS remake recreating classic Counter-Strike gameplay in WebGL with Three.js.

## Features

- Complete 3D Maps:
  - de_mirage (Oasis) with full CS collision hulls, navmeshes, and prop geometry.
  - de_dust2 (Dune) with full collision meshes, T/CT spawns, Long A, and B site.
- Factions & Character Models:
  - Counter-Terrorists (CT): SAS and FBI agent models with custom gloves.
  - Terrorists (T): Phoenix Connexion models.
- Full Weapon Arsenal & Viewmodels:
  - Pistols: USP-S, Glock-18, Desert Eagle, P250, Dual Berettas, Five-SeveN, Tec-9.
  - Rifles & Snipers: AK-47, M4A1-S, AWP, SSG 08, FAMAS, Galil AR, AUG, SG 553.
  - Mid-Tier / SMGs / Shotguns: MP5-SD, P90, MP9, MAC-10, Nova, XM1014.
  - Equipment & Grenades: Knife (CT and T), Zeus x27, C4 Explosive, HE Grenade, Flashbang, Smoke Grenade, Molotov/Incendiary, Decoy.
- Tactical Gameplay Engine:
  - Working buy menu ([B]) with round economy and weapon purchasing.
  - Autonomous tactical bot AI with pathfinding on de_mirage and de_dust2.
  - Bomb Defusal game mode with site planting and defuse kits.
  - Team Deathmatch game mode.
  - Real-time radar/minimap with teammate and site callout tracking.
  - Custom glove shaders and viewmodel weapon recoil/bobbing animations.
  - Complete sound library: 1,100+ audio clips (gunshots, reloads, footsteps, defuses, radio calls).

## Controls

- Movement: WASD
- Jump: SPACE
- Crouch: L-CTRL or C
- Walk: L-SHIFT
- Fire: MOUSE 1
- Aim / Scope / Alternate Fire: MOUSE 2
- Reload: R
- Buy Menu: B
- Drop Weapon / C4: G
- Plant / Defuse / Interact: E
- Scoreboard: TAB
- Pause / Options: ESC

## Running Locally

1. Start the game server:
```bash
npm start
```
or
```bash
node server.js
```

2. Open your web browser and navigate to:
```
http://localhost:8085
```

3. Select your map (de_mirage or de_dust2), game mode, and click PLAY GAME.
