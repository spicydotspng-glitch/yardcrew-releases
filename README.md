# YardCrew releases

Official downloads for **YardCrew**, the free desktop app that runs a team of persistent AI workers on your own computer with the ChatGPT plan you already have (through OpenAI's Codex). Each worker gets its own Linux computer on your machine (Docker Desktop, OrbStack or Colima). No API keys, no YardCrew account.

- Website: https://yardcrew.io
- Download page and install steps: https://yardcrew.io/download/
- This repository holds release binaries and release notes only. It does not contain the app's source code.

## Latest: 0.1.0-alpha.1 (alpha)

| Platform | File | Needs |
| --- | --- | --- |
| macOS, Apple Silicon | `YardCrew-0.1.0-alpha.1-arm64.dmg` | M1 or later, macOS 26 or later |
| Windows, 64-bit | `YardCrew-Setup-0.1.0-alpha.1-x64.exe` | Windows 10 (2004+) or Windows 11 |

The Linux worker computer needs a container app: Docker Desktop (free for personal use and small businesses), or OrbStack or Colima on a Mac, and about 3 GB free. Setup is one time, 5 to 25 minutes. Host mode, without a container, is available in Settings → Computer. Older versions: [all releases](../../releases).

Each file has a matching `.sha256`. Check a download before opening it:

- macOS: `shasum -a 256 YardCrew-0.1.0-alpha.1-arm64.dmg`
- Windows (PowerShell): `Get-FileHash .\YardCrew-Setup-0.1.0-alpha.1-x64.exe`

The result must match the `.sha256` file.

## Feedback

Found a bug, or want to tell us the first job you gave your crew? [Open an issue](../../issues/new/choose). Never paste passwords, tokens, or private files into an issue.

## License

YardCrew is © 2026 Niv Asayag. Bundled third-party components (Electron/Chromium, OpenAI Codex, and others) keep their own licenses; their notices ship inside the app.
