# Shark Snatch

Open your mouth. Eat sharks. That's the whole game.

**[Play it](https://ashleywolf.github.io/shark-snatch/)**

Sharks swim across the screen in random directions. Move your head to line up, then open your mouth wide to chomp them. Baby sharks are fast and worth 1 point. Great whites are slow and worth 5. You get three lives -- every shark that escapes costs one.

Difficulty ramps every 30 seconds: more sharks, faster swimming. See how deep you can go.

## How it works

- MediaPipe FaceLandmarker tracks your mouth via webcam
- `jawOpen` blendshape triggers the catch when it crosses the threshold
- Three shark types with weighted spawn rates
- Procedural audio (Web Audio API) -- no sound files
- Canvas 2D rendering with bubble particles and ocean gradients
- High scores saved to localStorage

Single HTML file. No dependencies. No build step.
