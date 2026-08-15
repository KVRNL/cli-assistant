<div align="center">

<img src=".github/banner.png" alt="CLI Assistant — Desktop companion for your AI coding CLIs" width="100%">

# CLI Assistant

### Desktop companion for your AI coding CLIs

<a href="https://github.com/KVRNL/cli-assistant/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/KVRNL/cli-assistant?display_name=tag&label=version&color=F5A623&labelColor=0d0d0f&style=for-the-badge"></a>
<a href="https://github.com/KVRNL/cli-assistant/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/KVRNL/cli-assistant/total?label=downloads&color=F5A623&labelColor=0d0d0f&style=for-the-badge"></a>
<img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0d0d0f?style=for-the-badge&labelColor=0d0d0f">
<img alt="Price" src="https://img.shields.io/badge/price-FREE-F5A623?style=for-the-badge&labelColor=0d0d0f">
<a href="./LICENSE"><img alt="License" src="https://img.shields.io/badge/license-Proprietary%20Freeware-0d0d0f?style=for-the-badge&labelColor=0d0d0f"></a>

<br>

Stay connected to your AI coding sessions without being chained to the terminal. Notifications, session management, and an AI chat dock — all in one lightweight desktop app.

### **[⬇&nbsp; Download CLI Assistant — free at kvrnl.io](https://kvrnl.io/products/cli-assistant/)**

</div>

<br>

---

## What it does

CLI Assistant keeps you plugged into your AI coding CLI sessions (Claude Code, Codex, and more) from a clean desktop app, so you can step away from the terminal without losing the thread. Get live session monitoring, desktop notifications you can reply to inline, and an AI chat dock with persistent memory.

It runs quietly in the background, updates itself silently, and stays out of your way until you need it. Free to use — claim your license key and download it straight from this page.

## Features

- **Live session monitoring and autopilot**
- **Desktop notifications with inline responses**
- **Assistant AI chat with persistent memory**
- **Auto-updating with silent installs**

## Download &amp; install

CLI Assistant is **completely free**. Downloads run through a free KVRNL account so every
install gets its own license key.

1. Go to **[kvrnl.io/products/cli-assistant/](https://kvrnl.io/products/cli-assistant/)**
2. Create a free account — email verification, nothing else
3. Claim your license key — instant, no waiting
4. Download and install

> [!NOTE]
> CLI Assistant isn't code-signed yet, so Windows SmartScreen may warn you on first run.
> Click **More info → Run anyway**. Code signing is on the roadmap.

## Your license key

- **Free, one per product**, issued from your KVRNL account.
- **A key activates on one machine.** The first device to activate it claims it.
- **Switching computers?** Hit **Release device** on your
  [account page](https://kvrnl.io/account/) and the key is free to use again.
- Keys are checked over HTTPS at launch. See [Privacy](#privacy).

## Requirements

- **Windows 10 or 11** (64-bit)
- A free [KVRNL account](https://kvrnl.io/signup/) for your license key

## Privacy

CLI Assistant sends KVRNL only what's needed to validate your license: **the key, the
product name, and a hardware ID**. No telemetry, no analytics, no tracking, and
none of your files. Full policy: **[kvrnl.io/privacy](https://kvrnl.io/privacy/)**

## What's new

**v2.5.11** — 2026-08-05
  - Fixed CLI Assistant being flagged by Windows Defender and other antivirus software. Nothing was ever wrong with the app — a few of the ways it did ordinary things just happened to look like the way malware behaves, and this release changes all of them.
  - Voice notifications no longer write a temporary script file to your system and run it through PowerShell — the biggest cause of the false alarms. Speech now runs entirely in memory.
  - The app's own updater and the one-click installers for Git, Obsidian, Claude Desktop and Node.js now download into CLI Assistant's own folder instead of your Windows temp folder, and no longer launch hidden.
  - CLI Assistant.exe now carries proper Windows file details (publisher, product name and version), which it was previously missing.

**v2.5.10** — 2026-07-08
  - New: a per-CLI Desktop Popups picker in Settings — connect Claude Code, Codex, and Copilot individually so the CLIs you use can raise desktop popups through CLI Assistant.
  - Fixed the Settings provider/model dropdowns — scrolling the page no longer accidentally changes the selection.

**v2.5.9** — 2026-07-08
  - Fixed the Assistant becoming slow/unresponsive when set to Codex — it no longer hangs on Codex’s folder-trust prompt (it now runs Codex read-only from a trusted working directory).
  - Renamed the built-in “Neural Link” chat to simply “Assistant.”

**v2.5.8** — 2026-07-08
  - Assistant now works with more than just Claude — in Settings → Assistant you can pick which AI CLI powers it (Claude Code, Codex, or GitHub Copilot) and choose the model.
  - Broadened the app throughout to reflect that CLI Assistant is for your AI coding CLIs, not just one of them.
  - The sidebar now reads “Powered by KVRNL.”

**v2.5.7** — 2026-07-08
  - New name: Claude Assist is now CLI Assistant. Same app, same features — the name just reflects what it really is: a companion for your AI coding CLIs (Claude Code, Codex, Gemini and more), not just one of them.

Full history → **[kvrnl.io/changelog/cli-assistant](https://kvrnl.io/changelog/cli-assistant/)**

## Documentation

Setup guides and how-tos → **[kvrnl.io/docs/cli-assistant](https://kvrnl.io/docs/cli-assistant/)**

## Support

- 🐛 **Found a bug?** [Open an issue](https://github.com/KVRNL/cli-assistant/issues/new/choose)
- 💬 **Question?** [kvrnl.io/contact](https://kvrnl.io/contact/)
- ❓ **FAQ** → [kvrnl.io/faq](https://kvrnl.io/faq/)

## License

**Proprietary freeware — free to use, not open source.**

This repository hosts the installer releases, documentation, and license for
CLI Assistant. **The application source code is not published.** See
**[LICENSE](./LICENSE)** for the full terms.

---

<div align="center">
<br>

**[kvrnl.io](https://kvrnl.io)** &nbsp;·&nbsp; **[All products](https://kvrnl.io/products/)** &nbsp;·&nbsp; **[Changelog](https://kvrnl.io/changelog/)** &nbsp;·&nbsp; **[Contact](https://kvrnl.io/contact/)**

<sub>© 2026 <b>KVRNL</b> — an AI-powered software studio shipping free desktop tools.</sub>

</div>
