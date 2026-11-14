<img src="https://www.hackangel.xyz/windsland/img/icon-256.png" width="88" alt="Windsland icon" />

# Windsland for Windows: downloads

Official installers for **Windsland** (formerly *Dynamic Island*), a smooth, animated island at the top of your Windows screen for music, notifications, charging and live activities, plus an optional dock. Built by [Hack Angel](https://www.hackangel.xyz/).

**➜ [Download page and features](https://www.hackangel.xyz/windsland/)**

**➜ [Latest release](https://github.com/HackAngeldon/Windsland-Releases/releases/latest)** (Windows 10 2004+ / Windows 11, x64)

This repository contains release files only. **The source code is open** (MIT): **[HackAngeldon/Windsland](https://github.com/HackAngeldon/Windsland)**.

## The new name

Windsland was called Dynamic Island until November 2026. "Dynamic Island" is Apple's name for an iPhone feature and a trademark of Apple Inc., so the app now has a name of its own. Windsland is an independent app and isn't affiliated with or endorsed by Apple. Old links to this repository and to `hackangel.xyz/dynamic-island` redirect here. Releases up to 0.3.x ship as `DynamicIsland-Setup.exe`; newer ones ship as `Windsland-Setup.exe` (with a copy under the old name, so old download links keep working).

## Verify your download

Each release lists the installer's SHA-256 checksum, and `SHA256SUMS.txt` is attached. Check it in PowerShell (use the file name you downloaded):

```powershell
(Get-FileHash .\Windsland-Setup.exe -Algorithm SHA256).Hash
```

Releases are currently **not code-signed**, so Windows SmartScreen may say "Windows protected your PC". If the checksum matches, choose *More info* → *Run anyway*.

## Privacy and security

- Never connects to the internet: no telemetry, no update checks.
- Runs with your normal user rights and never asks for admin while running.
- Reads what's playing and your notifications read-only, and keeps everything on your PC.
- Hardened against DLL hijacking, malicious notification images, crafted notification content and unsafe launch commands.

Only download installers from this repository's [Releases](https://github.com/HackAngeldon/Windsland-Releases/releases) page or from [hackangel.xyz/windsland](https://www.hackangel.xyz/windsland/).