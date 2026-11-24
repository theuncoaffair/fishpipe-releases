# FishPipe releases

This repository intentionally contains no application source code.
It contains only the signed release APK and release notes used by the
FishPipe updater and the Obsidian Git release vault.

- `releases/latest.json`
- `releases/fishpipe-release.apk`
- `releases/release-notes.md`

## Updating FishPipe

Sync this private repository with Obsidian Git into the vault folder selected in
FishPipe under **Check updates**. The updater reads `releases/latest.json` and
`releases/fishpipe-release.apk` from that folder. No GitHub token is embedded in
the app.
