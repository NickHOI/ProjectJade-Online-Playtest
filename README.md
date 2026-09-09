# Project Jade Online Playtest

## Download

**[Download ProjectJadeOnlineSetup-Phase35.exe](https://github.com/NickHOI/ProjectJade-Online-Playtest/releases/download/phase3.5-online-playtest/ProjectJadeOnlineSetup-Phase35.exe)**

This single Windows installer is the only file either player needs. No manual ZIP extraction is required.

> Updated after the 2026-09-09 two-human test: this build fixes a lost Session-admission completion that could leave both players waiting. It also shows staged connection progress and automatically recovers the waiting lease.

## Host

1. Run the installer once.
2. Double-click **Project Jade Host** on the desktop.
3. Create a private Workshop and send the displayed room code to the other permanent partner.

## Friend

1. Run the same installer once.
2. Double-click **Project Jade Join** on the desktop.
3. Enter the room code and join the Workshop.

The connection uses Unity Lobby/Relay. Players do not enter an IP address, use a VPN, or configure port forwarding. A Workshop has exactly two permanent equal human partners. Physical play pauses when either partner disconnects, while durable Workshop state remains on the host machine.

This is a development playtest. The installer is not code-signed, so Windows may display a SmartScreen warning.

- Unity: `6000.5.10f1`
- Source checkpoint: `2a0e1cab0ac8963ca4ad38e29ce5d27135998e94`
- Installer bytes: `118403072`
- Installer SHA-256: `04217B0AE846C34D2F9ACFDAB0113F45047BA361F245969993617D810410E150`

This repository is a public download page only. Project Jade source code is not published here.