# 彩墨 Ink Wash

A ~150-second generative Chinese colour ink-wash film in a single `index.html`: WebGL2, custom GLSL, ping-pong framebuffers, and a stateful GPU ink simulation (wet paper, pigment diffusion, edge deposition, rice paper, dry brush, subtractive pigment mixing).

Open `index.html` directly in a browser. Controls: `SPACE` / click to pause, `R` to replay, `F` for fullscreen, `M` to mute.

Music is synthesised live with Web Audio (guqin-like plucks, xiao flute, drone, water drops, stone chime in D pentatonic) and scheduled against simulation time. Browsers block sound until a gesture, so the first tap turns sound on.

Optional URL parameters: `?res=480` sets the simulation resolution (default 640), `?t=60` fast-forwards, and `?seed=123` changes the seed.
