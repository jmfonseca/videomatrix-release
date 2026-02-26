# VideoMatrix v1.0.7 Release Notes

**Release Date**: February 26, 2026
**Distribution**: macOS Standalone App (Apple Silicon & Intel)

## What's New in v1.0.7

### Improved Installation Experience

✨ **Enhanced DMG Installer**
- DMG now includes Applications folder shortcut for easy drag-and-drop installation
- Users can simply drag VideoMatrix to the Applications folder icon
- Professional macOS installation experience matching Apple's standards

### Technical Details

- **File**: VideoMatrix.dmg
- **Size**: 41MB (compressed)
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
- **Internet**: Required for first-time ffmpeg download (if needed)

## What VideoMatrix Does

VideoMatrix is a local macOS tool that combines video clips from multiple categorized folders (e.g., Hook, Meat, CTA) into every possible permutation. Perfect for generating ad creative variations at scale.

### Key Features

- ✅ Combinatorial video generation from multiple folders
- ✅ Unique ID assignment for each output (e.g., R3421_hook1_meat2_cta3.mp4)
- ✅ CSV manifest with source tracking
- ✅ Optional background music mixing
- ✅ No re-encoding (fast concat with `-c copy`)
- ✅ Native macOS app with beautiful UI
- ✅ No Python installation required

## Support

For issues or questions:
- Check the built-in README
- Review the CSV manifest for combination details
- Ensure all source videos have matching codecs/resolution for best results

## Changelog

### v1.0.7 (2026-02-26)
- Enhanced DMG installer with Applications folder shortcut
- Improved installation user experience
- Updated distribution packaging

### Previous Versions
- v1.0.6: Auto-update installation improvements
- v1.0.3: Automatic update installation with one-click install & relaunch
- Earlier: Initial releases with core video multiplier functionality

---

**Built with**: Python 3.14, pywebview, PyInstaller
**Code Signed**: Mystic Star Lda
**Notarization**: Apple-verified for macOS Gatekeeper
