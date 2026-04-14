# noclip.exe

> *You didn't mean to end up here. Nobody does.*

## What is this?

**noclip.exe** is an experimental web-based horror exploration built entirely in the browser. No downloads. No installs. Just a URL and the growing realization that you are not going to find your way back.

You've clipped through the boundaries of normal space into an infinite, procedurally generated labyrinth of yellowed wallpaper, damp carpet, and buzzing fluorescent lights. The hallways stretch endlessly in every direction. Some lights work. Most don't. The ones that flicker do so in patterns that almost mean something.

The corridors generate ahead of you as you walk. When you turn around, the path you came from no longer exists. New walls. New turns. New dead ends. The architecture reshuffles itself the moment it leaves your field of vision. There is no backtracking. There is no map. There is only forward.

## The Logs

Scattered throughout the labyrinth are handwritten logs — 50 entries from someone named Jason who was here before you. Found on tables, dropped on the floor, left in corridors that may not exist by the time you finish reading them.

The logs tell a story. Not all at once. You find them out of order, in random places, at random times. Some you'll find quickly. Others may take hours of wandering. Each one peels back another layer of what this place is, how it works, and whether there's any way out.

Press **L** to open the journal. Found entries are readable. Unfound entries are blurred — you can see they exist, but you can't read them until you find the physical log in the world. The question isn't whether you'll find them all. It's whether you'll still want to keep looking.

## The Experience

- **Infinite procedural generation** — corridors, turns, and junctions that never repeat and never end
- **Reality shifts behind you** — the world restructures itself when you're not looking
- **Flashlight-dependent exploration** — the rooms are dark, your flashlight is your lifeline
- **50-entry narrative** — a complete story hidden across an infinite space
- **Procedural artwork** — paintings and frames on walls, each one unique, each one slightly wrong
- **Spatial audio design** — electrical hum, water drips, distant metallic groaning, ambient dread
- **Persistent progress** — found logs save locally, pick up where you left off

## How to Play

Open **[noclip.exe](https://enzoimagines.github.io/noclip-exe/)** in any modern browser. Click to enter. That's it.

| Control | Action |
|---------|--------|
| `W A S D` | Move |
| `Mouse` | Look around |
| `E` | Pick up / read a log |
| `L` | Open journal |
| `ESC` | Pause menu |

Works best in a dark room with headphones.

## Technical

Built from scratch with [Three.js](https://threejs.org/). No frameworks. No game engine. No server. Just geometry, fog, and the uncanny.

- Edge-based procedural wall generation with corridor region system
- Versioned chunk architecture — cells regenerate with new layouts when they leave view
- Shared geometry pool for zero-allocation chunk building
- Throttled build/destroy pipeline (max 4 builds per frame) for consistent framerate
- Canvas-generated procedural textures (carpet, walls, ceiling tiles, paintings)
- Web Audio API procedural soundscape
- ACES filmic tone mapping + linear fog

## The Idea

There's a theory that liminal spaces — empty hallways, abandoned malls, hotel corridors at 3am — feel uncanny because they resemble the spaces your brain generates during memory consolidation. Places that are *almost* real. Familiar but hollow. Recognizable but empty.

**noclip.exe** is an attempt to build one of those spaces and let you walk through it. Not as a game with objectives, but as an experience. The logs give you a reason to keep going. The shifting architecture ensures you can never feel safe. The darkness makes every corner a question.

You're not supposed to be here. But now that you are — keep walking.

---

**[Play it now](https://enzoimagines.github.io/noclip-exe/)** · **[𝕏 @EnzoImagines](https://x.com/EnzoImagines)** · **[GitHub](https://github.com/EnzoImagines/noclip-exe)**
