# AR

AR is a screenshare tool for Minecraft on Windows. SSer ask a player to run it, and it scans the PC for cheat clients, injected code, macros, alt accounts and signs that evidence was cleaned up. Everything it finds is shown in one window, with an explanation and the evidence behind each finding.

## How it works

1. The player downloads `ar.exe` from [Releases](../../releases/latest) and runs it.
2. AR sends a one-time 6-digit code to the booster Discord channel. SSer give the code to the player.
3. Once the code is entered, AR scans the PC. This usually takes a minute or two.
4. The results open, grouped by check and sorted by severity. SSer can save them as an HTML or JSON report.

## What it checks

- **Game process:** injected DLLs, hidden code, hooked functions, Java agents and classes that did not come from Minecraft or a mod loader
- **Mods:** identifies every mod and flags known cheats or disguised files
- **Jars:** which jar files were launched, and jars that were renamed, overwritten or deleted
- **Macros:** mouse and keyboard macro software, auto-clickers and their config files
- **Alt accounts:** Discord and Minecraft accounts used on the PC
- **System history:** Windows logs and records of what ran, was downloaded or was plugged in
- **Cleanup:** hidden data in game files, and file timestamps or links that were tampered with

Each finding is marked **Detected**, **Warning** or **Info**. A finding is evidence for the SSer to review, not an automatic verdict.

## Requirements

- Windows 10 or 11 (64-bit)
- Administrator rights (AR asks when it starts)
- An internet connection

## Privacy

Scan results stay on the PC unless staff save a report. AR only sends two things over the internet: the access code and PC name to the booster Discord channel, and mod file hashes to Modrinth so it can identify mods.

---

Made by p1ae · [GitHub](https://github.com/p1aegg) · [Discord](https://discord.gg/GwNVZtt9WJ)
