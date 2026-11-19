<div align="center">

<img src="assets/lexidictate-icon.png" width="128" height="128" alt="LexiDictate">

# LexiDictate

**Lightweight, system-wide voice dictation for Windows powered by Gemini Live & Flash.**

[![Latest release](https://img.shields.io/github/v/release/lexi-apps/lexi-dictate?label=latest&color=2ea043)](https://github.com/lexi-apps/lexi-dictate/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/lexi-apps/lexi-dictate/total?color=0969da)](https://github.com/lexi-apps/lexi-dictate/releases)
![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20(64--bit)-0078d4)
![Price](https://img.shields.io/badge/price-free-8250df)
[![Support on Patreon](https://img.shields.io/badge/Patreon-support-f96854?logo=patreon&logoColor=white)](https://www.patreon.com/cw/LexiApps)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-tip-FFDD00?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/lexiapps)
[![Website](https://img.shields.io/badge/Website-lexi--apps.github.io-ff5a36)](https://lexi-apps.github.io/)

### [⬇ Download the latest version](https://github.com/lexi-apps/lexi-dictate/releases/latest)

<sub>Run <code>LexiDictate-Setup-0.2.0.exe</code> from the latest release.</sub>

[Features](#features) · [Screenshots](#screenshots) · [Installation](#installation) · [FAQ](#faq)

<br>

<img src="assets/screenshots/general.png" width="820" alt="LexiDictate Settings Window">

</div>

---

## Features

| | |
|---|---|
| 🎙️ **Focus-aware floating mic pop-up** | Automatically appears near active text fields across browsers and desktop apps, hides on non-editable clicks, and never steals focus from what you are typing. |
| ⚡ **Real-time live transcript preview** | Streams partial words onto the compact floating capsule as you speak via Gemini Live, then delivers crisp final text right after you stop. |
| ✍️ **Smart sentence polishing** | Removes filler words, resolves inline self-corrections, fixes punctuation, and naturally preserves bilingual English technical terms mixed into speech (also supports Verbatim & Translate-to-English modes). |
| 🧠 **Curated fast Gemini models** | Offers vetted Live (`gemini-3.5-transcribe-live`, `gemini-3.1-flash-live-preview`, `gemini-2.5-flash-native-audio-latest`, `gemini-3.8-live`) and Flash Polish (`gemini-3.1-flash-lite`, `gemini-3-flash-preview`, `gemini-3.5-flash-lite`, `gemini-3.5-flash`, `gemini-3.8-flash`) presets with speed & quality notes. |
| 🔁 **Multi-key 429 automatic failover** | Add multiple Google AI Studio API keys in priority order — if one hits a rate limit (`429`), LexiDictate switches seamlessly to your next ready key, with transient `503` model fallback built in. |
| ⌨️ **One-click keyboard & mouse shortcuts** | Bind single keys (like `Right Alt` or `F9`), combinations (`Ctrl+Space`), or mouse side buttons (`Mouse 4/5`) by simply pressing them — no manual key names to type. |
| 🎨 **Matte Obsidian & Light Ivory UI** | Clean native Windows interface with 4 live accent presets (`Ivory`, `Emerald`, `Amber`, `Steel`), custom vocabulary hints, and local dictation history. |
| 📋 **Clipboard-safe text insertion** | Restores your previous clipboard contents cleanly after pasting, or type directly via Unicode input without touching the clipboard. |
| 🔒 **Local-first privacy** | Zero ads, zero telemetry, zero intermediary servers. API keys stay strictly in your local Windows profile (`%APPDATA%\LexiDictate\config.json`). |
| 🌍 **Bilingual interface** | Full English and Turkish UI with instant live switching. |

## Screenshots

### API Key Pool & Curated Model Selector

<div align="center">
<img src="assets/screenshots/api-pool.png" width="820" alt="LexiDictate API Key Pool and Model Selector">
</div>

| Interactive Shortcuts | Floating Pop-up States |
|---|---|
| <img src="assets/screenshots/shortcuts.png" alt="LexiDictate Shortcuts"> | <img src="assets/screenshots/popup-states.png" alt="LexiDictate Floating Pop-up States"> |

## Installation & Quick Start

1. Download **`LexiDictate-Setup-0.2.0.exe`** from the [latest release](https://github.com/lexi-apps/lexi-dictate/releases/latest).
2. Run the installer. Because the executable is not code-signed yet, Windows SmartScreen may show a warning: choose **More info → Run anyway**.
3. Launch **LexiDictate** and create a free API key at [Google AI Studio](https://aistudio.google.com/apikey).
4. Paste your key in **API Key Pool**, choose your preferred **Push-to-Talk** or **Toggle** shortcut in **Shortcuts**, click any text box, and start speaking.

**Requirements:** Windows 10 or Windows 11 (64-bit).

## FAQ

<details>
<summary><b>Is LexiDictate free?</b></summary>

Yes. LexiDictate is completely free with no ads, subscriptions, or paid tiers.
</details>

<details>
<summary><b>Why do I use my own Google AI Studio API key?</b></summary>

Using your own API key keeps your audio and dictated text moving directly between your PC and Google's API with low latency and no third-party proxy, account sign-up, or usage cap imposed by us.
</details>

<details>
<summary><b>What happens if an API key hits a 429 rate limit?</b></summary>

You can add multiple Google AI Studio API keys in **API Key Pool**. Whenever a key hits a `429` quota limit, LexiDictate places it in cooldown and automatically switches to the next available key without interrupting your workflow.
</details>

<details>
<summary><b>Does LexiDictate collect telemetry or upload my files?</b></summary>

No. Audio is only captured while a dictation session is active, and your settings, API keys, and recent history remain strictly local on your machine.
</details>

## Support Lexi

Lexi apps are free and have no ads. If LexiDictate saves you time, you can support development on Patreon or Buy Me a Coffee:

[![Support Lexi on Patreon](https://img.shields.io/badge/Support%20Lexi%20on-Patreon-f96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/cw/LexiApps)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a-Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/lexiapps)

## More from Lexi Apps

- **Website:** [lexi-apps.github.io](https://lexi-apps.github.io/)
- **[Lexi Download Manager](https://github.com/lexi-apps/lexi-download-manager):** Free multi-part download manager for Windows with video site downloads, torrents, and a browser extension.
- **[Lexi Ren'Py Translator](https://github.com/lexi-apps/lexi-renpy-translator):** Translates Ren'Py visual novels cleanly with glossary support.

## License

LexiDictate is freeware and free to use. The application source code is proprietary and is not published in this distribution repository.

## Contact

Bug reports and questions: **lexiapps@protonmail.com**

<div align="center"><sub>© Lexi Apps</sub></div>
