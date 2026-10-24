# Site Factory — idea bank

Direction: **technical demos**, not toy mini-games. Each site must look like it
should not fit in one file: real-time graphics, simulation, audio/DSP, or a real
algorithm with visible internals. Show an FPS/frame-time counter, live
parameters, and one line on how it works.

Rules: one screen, no libraries or external assets, works on a phone, one HTML
file, instant load. Skip anything already in `manifest.json`.

## Seeds (pick, mutate, or invent better)
- WebGL raymarching playground: SDF shapes, live shader editing
- Interactive fluid simulation (Navier–Stokes, canvas)
- Reaction–diffusion (Gray–Scott) with parameter sliders
- CPU/WebGL ray tracer with progressive sampling and a sample counter
- Raycasting 3D engine (Wolfenstein-style) with a minimap
- Web Audio synth: oscillators, filter, envelope, live FFT scope
- Mandelbrot/Julia deep zoom with WebGL
- Verlet physics sandbox: ropes, cloth, collisions
- A* / Dijkstra pathfinding visualizer on a generated maze
- Tiny Lisp or Brainfuck VM with step-by-step execution view
- SHA-256 proof-of-work demo with a live hash-rate counter
- CRDT text editor: two panes, conflicts resolved live
- Regex engine from scratch with a step trace
- Waveform/spectrogram from the microphone
- Boids flocking with spatial hashing and an FPS budget
- Procedural terrain + hydraulic erosion
- Chess engine with minimax and an evaluation bar
- Image → edge detection / ASCII with a camera feed
- L-system / generative art with seeded reproducibility
- Inline WASM (hand-assembled) doing a hot loop next to JS for comparison

## Judging
Ask: would a developer stop scrolling to see how it works? Does it visibly do
something expensive (frames, samples, particles, hashes)? If it is just a quiz
or a roulette, it is not technical enough.
