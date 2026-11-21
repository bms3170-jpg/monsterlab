# Monster Lab 3D Web Prototype v0.1

## Current vertical slice
Single-page iPhone portrait lobby and WebGL battle prototype. All hero drawings in WebGL are original procedural primitives. No network dependencies.

**Implemented:** hero roster/deck, level/awakening, earnable economy, shop/gacha, wave spawning, automatic attacks/effects, manual ultimate, merge, AI ally and basic cooperative burst, local storage, mode selection, 30-wave choice.

**Not implemented:** true 2-device network multiplayer, accounts and authoritative server, production 3D mesh rigging, cloud save, payments, analytics, polished audio, boss AI patterns, final balance.

## Next development milestone
1. 2-player multiplayer with authoritative room + saved accounts (WebSocket backend)
2. Combat skill system depth, individual evolution model assets, UI art/sound polish
3. Mobile Safari performance, low-memory testing on real devices
4. Boss patterns (currently boss HP/size/leak damage only), shared fusion variant selection
5. Automated persistence/combat regression tests and game economy balance

## Folder
- `index.html`: standalone single file for upload to static hosting
- `source/`: original split CSS/JS/HTML source
- `README_아이폰_실행방법.txt`: iPhone deployment instructions
