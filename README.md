# Bully PSP Port — Source and Patch Project

This repository contains source code, patch utilities, tests, configuration files, and third-party notices for the R2 packet-decoder update and R4 radar/map fix.

## Package layout

- `r2-packet-decoder/` — R2 source, build scripts, tests, PPSSPP profile, and engine notices.
- `radar-fix/` — R4 map patcher, native source and payloads, tests, and PS2RC notices.

## Important: game files are not included

The copyrighted game executable (`EBOOT.PBP`) and game data image (`disc/SCRIPTS/SCRIPTS.IMG`) are intentionally excluded. Supply your own legally obtained game files. The R2 checksum manifest covers only files included in this repository.

Read each package's `INSTALL.md` or `README.md` before applying a patch. Back up your game folder and saves first. The included validation notes describe tested environments and known limitations; they do not imply full compatibility across all devices or game locations.

## Third-party notices

Retain the license and notice files included in each package. The work is based in part on PS2RC by SandstoneDev; see the bundled notices for details.
