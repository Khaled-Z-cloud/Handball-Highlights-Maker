<p align="center"><img src="docs/logo.png" width="140" alt="Handball Highlights Maker logo"></p>

<h1 align="center">Handball Highlights Maker</h1>
<p align="center">Turn a full handball match recording into its highlights — automatically.<br>Free for Windows · works offline <br>Tunation</p>

---

## What it does

Handball Highlights Maker turns a full handball match recording into its highlights.
Drop a match video into the app and draw a box around the on-screen scoreboard. Handball Highlights Maker reads the score, finds every goal, and cuts a clip around each one. You can then fine-tune every clip and export the goals as separate clips and/or one combined highlights video — with elegant transitions and your own watermark if you like.

<p align="center"><img src="docs/01_open_detect.gif" width="680" alt="Open a video and detect the goals"></p>

## Features

- **Automatic goal detection** from the scoreboard — works with any broadcast layout (you draw the box once).
- **Precise manual editing:** drag the clip handles, nudge by ±0.5 s (click & hold to repeat), zoom the timeline, scrub with the mouse wheel.
- **Reorder goals** by drag & drop, double-click to play a clip, add clips the app missed.
- **Undo / Redo** and **saved sessions** — pick up your editing exactly where you left off.
- **Export your way:** each goal separately, one combined video, or both. Automatic quality, or choose resolution, bitrate, codec and frame rate.
- **Transitions:** none, fade through black, or dissolve.
- **Watermark:** place, resize and crop your logo on a virtual screen; it is applied identically at any video resolution.
- **Presets, themes, custom shortcuts:** dark (default) or light theme, every shortcut can be changed, settings can be saved as presets.
- **Offline & private:** your videos never leave your PC.

<p align="center"><img src="docs/02_trim.gif" width="680" alt="Trim clips with the handles"></p>

## Download

Go to the **[Releases](../../releases/latest)** page and download the latest `Handball-Highlights-Maker-…-Windows.zip`.

1. Unzip it anywhere (keep all the files together in the folder).
2. Run **`Handball Highlights Maker.exe`**.

No installation and no separate programs are needed. In the app, **Help → Check update** tells you when a new version is available.

> **Windows SmartScreen:** because the app is new and not code-signed, Windows may show *"Windows protected your PC"*. Click **More info → Run anyway**.

## Quick start

1. **Open a video** — drag it into the window or click *Open Video*.
2. **Draw a box** tightly around the two score numbers on the scoreboard (leave the match clock out if you can).
3. Wait while the goals are detected, then select any goal in the list and adjust its start/end if needed.
4. Click **Export**.

The full illustrated manual is inside the app: **Help → How to**.

<p align="center"><img src="docs/07_export.gif" width="680" alt="Export window"></p>

## Default keyboard shortcuts

| Action | Shortcut | Action | Shortcut |
|---|---|---|---|
| Play / pause | `Space` | Add clip at playhead | `A` |
| Play selected clip | `P` | Delete clip | `Del` |
| Previous / next clip | `↑` / `↓` | Delete all goals | `Ctrl+Shift+D` |
| Start earlier / later (0.5 s) | `Ctrl+←` / `Ctrl+→` | Undo / Redo | `Ctrl+Z` / `Ctrl+Y` |
| End earlier / later (0.5 s) | `Alt+←` / `Alt+→` | Save session | `Ctrl+S` |

All shortcuts can be changed in **Settings → Shortcuts**.

## Tips

- The scoreboard on TV usually updates a little *after* the goal, so clips start 20 s before the detected score change by default. Change this in Settings.
- If goals are missed or wrong, draw the scoreboard box tighter around the two numbers, or add clips manually.
- Dissolve transitions with 50+ clips can be slow; *Fade through black* is much lighter.

## Frequently asked questions

**Is it really free?** Yes — see the license below.
**Does it upload my videos?** No. Everything runs on your computer. The only network access is *Check update*.
**Which video formats work?** MP4, MKV, MOV, AVI, TS, M4V, WMV and WebM.
**Where are my settings stored?** In `%APPDATA%\HandballHighlightsMaker\` (settings, presets and your saved session).
**Mac / Linux?** Not available yet.

## Feedback & bugs

Found a bug or have an idea? Open an **[Issue](../../issues)** and, if you can, attach a screenshot of the scoreboard and the video resolution.

## License

Handball Highlights Maker is **free software for you to use, but it is not open source**. You may use it free of charge, including to make videos you publish or sell, but you may not copy, modify, resell or redistribute the app. See [LICENSE](LICENSE) for the full terms and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for the open-source components it uses.

## Author

**Khaled Zerrim** — Tunisia 🇹🇳 · [github.com/Khaled-Z-cloud](https://github.com/Khaled-Z-cloud/)
