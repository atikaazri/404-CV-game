# CV SCAN — 404 NOT FOUND

** DEVELOPED FOR CSG of SQU **

A computer vision game where you use your **index finger** to unlock a code. Blobs float across the screen — hover over three of them to triangulate and reveal what's been found.

---

## How to Play

1. Open `index.html` in Chrome or Edge
2. Click **[ ENABLE CAMERA ]** and allow webcam access
3. Point your **index finger** at the camera
4. **Hover** your fingertip over a blob and hold still — a loading arc will fill around it
5. Once the arc completes, the blob is locked
6. Lock **3 blobs** to triangulate and reveal the hidden specimen

---

## Files

```
index.html      — the game
logo.png        — your logo (top-left of the UI)
unlocked.png    — the image revealed when all 3 blobs are found
README.md       — this file
```

---

## Controls

| Action | Input |
|---|---|
| Select a blob | Hover index finger over it and hold |
| Restart | Open your hand fully · or press `Space` |
| Reset | Click `[ CLICK TO SCAN AGAIN ]` on the found screen |

---

## Requirements

- Modern browser with webcam support (**Chrome or Edge recommended**)
- Camera permission must be granted
- Works best with good lighting so your hand is clearly visible

---

## Tech

- [p5.js](https://p5js.org/) — canvas rendering & metaball physics
- [MediaPipe Hands](https://github.com/google-ai-edge/mediapipe.git) — real-time hand landmark detection
- No server required — runs entirely in the browser
- No data stored or transmitted
