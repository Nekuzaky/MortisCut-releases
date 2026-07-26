# Mortis Cut — Releases

Public release channel for **Mortis Cut** — multitrack video editing.

Auto-updating Windows installers, published with [electron-updater](https://www.electron.build/auto-update). **Source code is private.**

## Download

Grab the latest build from the [Releases page](../../releases).

| File | |
|---|---|
| `mortis-cut-Setup-<version>.exe` | Installer. Updates itself automatically. **Use this one.** |
| `mortis-cut-Portable-<version>.exe` | Portable. For machines where you cannot install anything — does not self-update. |

`latest.yml` and the `.blockmap` are consumed by the updater. You do not need to download them.

## Updates

The installed build checks shortly after launch and every six hours after that. Downloads
happen in the background; installing always asks first, so nothing replaces the app while you
have unsaved work open.

## Security

These builds are **not code-signed**. Windows SmartScreen will warn about an unknown publisher
on first run.

Update integrity relies on HTTPS and the SHA-512 recorded in `latest.yml`. Only download from
this repository.

## The Mortis suite

| App | Releases |
|---|---|
| Mortis 3D Edit | [Mortis3DEdit-releases](https://github.com/Nekuzaky/Mortis3DEdit-releases) |
| Mortis Ink | [MortisInk-releases](https://github.com/Nekuzaky/MortisInk-releases) |
| Mortis Écho | [MortisEcho-releases](https://github.com/Nekuzaky/MortisEcho-releases) |
| Mortis Cut | [MortisCut-releases](https://github.com/Nekuzaky/MortisCut-releases) |

## Contact

Bug reports and enquiries: contact@nekuzaky.com — https://nekuzaky.com/contact

## License

Copyright (c) 2026 Nekuzaky. All rights reserved. Builds are provided for use as-is and may
not be redistributed, repackaged or resold.
