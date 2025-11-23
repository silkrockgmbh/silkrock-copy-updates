# silkrock copy - Auto-Updates

<div align="center">

<img src="assets/SILKROCK-LOGO-PURPLE.png" alt="Silkrock Logo" width="400">

**Professional File Transfer Suite**

Fast, reliable, and verified file copying for professionals.

[![Latest Release](https://img.shields.io/github/v/release/silkrockgmbh/silkrock-copy-updates?label=Latest%20Version)](https://github.com/silkrockgmbh/silkrock-copy-updates/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/silkrockgmbh/silkrock-copy-updates/total)](https://github.com/silkrockgmbh/silkrock-copy-updates/releases)
[![License](https://img.shields.io/badge/license-Proprietary-blue)](https://silkrock.de)

</div>

---

## 📥 Download Latest Version

**[→ View All Releases and Download](https://github.com/silkrockgmbh/silkrock-copy-updates/releases/latest)**

Get the latest version of silkrock copy for your platform:

### Windows

-   Download the `.msi.zip` file (e.g., `silkrock copy_1.0.5_x64_en-US.msi.zip`)

### macOS

-   **Apple Silicon (M1/M2/M3)**: Download the `aarch64.dmg` file
-   **Intel**: Download the `x64.dmg` file

> **⚠️ IMPORTANT - macOS Users:**
>
> macOS may block the app on first launch due to Gatekeeper security. If the app won't open:
>
> **Option 1 - Right-click method (Recommended):**
>
> 1. Right-click (or Control+click) on **silkrock copy.app** in your Applications folder
> 2. Select **Open** from the menu
> 3. Click **Open** in the dialog that appears
>
> **Option 2 - Remove quarantine attribute (Advanced):**
>
> Open Terminal and run:
>
> ```bash
> xattr -cr /Applications/silkrock\ copy.app
> ```
>
> This removes the quarantine flag that macOS applies to downloaded applications.

### Linux

-   Download the `.AppImage.tar.gz` file (e.g., `silkrock-copy_1.0.5_amd64.AppImage.tar.gz`)
-   Extract and run the AppImage

---

## 🚀 What is silkrock copy?

**silkrock copy** is a professional-grade file transfer application designed for:

-   **🎬 Video Production Teams** - Copy large video files with integrity verification
-   **📸 Photographers** - Transfer photo libraries between storage devices
-   **💿 Media Professionals** - Duplicate and verify media assets
-   **🏢 IT Departments** - Reliable file deployment and backup

### Key Features

✅ **Checksum Verification** - Automatically verifies file integrity using multiple hash algorithms (MD5, SHA1, SHA256, xxHash)

✅ **Multi-Destination Copying** - Copy to multiple destinations simultaneously

✅ **Volume Detection** - Automatically detects and works with external drives

✅ **Progress Tracking** - Real-time progress with speed and ETA
✅ **MHL (ASC)** - Generate XML manifests per destination and verify against existing manifests

✅ **Error Recovery** - Intelligent retry mechanism for failed transfers

✅ **Multi-Format Reports** - Generate detailed reports in PDF, CSV, and TXT formats

✅ **Preset Management** - Save and reuse common copy configurations

✅ **Extension Filtering** - Filter files by type during copy operations

✅ **Auto-Updates** - Stay up-to-date automatically

---

## 🔒 Security & Privacy

-   All releases are **cryptographically signed** to ensure authenticity
-   No telemetry or data collection
-   Works completely offline after installation
-   Your files never leave your local network

---

## 📖 Installation

### Windows

1. Download the `.msi.zip` file
2. Extract the `.msi` installer
3. Run the installer and follow the prompts
4. The app will appear in your Start Menu

### macOS

1. Download the `.dmg` file for your Mac (Apple Silicon or Intel)
2. Open the `.dmg` file
3. Drag **silkrock copy** to your Applications folder
4. **Important**: See the macOS security warning above for first-time launch instructions

### Linux

1. Download the `.AppImage` file
2. Make it executable: `chmod +x silkrock-copy_*.AppImage`
3. Run it: `./silkrock-copy_*.AppImage`

---

## 🔄 Auto-Updates

silkrock copy includes automatic update checking:

1. The app checks for updates on startup
2. Click the update button in the header to manually check
3. When an update is available, you'll see a dialog with release notes
4. Click "Update Now" to download and install automatically
5. The app will restart with the new version

All updates are downloaded from this repository and verified with cryptographic signatures.

---

## 📊 Copy Reports

silkrock copy automatically generates comprehensive reports for every copy operation.

### Available Formats

-   **PDF** - Professional formatted report with visual layout
-   **CSV** - Excel-compatible spreadsheet for data analysis
-   **TXT** - Plain text report for easy reading

### Report Contents

Each report includes:

-   **Operation Summary** - Total files, sizes, duration, success/failure counts
-   **Settings Snapshot** - Complete record of all settings used for the operation
-   **Destination Details** - Statistics for each copy destination
-   **File-Level Details** - Individual file status, checksums, and errors (in "Full" layout)
-   **Metadata** - Preset info, app version, checksum algorithm, timestamps

### CSV Format

The CSV format uses a normalized schema with a `RecordType` column:

-   **Summary** rows contain overall operation statistics
-   **Destination** rows show per-destination stats
-   **File** rows list individual file details (Full layout only)

The CSV files are optimized for Excel:

-   UTF-8 BOM encoding (automatic Excel recognition)
-   CRLF line endings (Windows standard)
-   RFC4180-compliant quoting and escaping
-   ISO-8601 timestamps, sizes in bytes, durations in milliseconds

### Finding Your Reports

Reports are saved to:

-   **Windows**: `C:\Users\[YourName]\Documents\SilkRock Reports\`
-   **macOS**: `~/Documents/SilkRock Reports/`
-   **Linux**: `~/Documents/SilkRock Reports/`

Each copy operation creates a timestamped folder containing all selected formats plus a `manifest.json` file.

You can customize report settings in **Settings → General → Copy Reports**.

---

## 📋 System Requirements

### Windows

-   Windows 10 or later (64-bit)
-   4 GB RAM minimum
-   100 MB free disk space

### macOS

-   macOS 10.13 (High Sierra) or later
-   Apple Silicon (M1/M2/M3) or Intel processor
-   4 GB RAM minimum
-   100 MB free disk space

### Linux

-   64-bit Linux distribution
-   GTK3 support
-   4 GB RAM minimum
-   100 MB free disk space

---

## 🆘 Support

For technical support, feature requests, or bug reports:

-   **Website**: [https://silkrock.de](https://silkrock.de)
-   **Documentation**: See release notes for version-specific information
-   **Issues**: Check existing releases for known issues

---

## 📜 License

Copyright © 2025 Silkrock GmbH. All rights reserved.

This software is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.

---

## 🏢 About Silkrock GmbH

Silkrock GmbH specializes in professional media workflow solutions. We build tools that help creative professionals work more efficiently and reliably.

Visit us at [silkrock.de](https://silkrock.de)

---

<div align="center">

**Made with ❤️ by Silkrock GmbH**

</div>
