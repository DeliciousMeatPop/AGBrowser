<div align="center">

# ARMGDDN Browser

<img width="1254" height="1254" alt="image" src="https://github.com/user-attachments/assets/8583fc67-02b5-49b1-b6cf-463bc13c5047" />

---

**The official file browser for ARMGDDN Games — a customized [Rclone Browser](https://github.com/Alkl58/RcloneBrowser) built to make browsing and downloading from our remotes simple.**

[![Website](https://img.shields.io/badge/Website-ARMGDDNBrowser.com-2ea44f?style=for-the-badge)](https://armgddnbrowser.com)<br>
[![Telegram](https://img.shields.io/badge/Telegram-@ARMGDDNGames-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ARMGDDNGames)<br>
[![Is It Safe?](https://img.shields.io/badge/Is%20ARMGDDN%20Safe%3F-Read%20This-blue?style=for-the-badge)](https://rentry.co/IsARMGDDNSafe)

</div>

---

## What is ARMGDDN Browser?

ARMGDDN Browser is a portable, pre-configured front end for [Rclone](https://rclone.org/) — the swiss-army knife of cloud storage. Instead of wrestling with config files and command-line flags, you get a clean graphical interface that connects straight to the ARMGDDN Games remotes so you can browse, search, and download.

It's built on a feature-rich fork of the open-source **Rclone Browser**, bundled with a customized copy of Rclone and encrypted remote configs so everything works out of the box — no setup, no accounts, no fiddling.

## Features

- **Zero configuration** — remotes come pre-loaded and ready to browse.
- **Portable** — runs from its own folder; nothing is scattered across your system.
- **Self-updating** — pulls the latest remote config automatically each time you launch.
- **Fast transfers** — full multi-threaded Rclone download performance under the hood.
- **Familiar GUI** — browse remotes like folders, queue transfers, and watch progress.
- **Lightweight** — a small download that unpacks to a single portable directory.

## Installation

1. Download **`SETUP.7z`** from the [releases page](../../releases) or our [Telegram channel](https://t.me/ARMGDDNGames) (type /download).
2. Extract it and run **`INSTALL.bat`** — it unpacks the browser and drops a shortcut on your Desktop.
3. Launch from the Desktop shortcut (or run **`ARMGDDNBrowser.cmd`** directly).

On first launch the browser fetches the newest config and opens straight to the remotes.

> **Tip:** Install to a normal folder you control (Best use case is your drive root), not a protected system directory(e.g. **NOT** your Desktop or Documents or ANYWHERE in your user directory.).

## What's in the download

| File | What it does |
| --- | --- |
| `ARMGDDNBrowser.exe` | The Rclone Browser GUI. |
| `AG.exe` | Customized Rclone engine that powers browsing and transfers. |
| `ARMGDDNBrowser.cmd` | Launcher — runs the updater, then opens the browser. |
| `Update.bat` | Fetches the latest remote configuration on launch. |
| `AG.conf` / `update.conf` | Encrypted Rclone configs for the remotes. |
| `ARMGDDNBrowser.ini` | Portable settings for the browser. |
| `setup.ico` | ARMGDDN branding icon. |

## Is ARMGDDN Browser safe?

**Yes** — and we're transparent about how it works. The browser is a repackaged build of the open-source Rclone Browser plus a customized Rclone. Because we rebrand the executables and swap in a custom icon (via resource editing), Microsoft's SmartScreen may show a single false-positive flag. That's a common consequence of modifying an executable's resources — not malware.... And in fact, the normal rclone.exe is even flagged sometimes.

We've gone from dozens of antivirus flags in the past down to essentially one, and we're upfront about every file and what it does (see the table above). Don't want to trust the installer? You're welcome to inspect the batch scripts yourself — they're plain text.

📄 **Full write-up:** [rentry.co/IsARMGDDNSafe](https://rentry.co/IsARMGDDNSafe)

## Links & Community

- 🌐 **Beta Website:** [ARMGDDNBrowser.com](https://armgddnbrowser.com)
- 💬 **Telegram (channel & support):** [@ARMGDDNGames](https://t.me/ARMGDDNGames)
- 🛡️ **Safety FAQ:** [rentry.co/IsARMGDDNSafe](https://rentry.co/IsARMGDDNSafe)

## Credits

Built and maintained by **DeliciousMeatPop, George Jefferson, Miss Tulip, and the rest of the AG Staff.**

Standing on the shoulders of the [Rclone](https://rclone.org/) and [Rclone Browser](https://github.com/Alkl58/RcloneBrowser) open-source projects. ❤️


---

![Visitors](https://api.visitorbadge.io/api/visitors?path=DeliciousMeatPop%2FAGBrowser&label=People%20Who%20Forgot%20To%20Star%20This%20Repo&countColor=%23ba68c8&style=plastic)<br>
![Last Commit](https://img.shields.io/github/last-commit/DeliciousMeatPop/AGBrowser?label=Last%20Updated)<br>
![Created](https://img.shields.io/github/created-at/DeliciousMeatPop/AGBrowser?label=Created)<br>
![Monthly Commits](https://img.shields.io/github/commit-activity/m/DeliciousMeatPop/AGBrowser?label=Monthly%20Commits)

## ⭐ Do the thing

You’re already here. You’ve already scrolled.

Just hit the ⭐ and we both win.

⭐ Star this repo please

---

[![GitHub stars for this repo](https://img.shields.io/github/stars/DeliciousMeatPop/AGBrowser?style=social)](https://github.com/DeliciousMeatPop/AGBrowser) = **GitHub stars for this repo**

[![GitHub stars in total (all repos)](https://img.shields.io/github/stars/DeliciousMeatPop?style=social)](https://github.com/DeliciousMeatPop) = **GitHub stars in total (all repos)**
