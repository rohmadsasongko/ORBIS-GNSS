<div align="center">

<img src="orbis_logo.png" alt="ORBIS" width="120">

# ORBIS

**A single desktop platform for drone & GNSS survey data — from analysis to recap to report.**

GNSS PPK / Static processing (RTKLIB demo5) and photogrammetry support, in one native Windows app.

![version](https://img.shields.io/badge/version-1.7.1-2563eb) ![platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-444) ![license](https://img.shields.io/badge/license-Proprietary-555)

### ⬇️ [Download the latest installer](../../releases/latest)

</div>

---

## ✨ Highlights

- **Automatic PPK** — one click runs the RTKLIB demo5 kinematic solve
  (auto forward/backward selection) **plus a built-in QC report** that tells
  you honestly how far the two passes agree, per epoch, with plain-language
  advice — so a "100% Fix" can never mislead you again.
- **Automatic photo-mismatch detection & tagging** — Photo QC matches every
  photo to its event mark by EXIF time (camera clock offset found
  automatically), flags test shots / missing events, quarantines them in one
  click (undo-able), then geotags — photo count always equals event count.
- **Browser-style workspace tabs** — run several jobs side by side; a solve
  keeps running while you review another flight in a second tab.

## Install (Windows 10/11, 64-bit)

1. Download **`ORBIS_Setup_x.y.z.exe`** from the [Releases page](../../releases/latest).
2. Run it — **no administrator rights required** (installs per-user under `%LOCALAPPDATA%\Programs\ORBIS`).
3. The Microsoft WebView2 runtime is bundled and installed automatically if your PC doesn't already have it (works offline).
4. Launch ORBIS from the Start Menu / Desktop shortcut.

> If Windows SmartScreen appears: **More info → Run anyway.**

## Activation (one-time, free)

ORBIS is **free but requires a one-time activation key per PC**:

1. On first launch you'll see the **Activate ORBIS** screen.
2. Fill the **"Request a key"** form (Name · Email · Organisation) and click **Send request** — your request is emailed to the developer.
3. You'll receive your activation key by email — paste it into **"Already have a key?"** → **Activate**.

Activation is **permanent** and works fully **offline** afterwards. Updates and reinstalls keep your activation.

## Features

| Tab | What it does |
|-----|--------------|
| **UBX Viewer** | u-blox flight log analysis |
| **MRK Viewer** | DJI photo position explorer |
| **Event.pos Viewer** | RTKLIB event-position explorer (map · charts · table · export · **Photo QC · Photo geotag**) — folder or single file |
| **OBS Viewer** | RINEX `.obs` batch scanner |
| **Baseline Check** | Base ↔ rover quality — base RINEX 2/3 / UBX / .R; rover MRK / UBX / .pos / .sbg / RINEX |
| **RINEX Observe** | RINEX analysis & tools — merge · cut · decimate · **version convert (2.11 ↔ 3.x)** |
| **iBASE Viewer** | Base-station UBX `.R` scanner |
| **SBG Viewer** | Trinity LiDAR `.sbg` scanner |
| **Time Sync** | Base ↔ Rover overlap checker |
| **Processing** | GNSS PPK / Static via RTKLIB demo5 — auto F/B, **solution QC**, Photo QC, geotag |

Plus interactive maps & charts, photogrammetry helpers (auto photo IDs, camera-position CSV export), and a built-in self-updater.

## Updates

ORBIS checks for new versions automatically and can install them in one click
(**About → Check for updates**).

## License & contact

Proprietary software — **© 2026 Rohmad Sasongko. All rights reserved.**
The installer is provided for use; redistribution or reverse-engineering is not permitted.

**Questions / request a key:** rohmadaja777@gmail.com

---

*ORBIS — built by Rohmad Sasongko, GNSS & photogrammetry surveyor.*
