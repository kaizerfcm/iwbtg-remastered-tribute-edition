# I Wanna Be The Guy: Remastered Tribute Edition

<img src="sce_sys/icon0.png" width="128" align="right">

Native PS5 homebrew port of *I Wanna Be The Guy: Remastered*, version 1.6.6.6, with Windows and Linux builds.

## Download (v1.6.6.6)
| Platform | File |
| --- | --- |
| PS5 (title ID PPSA99099) | [IWBTGR-TributeEdition-PS5-PPSA99099.zip](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition/releases/download/v1.6.6.6/IWBTGR-TributeEdition-PS5-PPSA99099.zip) |
| Windows x64 | [IWBTGR-TributeEdition-win64.zip](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition/releases/download/v1.6.6.6/IWBTGR-TributeEdition-win64.zip) |
| Linux x64 | [IWBTGR-TributeEdition-linux-x64.tar.gz](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition/releases/download/v1.6.6.6/IWBTGR-TributeEdition-linux-x64.tar.gz) |

Checksums: [SHA256SUMS.txt](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition/releases/download/v1.6.6.6/SHA256SUMS.txt)

## Requirements
- **PS5:** a jailbroken console with a homebrew payload loader (for example etaHEN or elfldr), ShadowMountPlus
  (or another tool that registers apps from `/data/homebrew`), and FTP or a USB drive to copy the files.
- **Windows:** Windows 10/11 x64.
- **Linux:** x64 with glibc 2.38 or newer (Ubuntu 24.04, Fedora 39, Debian 13 or later). SDL2 is included.

## Install
**PS5**
1. Unzip `IWBTGR-TributeEdition-PS5-PPSA99099.zip`.
2. Copy the `PPSA99099` folder to `/data/homebrew/` on the console.
3. Let ShadowMountPlus scan (or reboot). The game appears on the home screen.

To update, copy the new folder over the old one. Saves are kept in `/data/iwbtgr/save`.

**Windows:** unzip and run `IWBTGR.exe`. **Linux:** extract and run `./iwbtgr.sh`.

## Controls
| PS5 | PC (default) | Action |
| --- | --- | --- |
| D-pad / left stick | Arrows | Move |
| Cross | Shift | Jump |
| Square | Z | Shoot |
| Triangle | R | Restart |
| Options | P | Pause |
| R1 | S | Skip |
| Circle | Backspace | Back |

Controls can be remapped in *Options*. On PC, F11 toggles fullscreen. Controllers work on PC too.

## Credits
- Michael "Kayin" O'Reilly: *I Wanna Be The Guy*
- Cherry Treehouse: *I Wanna Be The Guy: Remastered* (Natsu & Renko, Floogle & renex, Midoru, Koala,
  Roaming97 and everyone in the game's credits)
- shaman, back then as Wolfpac Gaming Studio: *I Wanna be the Tribute*
- shaman: the version 1.6.6.6 patch and extras (PS5 and PC editions)
- Emoji graphics: [Twemoji](https://github.com/jdecked/twemoji) by Twitter, Inc and other contributors,
  licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Built with the [PS5 payload SDK](https://github.com/ps5-payload-dev/sdk) and SDL2.

## Source
This repository only hosts the releases. The source code is kept in a private repository.
The runtime is GPL-3.0-or-later (`LICENSE`); the games' own content belongs to their authors.
