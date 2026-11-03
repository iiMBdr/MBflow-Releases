<p align="center"><img src="assets/MBflow.png" width="128" alt="MBflow video enhancement logo"></p>

# MBflow

Make every frame flow. A simple Windows video finishing studio with DLSS Neural Rendering and Super Resolution, smooth motion blur, vibrance and sharpness.

## Download

- [Offline installer](https://github.com/iiMBdr/MBflow-Releases/releases/latest/download/MBflow-Setup-Offline.exe): complete application and redistributable dependencies.
- [Online installer](https://github.com/iiMBdr/MBflow-Releases/releases/latest/download/MBflow-Setup-Online.exe): small downloader; verifies the downloaded installer with SHA256.
- [Release notes and checksums](https://github.com/iiMBdr/MBflow-Releases/releases/latest).

Windows x64 with a supported NVIDIA RTX GPU and driver is required for enhancement. Proprietary NR/SR model runtimes are not bundled. Existing Gameplay Finish runtime and settings are imported automatically; a new machine selects its runtime folder once.

## Use

Upload a video, choose the output name and optional resolution/vibrance, then **Enhance & Export**. Compare the original with an automatically prepared enhanced preview before exporting.

- Natural detail-preserving NR with highlight protection.
- Real SR evaluation when upscaling, with explicit engine failure reporting.
- 16-bit processing, HEVC Main10 SDR Rec.709 output.
- Output bitrate budget scales with resolution: 1080p → 4K targets four times the source budget.
- Frame rate, timestamps and audio are preserved.
- Dark interface follows Windows Accent.

**Check for updates** inside the installed app downloads a delta when available, falls back to the full package and waits for export completion before restarting. User data remains outside the installation folder.

This repository contains public downloads and artwork. Application source and build automation are maintained privately. NVIDIA trademarks belong to their owners; MBflow is not affiliated with NVIDIA. Reprocessing a recording cannot guarantee the same result as integration inside a game. Already clipped source detail cannot be reliably restored.
