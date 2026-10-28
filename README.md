# Unlock with Bio — Releases

This public repo holds nothing but GitHub Releases for Unlock with Bio:
the Windows NSIS `.exe` installer, `latest.yml`, and the `.blockmap` file.

Installed PCs self-update with electron-updater, which reads `latest.yml`
from these releases. There is no other update channel.

- Code (private): https://github.com/codingoclockgit/Unlock-with-Bio
- First Electron release: v0.2.0 (the Python v0.1.0 `latest.json` channel
  is retired — electron-updater does not read it).
