# Dolphin V.V.mImo H700

Community packages for the Anbernic RG H700 (ARM64, 1 GiB RAM). The project provides:

- a **V.V.mImo Standalone** edition for KNULLI;
- a **Dolphin libretro** edition for muOS.

It is intended for GameCube and, where supported by the device, Wii. No games, keys, game BIOS files, or user save data are included.

> Unofficial project. It is not affiliated with Dolphin Emulator, RetroArch, KNULLI, muOS, or Anbernic.

> **Beta warning:** compatibility and performance vary between games. Install and test carefully.

## User-facing features

| Area | Functionality |
| --- | --- |
| Scene profiles | Recognises light, normal 3D, and heavy 3D scenes to allow more suitable performance behaviour. |
| Presentation control | Manual and automatic FPS-limit modes. They can be disabled when a game is incompatible. |
| CPU Culling | Adjustable culling levels, including aggressive test profiles. |
| Texture management | Texture cache and cleanup controls designed for H700 memory limits. |
| Audio | DSP, backend, callback, latency, buffer, Audio Fill Gaps, Preserve Pitch, and stretching controls. |
| Video | Internal resolution, shader compilation, EFB/XFB, mipmapping, fog, VSync, VI Skip, and related graphics settings. |
| KNULLI standalone | Dedicated GameCube menu integration, V.V.mImo splash screen, save-state hotkeys, and exit hotkey. |

## KNULLI standalone installation

1. Copy `dolphin-vvmimo-standalone-knulli` and `Instalar Dolphin V.V.mImo Standalone.sh` to `roms/ports/`.
2. In KNULLI, open **Ports** and run **Instalar Dolphin V.V.mImo Standalone**.
3. A black screen can appear briefly while KNULLI saves its overlay. Do not turn off the device.
4. Wait for the completion message, then restart KNULLI.
5. Open a GameCube game. The entry launches the V.V.mImo standalone build, not the libretro core.

## muOS installation

1. Copy the matching `.muxzip` package to the root of the SD1/`ARCHIVE` partition.
2. Open **Apps → Archive Manager** on muOS.
3. Select and install the package.
4. Restart muOS before the first test.

## Notes

- There is no universal configuration for every game.
- Start with default settings and change one option at a time.
- Restart the emulator after changing an option marked as requiring a restart.
- The project documents visible functionality, but does not disclose internal controller logic or formulas.

## Licensing

Dolphin is free software under GPLv2+. Any released binary must be accompanied by the corresponding modified source code and applicable licence notices.
