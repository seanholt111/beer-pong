# Beer Pong (mobile-first)

Two-player hot-seat beer pong in a **single HTML file**. No build tools, no npm, no CDN — open it offline on a phone and pass it back and forth.

## Play on your phone

**Live site:** https://seanholt111.github.io/beer-pong/

1. Open the link above in **Safari** on iPhone (or Chrome on Android).
2. Optional: tap **Share → Add to Home Screen** for a fullscreen, app-like feel.
3. Or open `index.html` offline (AirDrop, Messages, Drive, etc.) — still one device at a time for pass-the-phone play.


On a computer you can open the site or `index.html` in a browser too, but the layout is tuned for **portrait phones (~375-430px wide)**.

## How to play

- Enter names (default **Sean** / **Guest**) • **Start Game**.
- **Drag back** on the lower half of the table like a slingshot, **release** to throw. Farther pull = more power; the dotted arc shows the path.
- Sink the ball in a cup to remove it. Clear all **10** of your opponent's cups to win.
- After each shot, **pass the phone** when prompted, then tap **I'm ready**.
- Tap **Re-rack** anytime to pack remaining cups into a tight triangle (handy at 6 / 3 / 1).

## Files

- `index.html` — entire game (CSS + JS inline)
- `README.md` — this file

## Notes / limitations

- House rules only (no redemption, no full tournament bracket).
- Simple 2D physics (arc + light rim bounce); not a physics engine sim.
- Best in portrait; landscape works but is cramped.
- Works offline as a local file; Add to Home Screen does not need a service worker.
