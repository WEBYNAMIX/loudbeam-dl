# Loudbeam — downloads

Official release downloads for **[Loudbeam](https://loudbeam.app)** — the driverless Windows
volume booster.

### [⬇ Download the latest version](https://github.com/WEBYNAMIX/loudbeam-dl/releases/latest)

A single portable `.exe`. No installer, no drivers, no account. To uninstall, delete the file.

## Verifying your download

Every release ships a `Loudbeam.exe.sha256` file. Builds are **not code-signed** yet, so Windows
SmartScreen may warn on first run — checking the hash is how you confirm the file is the one we
published:

```powershell
Get-FileHash Loudbeam.exe -Algorithm SHA256
```

Compare the result with the SHA-256 printed in the release notes. If they differ, do not run it.

## About this repository

This repo holds **only the released binaries**. Loudbeam's source code is kept in a separate
private repository — this one exists so the download link on loudbeam.app is public and
permanent without publishing the source.

Issues and support: **support@loudbeam.app**

---

© 2026 Loudbeam. Licensed under the EULA published at
[loudbeam.app/legal/eula.html](https://loudbeam.app/legal/eula.html).
