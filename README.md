# MovieHub — Next-Generation Circle FTP Cinema Experience

<div align="center">

![MovieHub App Banner](/logo.png)

**A high-performance, dedicated desktop cinema application for ultra-fast Circle FTP streaming.**  
Enjoy high-bitrate movies and TV series at unmetered ISP speeds with full multi-track audio switching, embedded subtitles, and an award-winning OTT interface.

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#system-requirements)
[![Audio Engine](https://img.shields.io/badge/Audio-Dual%20Audio%20%26%20Multi--Channel%20Support-E50914?style=for-the-badge&logo=dolby&logoColor=white)](#the-solution)
[![Network](https://img.shields.io/badge/Network-Circle%20FTP%20%2F%20BDIX%20Peered-10B981?style=for-the-badge)](#zero-configuration-streaming)
[![Setup](https://img.shields.io/badge/Setup-Zero%20Dependency%20Portable%20%2F%20Installer-6366F1?style=for-the-badge)](#getting-started)

</div>

---

## Overview

**MovieHub** transforms how you experience content from local ISP FTP networks. If your internet service provider (ISP) supports **Circle FTP** (or high-speed local BDIX peering), MovieHub gives you a native, buttery-smooth streaming experience rivaling premium streaming services — with zero buffering, instant seek times, and true multi-audio support.

Gone are the days of dealing with broken web players, muted audio files, or tedious VLC link-copying routines. Just launch MovieHub, pick your title, and start watching.

---

## The Problem: Why the Traditional Circle FTP Web Player Fails

For years, users streaming content from local ISP FTP portals have faced major limitations with web-based players:

### 1. Silent Dual-Audio & Multi-Track Releases
Most high-definition movies and anime releases contain **multi-track audio** (e.g., Dual Audio Hindi + English, Japanese + English, or 5.1/7.1 surround sound encoded in AC3, EAC3, or DTS). Standard web browsers **cannot natively decode or switch alternate audio tracks**. On the Circle FTP website, this causes:
- Complete silence when the primary track is an unsupported codec.
- Inability to switch to your preferred language (e.g., being stuck in an unwanted dubbed language).

### 2. Broken or Missing Subtitles
Modern video releases store soft subtitles inside MKV/MP4 containers (SSA, ASS, SRT). The web player fails to parse or render these embedded subtitle tracks, leaving viewers without subtitles for foreign-language dialogues or anime.

### 3. The Hectic "VLC Workaround"
To bypass these web limitations, users previously had to:
1. Browse the web portal and locate the desired title.
2. Inspect or right-click to copy the raw streaming URL.
3. Open **VLC Media Player**.
4. Go to `Media -> Open Network Stream`, paste the URL, and click Play.
5. Manually configure the audio track and hunt for external subtitle files online.
6. **Repeat this entire friction-filled process for every single episode or movie.**

### 4. Outdated Browsing & Lack of Continuity
The standard FTP web portal resembles an old file directory or static catalog with no playback resume, no progress bars, no episode auto-progression, and no watchlist.

---

## The Solution: What MovieHub Solves

MovieHub bridges the gap between high-speed local network storage and modern media playback engineering:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        TRADITIONAL METHOD                              │
│                                                                        │
│   Circle FTP Web  ──►  Copy Stream URL  ──►  Open VLC  ──►  Find Subs  │
│   (No Audio/Subs)      (Manual Step)         (Clunky)       (Manual)   │
└────────────────────────────────────────────────────────────────────────┘
                                    VS
┌────────────────────────────────────────────────────────────────────────┐
│                       THE MOVIEHUB EXPERIENCE                          │
│                                                                        │
│   Click "Watch Now"  ─────────────────────────────────►  Flawless Play │
│   • Auto-Demuxed Dual Audio    • Embedded Subtitles     • Instant Seek │
│   • One-Click Language Switch  • Continue Watching      • 4K HDR UI    │
└────────────────────────────────────────────────────────────────────────┘
```

---

## Key Features & Capabilities

### Intelligent Universal Audio Engine
- **Flawless Multi-Audio Playback**: Intelligently inspects the stream's audio layout and demuxes multi-channel or incompatible audio streams (AC3, EAC3 Dolby Digital, DTS) into universal high-fidelity audio on the fly.
- **One-Click Track Switching**: Effortlessly toggle between Hindi, English, Japanese, commentary, or alternate language streams right from the in-player control bar.
- **Zero Silence Guarantee**: No more missing dialogue or silent playback.

### Comprehensive Subtitle Support
- **Embedded Track Extraction**: Instantly parses and displays embedded subtitle tracks stored within the video file.
- **On-the-Fly Subtitle Synchronization**: Fine-tune subtitle timing (±0.5s, ±1.0s) directly while watching.
- **Custom Subtitle Loader**: Easily upload and load your own `.srt` or `.vtt` file directly into the player.

### Zero-Configuration Direct ISP Streaming
- **Native BDIX Peering**: If your Wi-Fi or LAN is connected to an ISP that provides Circle FTP access, MovieHub streams directly through your ISP’s gigabit local cache.
- **Zero Buffering**: Instant playback start times and instantaneous seek response without hitting international bandwidth caps.

### Native Cinema Player Suite
- **Keyboard Shortcuts**: Fully mapped controls (`Space` to play/pause, `Left`/`Right` arrows for ±10s seek, `Up`/`Down` for volume, `F` for Fullscreen, `M` to mute).
- **Playback Speed Controller**: From `0.75x` up to `2.0x` smooth speed scaling.
- **Smart Progress Tracking**: Automatically tracks where you left off with **Continue Watching** and visual progress bars.
- **Series Hub**: Multi-season tabs with one-click episode progression.

### Direct Link Streamer (`Direct Player`)
- Have an arbitrary FTP link, direct media URL, or local network video?
- Simply paste it into MovieHub's **Direct Player** to unlock all cinema controls, audio switching, and subtitle features without launching VLC.

### Modern Glassmorphic Cinema UI
- Deep OLED dark mode, progressive gradual blur header and dock, studio badge indicators (4K UHD, 1080p BluRay, Dual Audio), and animated catalog browsing.

---

## Feature Comparison

| Feature | Circle FTP Web Portal | VLC Manual Streaming | 🎬 **MovieHub Desktop** |
| :--- | :---: | :---: | :---: |
| **Instant 1-Click Play** | ✅ | ❌ *(Manual copy/paste)* | **✅ Instant** |
| **Dual Audio / Language Switch** | ❌ *(Muted / Not selectable)* | ✅ | **✅ 1-Click In-Player** |
| **Multi-Channel Audio (AC3/EAC3/DTS)** | ❌ *(Silent)* | ✅ | **✅ Universal Auto-Convert** |
| **Embedded Subtitles** | ❌ *(Broken)* | ✅ | **✅ Native In-Player** |
| **Subtitle Sync Adjustment** | ❌ | ✅ | **✅ Native Slider / Buttons** |
| **Continue Watching & Watchlist** | ❌ | ❌ | **✅ Persistent History** |
| **TV Series Season & Episode Hub** | ❌ *(Messy links)* | ❌ *(Manual file browsing)* | **✅ Visual Episode Grid** |
| **Requires External Software / VLC** | N/A | ❌ *(Requires VLC installed)* | **✅ Zero Dependencies Needed** |
| **Modern Streaming UI** | ❌ | ❌ | **✅ Premium OTT Interface** |

---

## System Requirements

- **Operating System**: Windows 10 or Windows 11 (64-bit)
- **Network**: Wi-Fi or Ethernet connection from an ISP that supports Circle FTP / BDIX local peering.
- **Dependencies**: **None.** The executable is completely self-contained. No external codecs, players, or runtimes are required.

---

## Getting Started

1. **Download**: Grab the latest `MovieHub Setup.exe` from the [Releases](../../releases) tab.
2. **Install**: Run the setup wizard.
3. **Stream**: Launch MovieHub while connected to your home Wi-Fi/Ethernet. Discover thousands of movies and TV series and stream instantly!

---

## Disclaimer

*MovieHub is an independent, client-side media player and interface. It does not host, upload, or index any media files on external servers. All playback streams are accessed directly from the user's local network ISP infrastructure via their existing ISP peering privileges.*
