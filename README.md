# Anti Spoil

A lightweight Chrome extension that hides the progress bar and time remaining on YouTube videos — so you can watch without knowing how much is left.

Great for sports highlights, movie trailers, mystery videos, or anything where the remaining time gives away the ending.

## What it hides

- The progress/seek bar at the bottom of the player
- The elapsed / total time display (e.g. `3:42 / 10:15`)

Works on `youtube.com` and embedded YouTube players (`youtube-nocookie.com`).

You can still control playback with keyboard shortcuts:

| Key | Action |
|-----|--------|
| `J` | Rewind 10 seconds |
| `K` | Play / Pause |
| `L` | Forward 10 seconds |

## Install

1. [Download this repo](../../archive/refs/heads/main.zip) or clone it:
   ```
   git clone https://github.com/NumaNumaNuma/anti-spoil.git
   ```
2. Open Chrome and go to `chrome://extensions`
3. Enable **Developer mode** (toggle in the top-right)
4. Click **Load unpacked**
5. Select the `anti-spoil` folder

The extension is now active on all YouTube pages.

## Uninstall

Go to `chrome://extensions`, find **Anti Spoil**, and click **Remove**.

## License

[MIT](LICENSE)
