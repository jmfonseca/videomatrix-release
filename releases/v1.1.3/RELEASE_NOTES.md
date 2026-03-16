# VideoMatrix v1.1.3 Release Notes

**Release Date**: March 16, 2025
**Distribution**: macOS Standalone App (Apple Silicon & Intel)

## What's New in v1.1.3

- **Fix mixed-format video support**: Clips from different sources (iPhone HEVC, standard H.264) can now be combined in any order without black frames or color issues
- **Pre-encode optimization**: Each unique clip is now encoded once, then assembled into all combinations — significantly faster for large sets
- **BT.709 color conversion toggle**: New checkbox in settings to convert HDR/BT.2020 clips to standard BT.709 color space (enabled by default, recommended for social media)
- **Fixed black frames**: Last segment no longer shows black when mixing clips with different frame rates or codecs

## Installation Instructions

1. **Download** VideoMatrix.dmg
2. **Double-click** to mount the disk image
3. **Drag** VideoMatrix.app to the Applications folder
4. **Launch** from Applications folder

## System Requirements

- **macOS**: 11.0 (Big Sur) or later
- **Architecture**: Apple Silicon (M1/M2/M3) and Intel
- **Internet**: Not required (ffmpeg is bundled)

---

**Code Signed**: Mystic Star Lda — Notarized by Apple
