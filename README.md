# Sequence Cleaner (CEP) Releases

This repository contains installable releases of the **Sequence Cleaner** CEP extension for **Adobe Premiere Pro**.

- Source code and development repo: `ittakesii/sequencecleaner`
- Downloads: see the **Releases** page for the latest `.zxp`

## Install (macOS / Windows)

1. Download the latest `.zxp` from **Releases**.
2. Install it using a ZXP installer/extension manager (for example, an extension manager that supports self-signed ZXP packages).
3. Restart Premiere Pro.
4. Open the panel in Premiere:
   - `Window > Extensions (Legacy) > Sequence Cleaner`

## Verify Download (optional)

Each release includes a `.sha256` file.

- macOS:
  - `shasum -a 256 PremiereSequenceCleanerPlugin-vX.Y.Z.zxp`
- Windows (PowerShell):
  - `Get-FileHash .\\PremiereSequenceCleanerPlugin-vX.Y.Z.zxp -Algorithm SHA256`

Compare the output to the contents of the `.sha256` file.

## Notes

- CEP panels are considered “Legacy” in Premiere Pro. You may need to enable CEP extensions depending on your Premiere/OS configuration.
- This repo intentionally contains only install artifacts and minimal documentation (no UXP/dev sources).

