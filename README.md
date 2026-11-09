# RSVP Reader

Read long text one word at a time on a black screen. The fixation letter is red and stays in the same spot on screen.

Live at: https://arallsopp.github.io/rsvp/

## Ways to load text

- **Paste:** tap *Paste* (or long-press the box), then *Read*.
- **Shortcut (share sheet):** `https://arallsopp.github.io/rsvp/?paste` shows a "Tap to paste & read" button that reads the clipboard.
- **Link with text:** `https://arallsopp.github.io/rsvp/#text=<url-encoded text>` opens straight into the reader. Good for short text only.

## iOS Shortcut: "RSVP Read"

1. Shortcuts → **+** → name it **RSVP Read**.
2. **ⓘ** → turn on **Show in Share Sheet**. Receive: Text, Rich Text, PDFs, Safari web pages, URLs. If there's no input: **Get Clipboard**.
3. *(Optional, for web pages)* **Get Article using Safari Reader** → **Get Details of Article: Body**.
4. **Get Text from Input**.
5. **Copy to Clipboard**.
6. **Open URLs**: `https://arallsopp.github.io/rsvp/?paste`

From the Google Docs app: Select All → Copy → open the reader, or *Share & export → Send a copy → PDF → RSVP Read*.

## Reader controls

- Tap: play/pause. While paused you can tap a word in the context to jump to it, drag the scrubber, or step by word or sentence.
- Keys: Space, ←/→ (word), ⇧←/⇧→ (sentence), ↑/↓ (speed), Esc.
- Your position, speed, word size and pause length are saved on the device.

## Files

`index.html` (whole app), `manifest.json`, `sw.js` (offline cache; bump `VERSION` on changes), `icon-*.png`.
