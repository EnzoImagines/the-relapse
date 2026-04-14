# The Relapse

> *You got out once. At least, you think you did.*

## What is this?

**The Relapse** is an experimental browser-based psychological horror experience. No downloads. No installs. Just a URL and the slow, creeping realization that you've been here before.

You're standing in a hallway. Yellow wallpaper. Damp carpet. A fluorescent light buzzes overhead — the only one that works on this stretch. Your flashlight cuts a cone through the dark. You start walking. The corridor stretches ahead. You turn a corner. Then another. After a while, you look behind you.

The way you came is gone.

New walls. New corridors. A turn that wasn't there thirty seconds ago. You keep walking because there's nothing else to do. And somewhere, deep in the back of your mind, you realize — you recognize this carpet. You've walked under these lights before. You've smelled this air before.

You got out. You're sure you got out. But here you are again.

**This is the relapse.**

## The Logs

You're not the first person to walk these halls.

Scattered across the labyrinth are 50 handwritten logs from someone named Jason. Dropped on floors. Left on tables. Abandoned in corridors that may not exist by the time you finish reading them.

Jason mapped this place. Jason tried to understand it. Jason tried to leave. His logs tell the full story — not in order, not in sequence. You find them where the place decides to put them. Some quickly. Some after hours of searching. Each one reveals a little more about what's happening here, and a little less about whether escape is possible.

Press **L** to open the journal. Entries you've found are readable. The rest are visible but blurred — proof that there's more to the story, just out of reach. Collect them all to piece together the full truth. Or don't. The hallways don't care either way.

## The Experience

- **Infinite procedural corridors** — the labyrinth generates itself as you walk, endless and unrepeating
- **Reality shifts behind you** — turn around and the architecture has rewritten itself
- **Flashlight-driven exploration** — darkness is the default, your light is everything
- **50-entry hidden narrative** — a complete story scattered across an impossible space
- **Procedural artwork** — paintings on walls, each unique, each slightly unsettling
- **Layered soundscape** — electrical hum, water drips, metallic groaning, ambient music
- **Persistent progress** — found logs save between sessions

## How to Play

Open **[The Relapse](https://enzoimagines.github.io/the-relapse/)** in any modern browser. Click to enter.

Best experienced in a dark room with headphones.

| Control | Action |
|---------|--------|
| `W A S D` | Move |
| `Mouse` | Look around |
| `E` | Pick up / read a log |
| `L` | Open journal |
| `ESC` | Pause menu |

## Technical

Built from scratch with [Three.js](https://threejs.org/). No frameworks. No game engine. No server. Just geometry, fog, and the uncanny.

- Corridor region generation system with versioned chunk architecture
- Edge-based procedural walls — cells regenerate new layouts when they leave your field of vision
- Shared geometry pool with throttled build/destroy pipeline for consistent framerate
- Procedural canvas textures (carpet, wallpaper, ceiling tiles, oil paintings)
- Web Audio API soundscape — all audio is generated or streamed in-browser
- ACES filmic tone mapping, linear fog, SpotLight flashlight with real-time cone

## Why?

There's a theory that liminal spaces — empty hallways, abandoned malls, hotel corridors at 3am — feel wrong because they resemble the architecture your brain constructs during memory consolidation. Not real places, but the scaffolding of places. Familiar geometry with nothing inside.

**The Relapse** takes that idea and asks: what if you couldn't leave? What if every time you thought you'd escaped, you were just walking deeper into the same structure? What if the architecture itself was the thing you kept relapsing into?

The logs give you something to search for. The shifting walls make sure you can never feel oriented. The darkness makes every step forward an act of faith.

You've been here before. You'll be here again.

Keep walking.

---

**[Play now](https://enzoimagines.github.io/the-relapse/)** · **[𝕏 @EnzoImagines](https://x.com/EnzoImagines)**
