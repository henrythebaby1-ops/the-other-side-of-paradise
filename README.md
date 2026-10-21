# The Other Side of Paradise

A small three.js game about finding the number between 3 and 4.

You wake up in Professor Ersheim's room of illusions. Solve its 12 puzzles, find your way out the door that keeps leading back inside, and then search the number line in paradise for the number between 3 and 4.

Plays in a desktop browser or in VR (WebXR).

## Play

- **Online:** open the GitHub Pages link for this repo (Settings → Pages).
- **Locally:** download the repo and open `index.html`. Keep `the-other-side-of-paradise.mp3` in the same folder so the music plays.

## Controls

**Desktop**
- Click to look around (Esc releases the mouse)
- WASD or arrow keys to move
- Click on things to interact

**VR** (press *Play in VR* in a WebXR browser such as the PICO or Quest browser)
- Left stick or WASD to move
- Drag the mouse or use the arrow keys to look around; right stick or Q/E to snap-turn
- Trigger, Space, Enter, F or a click to interact with whatever you point or look at

## The puzzles

1. The hidden number: cubes that only form a "3" from one spot (anamorphic art)
2. Which square is lighter? (Adelson's checker shadow)
3. Which line is longer? (Müller-Lyer)
4. Make the triangle impossible (Penrose triangle)
5. Count the grey dots (Hermann grid)
6. Count the triangles (Kanizsa triangle)
7. Stare at the heart (negative afterimage)
8. Which orb is bigger? (forced perspective)
9. Find the code (the upside-down room)
10. How does Ersheim count?
11. Separate the bleem jelly beans
12. Read about Laszlo Bleem

Then: leave through the door. It's on the other side.

## Testing VR without a headset

`pico-emulator.html` is the same game with an emulated PICO 4 headset, using Meta's [Immersive Web Emulation Runtime](https://github.com/meta-quest/immersive-web-emulation-runtime). Open it from a web server (not by double-clicking the file) and press *Play in VR*.

## Credits

- **Music:** "The Other Side of Paradise" by Glass Animals, from *How to Be a Human Being* (2016). All music rights belong to Glass Animals and their labels; the track is included here for the game only.
- **Inspired by** "The Secret Number", a short film by Colin Levy (2012), adapted from the short story by Igor Teper.
- Built with [three.js](https://threejs.org/) r128 (bundled as `three.min.js`, MIT license). The PICO 4 emulator uses Meta's IWER (bundled as `iwer.min.js`, MIT license).
