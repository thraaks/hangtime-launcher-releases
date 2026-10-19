# HANGTIME Launcher downloads

This public repository hosts HANGTIME Launcher beta binaries and the signed beta update feed. The development source repository remains private.

Download the [latest beta release](https://github.com/thraaks/hangtime-launcher-releases/releases/tag/launcher-v0.1.9). Most Windows x64 users should choose `HANGTIME-Launcher-0.1.9-beta-Setup.exe`; the ZIP is a portable alternative. Compare downloaded files with the attached checksums before installation.

The launcher detects a user-owned ScootX installation, bundles the SXB Menu client, and downloads the pinned official BepInEx build if it is missing. It contains no ScootX game files. The installer does not require administrator rights. It is currently unsigned, so Windows may show an unknown-publisher prompt.

`beta-feed.json` is an RSA-PSS/SHA-256 signed update manifest consumed by the Beta channel in HANGTIME Launcher. The launcher verifies the signature and package hashes before installation. Launcher self-updates are not yet available; run a newer setup package over an existing installation to upgrade.
