# VideoMatrix v1.1.0 Release Notes

**Release Date**: March 3, 2026
**Distribution**: macOS Standalone App (Apple Silicon & Intel)

## What's New in v1.1.0

### Multi-Format Video Export

✨ **New Export Formats**
- Export combinations as MP4, MOV, or other formats
- Flexible output format selection in the UI

### Drag-and-Drop Folder Support

✨ **Drag Folders Directly onto the App**
- Drag and drop folders from Finder directly into the folder input fields
- No need to click "Browse" — just drag your Hook, Meat, CTA folders in

### Bundled ffmpeg

✨ **ffmpeg Included**
- ffmpeg is now bundled inside the app — no Homebrew or manual download required
- App works immediately after installation with no extra setup
- Automatic architecture detection (Apple Silicon / Intel)

### Filename Fix

- Output filenames now use hyphens instead of underscores in certain cases for cleaner naming

### Technical Details

- **File**: VideoMatrix.dmg
- **Size**: 23MB (compressed)
- **Code Signing**: Fully signed with Apple Developer ID
- **Notarization**: Apple-notarized for seamless installation
- **No Gatekeeper Warnings**: Users can install and launch without security prompts

## Installation Instructions

1. **Download** VideoMatrix.dmg
2. **Double-click** to mount the disk image
3. **Drag** VideoMatrix.app to the Applications folder
4. **Launch** from Applications folder

The app will open immediately without any security warnings!

## System Requirements

- **macOS**: 11.0 (Big Sur) or later
- **Architecture**: Apple Silicon (M1/M2/M3) and Intel
- **Disk Space**: ~102MB installed
- **Internet**: Not required (ffmpeg is bundled)

## What VideoMatrix Does

VideoMatrix is a local macOS tool that combines video clips from multiple categorized folders (e.g., Hook, Meat, CTA) into every possible permutation. Perfect for generating ad creative variations at scale.

### Key Features

- Combinatorial video generation from multiple folders
- Unique ID assignment for each output (e.g., R3421_hook1_meat2_cta3.mp4)
- CSV manifest with source tracking
- Optional background music mixing
- No re-encoding (fast concat with `-c copy`)
- Native macOS app with beautiful UI
- No Python installation required
- No ffmpeg installation required

## Changelog

### v1.1.0 (2026-03-03)
- Multi-format video export support
- Drag-and-drop folder support from Finder
- ffmpeg bundled — no external dependencies
- Underscore-to-hyphen filename fix

### v1.0.7 (2026-02-26)
- Enhanced DMG installer with Applications folder shortcut

### Previous Versions
- v1.0.6: Auto-update installation improvements
- v1.0.3: Automatic update installation with one-click install & relaunch
- Earlier: Initial releases with core video multiplier functionality

---

**Built with**: Python 3.9, pywebview, PyInstaller
**Code Signed**: Mystic Star Lda
**Notarization**: Apple-verified for macOS Gatekeeper
