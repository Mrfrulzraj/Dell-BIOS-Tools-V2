<p align="center">
  <img src="https://github.com/Mrfrulzraj/Dell-BIOS-Tools-V2/blob/5ecf11fc2f09a52d619f42b18cf55e98d4cd8bda/logo.png" alt="Logo" width="200"/>
</p>
# Dell BIOS Tools V2.1

A professional GUI application for Dell BIOS management, featuring BIOS unlocking and Service Tag extraction capabilities.

![Dell BIOS Tools](https://img.shields.io/badge/Version-2.1-blue) ![Platform](https://img.shields.io/badge/Platform-Windows-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## Features

### 🔓 BIOS Unlocker Tool
- Patch BIOS files to unlock advanced settings
- Automatic Intel signature detection
- Pattern-based patching for Dell BIOS files
- Detailed logging of patching process
- Safe operation with backup preservation

### 🏷️ Service Tag Extractor
- Extract service tags from BIOS dump files
- Multiple tag occurrence detection
- UTF-16LE encoding support
- Detailed offset information
- Most likely tag identification

## Installation

### Prerequisites
- Windows 7/8/10/11
- .NET Framework 4.5 or later (for PyInstaller builds)
- Administrative privileges (recommended for BIOS operations)

### Running from Source
1. Install Python 3.7 or later
2. Install required packages:
   ```bash
   pip install tkinter
