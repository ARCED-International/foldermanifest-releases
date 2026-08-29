# FolderManifest — Folder Compare, Duplicate Finder & File Integrity Toolkit

**Know exactly what's in any folder. Instantly.**

FolderManifest is a local-first desktop app for **Windows, Linux, and macOS** that helps you compare folders, find duplicate files, verify file integrity with SHA-256 checksums, monitor folders for changes, and archive projects with proof. Everything runs on your machine — no cloud, no account required.

> Official downloads and auto-update files. App source is maintained privately; this repo hosts signed release binaries only.

---

## Download

### Windows

[![Download for Windows](https://img.shields.io/badge/Download-Windows%20Installer-0078d4?style=for-the-badge&logo=windows)](https://github.com/arced-international/foldermanifest-releases/releases/latest/download/FolderManifest-Setup.exe)

- **Installer (recommended):** [`FolderManifest-Setup.exe`](https://github.com/arced-international/foldermanifest-releases/releases/latest/download/FolderManifest-Setup.exe) — installs with auto-update
- **Portable:** [`FolderManifest-Portable.exe`](https://github.com/arced-international/foldermanifest-releases/releases/latest/download/FolderManifest-Portable.exe) — run without installing

> Windows builds are signed with Azure Artifact Signing (Microsoft-verified publisher). No SmartScreen warning.

### Linux

[![Download AppImage](https://img.shields.io/badge/Download-Linux%20AppImage-f97316?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/arced-international/foldermanifest-releases/releases/latest/download/FolderManifest.AppImage)

- **AppImage:** [`FolderManifest.AppImage`](https://github.com/arced-international/foldermanifest-releases/releases/latest/download/FolderManifest.AppImage) — runs on any distro, no install needed
- **`.deb`:** [`FolderManifest.deb`](https://github.com/arced-international/foldermanifest-releases/releases/latest/download/FolderManifest.deb) — Ubuntu / Debian / Mint
- **`tar.gz`:** [`FolderManifest.tar.gz`](https://github.com/arced-international/foldermanifest-releases/releases/latest/download/FolderManifest.tar.gz) — other distributions

---

## What it does

| Feature | Detail |
|---|---|
| **Folder compare** | Compare two folders side by side — see added, removed, and modified files instantly |
| **File compare** | Compare two files by content, size, or metadata |
| **Duplicate file finder** | Detect duplicate files by SHA-256 content hash — even when names differ. Duplicates go to a reversible Recovery Bin, never permanently deleted |
| **File integrity & checksums** | CRC32 and SHA-256 checksum calculator for any file; save a folder snapshot and verify it later — prove exactly what changed |
| **Folder monitor** | Watch a folder in the background from the tray; log every file added, removed, or changed with history and CSV export |
| **Safe Archive** | Copy folders to local storage, S3, or Google Drive with SHA-256 manifests and reports that prove what arrived — resumable, verifiable transfers |
| **Auto Organize** | Build a reviewable cleanup plan from rules, apply after approval, undo anytime |
| **Spreadsheet tools** | Clean up and deduplicate CSV / XLSX data |
| **Reports** | Interactive HTML, CSV, Markdown, and JSON exports for audits and automation |
| **CLI** | Full command-line interface with stable JSON output and exit codes for scripting, cron, CI/CD, and AI agents |
| **Offline & private** | Runs entirely local — files never leave your machine unless you export |

**Free browser-based tools** (no install): [compare files online](https://www.foldermanifest.com/tools/compare-files), [compare folders online](https://www.foldermanifest.com/tools/folder-compare), [find duplicates online](https://www.foldermanifest.com/tools/find-duplicates), [checksum calculator](https://www.foldermanifest.com/tools/checksum-calculator).

---

## Who uses it

- **IT & sysadmins** verifying backup integrity and software deployments
- **Legal & compliance** teams proving file integrity for audits
- **Archivists & researchers** tracking long-term dataset changes
- **Developers** diffing project folders between environments
- **Photographers & editors** deduplicating media libraries safely
- **Anyone** who ever asked *"what changed in this folder?"*

---

## Frequently asked questions

**How do I compare two folders for differences?**
Open FolderManifest, choose Compare Folders, pick both directories — added, removed, and modified files appear side by side. Export the result as HTML, CSV, Markdown, or JSON.

**How do I find and remove duplicate files safely?**
Find Duplicates scans by content hash (SHA-256), so renamed copies are still caught. Duplicates are moved to the Recovery Bin — fully reversible, nothing is deleted without your approval.

**Can I verify a folder hasn't changed?**
Yes. Save a folder snapshot with Verify Changes; later, re-check it and get a verifiable SHA-256 fingerprint showing exactly which files were added, removed, or modified.

**Does it work offline?**
Completely. FolderManifest is local-first — no cloud dependency, no account needed to scan, compare, or verify.

**Is there a command line?**
Yes — every feature is available via CLI with stable JSON output and exit codes, ready for Task Scheduler, cron, CI/CD pipelines, and AI agents.

---

## Pricing

7-day full-access free trial (no credit card). Then **$39 once** for a lifetime single-device license with a 30-day money-back guarantee. [Buy a license →](https://www.foldermanifest.com/pricing)

---

## Reviews & listings

- [Product Hunt](https://www.producthunt.com/products/foldermanifest)
- [G2 (4.9/5)](https://www.g2.com/products/foldermanifest/reviews)
- [SourceForge](https://sourceforge.net/projects/foldermanifest/)
- [AlternativeTo](https://alternativeto.net/software/foldermanifest/)

---

## License & source

FolderManifest is proprietary software. © ARCED International LLC.
Binaries here are governed by the [EULA at foldermanifest.com/eula](https://www.foldermanifest.com/eula).
Source code is private.

**Website:** [foldermanifest.com](https://www.foldermanifest.com)
**Support:** [contact@foldermanifest.com](mailto:contact@foldermanifest.com)
