# Ассеты (сгенерированы через Replicate, 2026-11-09)

- `characters/assassin_v1.glb` — TRELLIS image→3D из A-позы ассасина (art/concepts/assassin_apose_v1.png), без скелета.
- `characters/assassin_v1_rigged.glb` — тот же меш после авто-риггинга uthana/create-character-v1, скелет Mixamo (52 кости).
- `anim/*.glb` — движения sprited/kimodo (скелет SOMA, только анимация костей): idle, walk, attack, hit, death. Ретаргет на Mixamo делается на лету в `src/render/animations.ts`.

Просмотр: `/#viewer?url=/assets/characters/assassin_v1_rigged.glb&clip=walk` (clip: idle | walk | attack).
