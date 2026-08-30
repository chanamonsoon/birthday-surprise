# Birthday Surprise 💗

A single-file, interactive birthday page for a partner — password-locked, with a
love letter reveal, a photo gallery, a candle to blow out, and a small gift box.

## Usage

1. Open `index.html` in a browser (double-click it, or drag it into a browser tab).
2. Enter the password on the lock screen to see the surprise.
3. Optionally click into the gallery photos to upload your own images, then
   press **"ดาวน์โหลดเว็บฉบับสมบูรณ์"** to save a finished copy with those photos
   baked in — that's the file to actually send.

## Customizing

Everything editable lives in one place: the `CONFIG` object near the bottom of
`index.html` (search for `const CONFIG`). You can change:

- `partnerName` / `yourName` — the names shown throughout the page
- `password` / `passwordHint` — the lock screen password and its hint
- `heroMessage` — the intro message under the title
- `timeline` — the "Our Story" moments (icon, title, text)
- `letter` — the full love letter text
- `surpriseMessage` — the message revealed by the gift box

No build step or dependencies — it's plain HTML/CSS/JS.
