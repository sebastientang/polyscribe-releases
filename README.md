# Polyscribe for Windows: releases

Each release holds `Polyscribe.exe` and `latest.json`.

Installed copies of Polyscribe look here once a day. They install a newer version only when
`latest.json` carries a valid signature from the release key built into the app, and the
downloaded exe matches the signed SHA-256 and size.

To install: download `Polyscribe.exe` from the latest release into
`%LOCALAPPDATA%\Programs\Polyscribe`, then run it. No administrator rights are needed.
