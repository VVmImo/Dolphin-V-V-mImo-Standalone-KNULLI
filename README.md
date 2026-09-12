# Dolphin V.V.mImo Standalone for KNULLI

An unofficial standalone Dolphin package for ARM64 H700 devices running KNULLI. It provides a dedicated **Nintendo GameCube** menu entry and launches Dolphin directly, without RetroArch.

> Beta software. Compatibility and performance vary by game. This project is not affiliated with Dolphin Emulator, KNULLI, Anbernic, or RetroArch.

## Included

- Standalone Dolphin executable, `Sys` files, and Dolphin-specific configuration.
- Dedicated GameCube integration using `/userdata/roms/gc`.
- V.V.mImo startup splash screen.
- Save state: **M + R2**; save state: **M + L2**; exit: **M + B**.
- Configurable video, audio, CPU/JIT, shader, EFB/XFB, cache, and scene-profile options.

## Install

1. Copy `dolphin-vvmimo-standalone-knulli` and `Instalar Dolphin V.V.mImo Standalone.sh` to `roms/ports/`.
2. Run the installer from **Ports**.
3. Wait for its completion message and restart KNULLI.
4. Put GameCube games in `/userdata/roms/gc`.

KNULLI can hide an empty GameCube system. A short black screen during installation is normal while its persistent overlay is saved.

## Licence

Dolphin is GPLv2+. Publish matching modified source code and required licence notices with any distributed binary.
