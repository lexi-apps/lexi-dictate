<div align="center">

<img src="assets/lexidictate-icon.png" width="88" height="88" alt="LexiDictate">

# LexiDictate

**Speak anywhere on Windows. Paste clean text in ~0.5s — or highlight text and translate with `Alt + Q`.**

[![Latest release](https://img.shields.io/github/v/release/lexi-apps/lexi-dictate?style=flat-square&label=release&color=2ea043)](https://github.com/lexi-apps/lexi-dictate/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/lexi-apps/lexi-dictate/total?style=flat-square&color=0969da)](https://github.com/lexi-apps/lexi-dictate/releases)
![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-0078d4?style=flat-square)
[![Website](https://img.shields.io/badge/website-lexi--apps.pages.dev-ff5a36?style=flat-square)](https://lexi-apps.pages.dev/lexi-dictate/)
[![Discord](https://img.shields.io/badge/discord-community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/HN9eWThUn2)
[![Patreon](https://img.shields.io/badge/patreon-support-f96854?style=flat-square&logo=patreon&logoColor=white)](https://www.patreon.com/cw/LexiApps)
[![Buy Me a Coffee](https://img.shields.io/badge/buy%20me%20a%20coffee-tip-ffdd00?style=flat-square&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/lexiapps)

### [Download LexiDictate 0.8.6 for Windows](https://github.com/lexi-apps/lexi-dictate/releases/latest)

<sub>Run <code>LexiDictate-Setup-0.8.6.exe</code> · Windows 10 & 11 (64-bit) · 100% Freeware · Bring your own Gemini API key</sub>

<br>

<img src="assets/cards/lexidictate-demo.gif" width="880" alt="LexiDictate — Interactive Voice Dictation & Alt + Q Selection Translate Demo">

<sub>~14-second interactive highlight — live dictation &amp; Alt + Q selection translate · Click any feature card below for full 1600×900 detail · <a href="https://lexi-apps.pages.dev/lexi-dictate/">Watch full 31s 60fps showcase on website ↗</a></sub>

</div>

---

## See It in Action

<table>
  <tr>
    <td width="50%">
      <a href="assets/cards/card-translate.png"><img src="assets/cards/card-translate.png" alt="Quick Selection Translation with floating icon and Alt + Q"></a>
    </td>
    <td width="50%">
      <a href="assets/cards/card-modes.png"><img src="assets/cards/card-modes.png" alt="Smart Polish, Voice Commands and 14-Language Translation"></a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <a href="assets/cards/card-pool-game.png"><img src="assets/cards/card-pool-game.png" alt="Multi-Key 429 Failover and Game Mode Auto-Pause"></a>
    </td>
    <td width="50%">
      <a href="assets/cards/card-local.png"><img src="assets/cards/card-local.png" alt="100% Free, Direct Google AI Studio Connection, SHA-256 and Multi-Monitor DPI"></a>
    </td>
  </tr>
</table>

---

## At a Glance

- **Sub-Second Live Voice:** Hold `Right Alt` (or any key / mouse button), speak naturally, and paste into Discord, Chrome, VS Code, or any Windows text box in `~0.5s` without losing focus.
- **Quick Selection Translate (`Alt + Q`):** Highlight any snippet for a tiny translate icon (0 API calls until clicked) or press `Alt + Q`, with `TR ↔ EN` flip and clipboard protection.
- **Smart Polish, Commands & 14 Languages:** Strips fillers, resolves self-corrections, runs TR/EN voice commands (`new line`, `new paragraph`, `undo dictation`), or translates directly into 14 languages.
- **Multi-Key `429` Failover & Retry:** Rotate multiple Gemini API keys automatically on rate limits, plus one-click RAM-only **Retry** (auto-clears after 10 min).
- **Game Mode & Multi-Monitor Ready:** Auto-pauses in fullscreen/borderless/windowed games (whitelisting Snipping Tool, ShareX, Lightshot, OBS), supports mixed-DPI monitors (`HMONITOR`), and keeps Turkish `AltGr` (`@`, `€`) clash-free.
- **Local-First & Verified:** Zero ads, accounts, or middleman servers — API keys are encrypted at rest with Windows DPAPI (CurrentUser), plus fail-closed SHA-256 silent updates and privacy-redacted bug reports.

---

## Quick Start (30 Seconds)

1. Download and run **`LexiDictate-Setup-0.8.6.exe`** from the [latest release](https://github.com/lexi-apps/lexi-dictate/releases/latest) *(if SmartScreen prompts, choose **More info → Run anyway**)*.
2. Get a free API key from [Google AI Studio](https://aistudio.google.com/apikey) and paste it into **API Key Pool**.
3. Click any text box, hold **`Right Alt`**, speak, and release.

---

<details>
<summary><b>App Screens — Floating Capsule & Settings (5 screenshots)</b></summary>
<br>

| Floating Pop-up & Translation Card | General Settings |
|---|---|
| <img src="assets/screenshots/popup-states.png" alt="Floating Pop-up States"> | <img src="assets/screenshots/general.png" alt="General Settings"> |

| API Key Pool & Models | Shortcuts & Game Mode |
|---|---|
| <img src="assets/screenshots/api-pool.png" alt="API Key Pool"> | <img src="assets/screenshots/shortcuts.png" alt="Shortcuts and Game Mode"> |

<div align="center">
<img src="assets/screenshots/about.png" width="760" alt="About and Updates">
</div>

</details>

---

## FAQ

<details>
<summary><b>Is LexiDictate free?</b></summary>

Yes — 100% freeware with no ads, subscriptions, or accounts. You connect directly to Google AI Studio using your own API key.
</details>

<details>
<summary><b>Does selection translation use quota automatically?</b></summary>

No. Highlighting text sends zero API requests until you click the floating icon or press `Alt + Q`, and the last 20 translations are cached in RAM.
</details>

<details>
<summary><b>Does it interfere with games or my clipboard?</b></summary>

No. Game Mode automatically suspends hotkeys and active dictation in games, and clipboard insertion preserves screenshots/files while restoring previous text automatically.
</details>

<details>
<summary><b>Where is my data stored?</b></summary>

Strictly locally in `%APPDATA%\LexiDictate\config.json`, with your API key values encrypted via Windows DPAPI (CurrentUser scope). Audio is streamed directly to Google AI Studio only while dictating, and failed-session Retry audio lives solely in RAM for up to 10 minutes.
</details>

---

## Support & Links

[![Support Lexi on Patreon](https://img.shields.io/badge/Support%20Lexi%20on-Patreon-f96854?style=flat-square&logo=patreon&logoColor=white)](https://www.patreon.com/cw/LexiApps)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a-Coffee-ffdd00?style=flat-square&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/lexiapps)

- **Website:** [lexi-apps.pages.dev/lexi-dictate](https://lexi-apps.pages.dev/lexi-dictate/)
- **Discord:** [discord.gg/HN9eWThUn2](https://discord.gg/HN9eWThUn2)
- **More Apps:** [Lexi Download Manager](https://github.com/lexi-apps/lexi-download-manager) · [Lexi Ren'Py Translator](https://github.com/lexi-apps/lexi-renpy-translator)
- **Contact:** `lexiapps@protonmail.com` · Freeware (proprietary source)

---

<div align="center"><sub>© Lexi Apps</sub></div>
