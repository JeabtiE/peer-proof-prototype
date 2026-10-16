# Peer Proof – clickable prototype v2

Clickable mobile prototype for Peer Proof: a weekly "recipe from shops like yours" flow for made-to-order shops, from discovery in LINE OA through to proving the result.

All data in the prototype is synthetic and the design is stand-alone.

## Flow

1. Discover (LINE OA message)
2. Recipe card (afternoon combo, 2–5 pm)
3. Choose: do it for me / try it myself / not for my shop
4. Preview and confirm (or the try-it-yourself principle)
5. Prove (2 weeks later, vs similar shops)
6. Appendix: if it did not work (roll back)

## Run locally

It is a single static file with no build step and no dependencies.

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy on Vercel

Vercel serves `index.html` at `/`, so no extra configuration is needed.

- Framework Preset: Other
- Build Command: empty
- Output Directory: empty (project root)

## Controls

- Tap the buttons inside the phone frame to move through screens
- Back arrow in the header, or the left arrow key, goes back
- "Restart" above the phone returns to screen 1
