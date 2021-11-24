# A7-TextureConvert
*A mod that automates PVRZ texture conversion to various compression types used by the mobile game variants.*

## Overview

A helper mod that allows you to automate PVRZ texture conversion to various compression types used by the mobile variants of the Enhanced Edition games.

## Components

### Convert PVRZ files

This component consists of multiple subcomponents:
- PVRTC 2bpp: All game files
- PVRTC 2bpp: All game files, alpha-blended files only
- PVRTC 2bpp: Override files only
- PVRTC 2bpp: Override files only, alpha-blended files only
- PVRTC 4bpp: All game files (iOS recommended)
- PVRTC 4bpp: All game files, alpha-blended files only (iOS recommended)
- PVRTC 4bpp: Override files only (iOS recommended)
- PVRTC 4bpp: Override files only, alpha-blended files only (iOS recommended)
- ETC1: All game files
- ETC1: All game files, alpha-blended files only
- ETC1: Override files only
- ETC1: Override files only, alpha-blended files only
- ETC2: All game files
- ETC2: All game files, alpha-blended files only
- ETC2: Override files only
- ETC2: Override files only, alpha-blended files only

PVRTC and ETC1/ETC2 are texture compression formats used by iOS and/or Android devices.

For each compression type you can choose to convert:
- all available PVRZ files (biffed and in override folder)
- only files present in the override folder

And optionally further restrict conversion only to files with advanced alpha-blending.
