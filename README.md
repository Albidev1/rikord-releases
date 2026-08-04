# Rikord

League of Legends recorder with an automatic montage forge. It records your
matches on its own, marks every kill, death and assist on the timeline, and
stitches your best moments into one video.

## Download

### [→ Download the latest installer](https://github.com/Albidev1/rikord-releases/releases/latest)

Take `Rikord-Setup-<version>.exe` from **Assets** and run it. Windows 10/11,
64-bit. It installs for the current user only, so there is no admin prompt.

Windows will say **"Windows protected your PC"** — the installer is not
code-signed yet. Click **More info → Run anyway**.

## What it does

- **Records on its own.** It watches for a League match and starts and stops
  with the game. There is a Record button for everything else.
- **Marks the moments.** Every kill, death and assist sits on the timeline
  under the video. Click one and the clip range is already set around it.
- **Forges montages.** Pick games and which moments you want, set how many
  seconds before and after, and it cuts and stitches them into one video.
- **Brings its own ffmpeg**, and picks the right encoder for your machine —
  NVIDIA, AMD, Intel or CPU.

Recordings land in `Videos\Rikord`. Nothing is uploaded anywhere.

## Updates

Rikord checks here for new versions. When one lands, the app shows
**Update available** in the sidebar — one click downloads it, one more
installs it. It never interrupts a recording.

---

This repository only carries the installers. Issues and ideas are welcome.
