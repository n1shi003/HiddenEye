# 👁 HiddenEye

> **Uncover what’s hiding in plain sight.**

HiddenEye scans your chosen path and surfaces everything suspicious in a clean, dark-themed dashboard. Toggle detection modules on/off, adjust recursion depth, and filter results by category — all in real time.

---

## ✨ Features

- 🔍 **Hidden File Detection** — Uncovers Windows hidden attributes (`attrib:H`), and macOS `chflags:hidden` items.
- 🧩 **Double-Extension Spoofing** — Flags dangerous files disguised as safe ones (e.g., `photo.jpg.exe`).
- 🎭 **RTL Override Detection** — Spots Unicode bidirectional tricks used to spoof filenames.
- 🔐 **Sensitive Keyword Scan** — Auto-detects filenames containing `password`, `wallet`, `id_rsa`, `.env`, `token`, and more.
- 🧪 **Magic-Byte Mismatch** — Identifies files whose content doesn't match their extension (e.g., a ZIP named `.jpg`).
- 🌡 **Entropy Analysis** — Highlights high-randomness files that may be encrypted, packed, or obfuscated.
- 🖼 **Steganography Detection** — Reveals data appended after JPEG/PNG EOF markers.
- 🗂 **NTFS ADS Scanner** *(Windows)* — Discovers Alternate Data Streams hiding behind innocent files.
- 🧭 **Regex Pattern Search** — Hunt custom filename patterns across any directory.
- 📂 **Smart Recursion** — Scan deep with configurable depth limits, while safely skipping system folders.
- 🛡 **System Folder Protection** — Automatically avoids critical OS directories to prevent accidental damage.

---

## 🖥 Platform Support

| Platform | Package | Status |
|----------|---------|--------|
| Windows | `HiddenEye-win32-x64.zip` | ✅ Native |
| macOS | `HiddenEye-darwin-x64.zip` | ✅ Native |
| Linux | `HiddenEye-linux-x64.tar.gz` | ✅ Native |

> ⚠️ **Note:** macOS Gatekeeper and Windows SmartScreen may show a warning on first launch because HiddenEye is not code-signed. This is expected for independent security tools.

---

## 🛡️ Safe & Ethical Use

HiddenEye is designed for **authorized security analysis** on systems you own or have explicit permission to audit. It never modifies, deletes, or exfiltrates files — it only reads metadata and reports findings.

> **Always obtain proper authorization before scanning any system you do not own.**

---

## 📦 Releases

Check the [Releases](../../releases) page for the latest builds and changelogs.

---

*Built with precision for the cybersecurity community.*
