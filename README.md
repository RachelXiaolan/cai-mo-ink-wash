# 彩墨 Ink Wash

A ~150-second generative Chinese colour ink-wash film in a single `index.html`: WebGL2, custom GLSL, ping-pong framebuffers, and a stateful GPU ink simulation (wet paper, pigment diffusion, edge deposition, rice paper, dry brush, subtractive pigment mixing).

Open `index.html` directly in a browser. Controls: `SPACE` / click to pause, `R` to replay, `F` for fullscreen, `M` to mute.

Music is synthesised live with Web Audio (guqin-like plucks, xiao flute, drone, water drops, stone chime in D pentatonic) and scheduled against simulation time. Browsers block sound until a gesture, so the first tap turns sound on.

Optional URL parameters: `?res=480` sets the simulation resolution (default 640), `?t=60` fast-forwards, and `?seed=123` changes the seed.

## 小水彩 Little Watercolour

`watercolor.html` is a playful sibling built on the same stateful GPU simulation. It runs about 120 seconds in five chapters: 滴答 (drip), 彩虹 (rainbow), 花园 (garden), 池塘 (pond), 派对 (party).

- Bright transparent watercolours on cold-press paper, with raking-light relief and granulation.
- Crisp dried edges, and per-character coloured lettering.
- A round 乐 stamp at the end.
- A bouncy C-pentatonic soundtrack: marimba, glockenspiel, pizzicato bass, shaker and bubbles.

It uses the same controls and URL parameters as the ink version. Each page links to the other in its bottom bar.
