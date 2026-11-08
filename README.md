<img src="https://www.hackangel.xyz/dynamic-island/img/icon-256.png" width="88" alt="Dynamic Island icon" />

# Dynamic Island for Windows: downloads

Official installers for **Dynamic Island**, a smooth, animated island at the top of your Windows screen for music, notifications and charging. Built by [Hack Angel](https://www.hackangel.xyz/).

**➜ [Download page and features](https://www.hackangel.xyz/dynamic-island/)**

**➜ [Download the latest installer](https://github.com/HackAngeldon/DynamicIsland-Releases/releases/latest/download/DynamicIsland-Setup.exe)** (Windows 10 2004+ / Windows 11, x64)

This repository contains release files only; the source code is private.

## Verify your download

Each release lists the installer's SHA-256 checksum, and `SHA256SUMS.txt` is attached. Check it in PowerShell:

```powershell
(Get-FileHash .\DynamicIsland-Setup.exe -Algorithm SHA256).Hash
```

Releases are currently **not code-signed**, so Windows SmartScreen may say "Windows protected your PC". If the checksum matches, choose *More info* → *Run anyway*.

## Privacy and security

- Never connects to the internet: no telemetry, no update checks.
- Runs with your normal user rights and never asks for admin while running.
- Reads what's playing and your notifications read-only, and keeps everything on your PC.
- Hardened against DLL hijacking, malicious notification images, crafted notification content and unsafe launch commands.

Only download installers from this repository's [Releases](https://github.com/HackAngeldon/DynamicIsland-Releases/releases) page or from [hackangel.xyz/dynamic-island](https://www.hackangel.xyz/dynamic-island/).
