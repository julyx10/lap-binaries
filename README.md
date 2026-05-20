# lap-binaries

Prebuilt sidecar binaries for Lap (ffmpeg, ffprobe, etc.).

This repository hosts versioned, cross-platform binaries used during CI and release packaging.
It ensures reproducible builds without requiring users to install external dependencies.

<p>
  <img src="https://img.shields.io/github/downloads/julyx10/lap-binaries/total" alt="GitHub all releases"></a>
</p>

## Purpose

This repository exists to:

- Keep the main Lap repository clean (no large binaries in git history)
- Provide versioned and reproducible builds
- Simplify CI and cross-platform packaging
- Avoid requiring users to manually install dependencies like ffmpeg

## Contents

Each release contains prebuilt binaries for multiple platforms:

### macOS
- `ffmpeg-aarch64-apple-darwin`
- `ffprobe-aarch64-apple-darwin`
- `ffmpeg-x86_64-apple-darwin`
- `ffprobe-x86_64-apple-darwin`

### Windows
- `ffmpeg-x86_64-pc-windows-msvc.exe`
- `ffprobe-x86_64-pc-windows-msvc.exe`
- `ffmpeg-aarch64-pc-windows-msvc.exe`
- `ffprobe-aarch64-pc-windows-msvc.exe`

### Linux
- `ffmpeg-x86_64-unknown-linux-gnu`
- `ffprobe-x86_64-unknown-linux-gnu`
- `ffmpeg-aarch64-unknown-linux-gnu`
- `ffprobe-aarch64-unknown-linux-gnu`

