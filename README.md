# RTX Guide
NOTE: RTX Remix requires an RTX enabled graphics card. I think you can run it on certain AMD cards, but im not fully knowledged in that area. If you have any questions, I urge you to join the [RTX-Remix Discord server](https://discord.gg/c7J6gUhXMk) and ask there. There is also a forum post there in the `remix-projects` channel for SCP Containment Breach in general.

1. Build the game from this repo (You can also use the original repo, as this one currently doesn't do much except disable monitors)
2. Go to the latest release of [DxWrapper](https://github.com/elishacloud/dxwrapper/releases) and download `dx7.games.zip`
3. Download the latest GitHub Actions bulds of NVIDIAGameWorks/bridge-remix and NVIDIAGameWorks/dxvk-remix (currently [this](https://github.com/NVIDIAGameWorks/bridge-remix/actions/runs/13532512152) and [this](https://github.com/NVIDIAGameWorks/dxvk-remix/actions/runs/13735050636) as of writing. The `release` version is fine.)
4. Drag DxWrapper into the game folder
5. Open the `bridge-remix` archive and extract the contents into the game folder (next to where the .exe is)
6. Open the `dxvk-remix` archive and extract the contents into the newly created `.trex` folder.
7. Change your Options.ini for SCB-UE Reborn to [this one](https://pastebin.com/raw/XphEjweV), open the Options.ini and replace the contents or replace the file itself. This is in `AppData\Roaming\scpcb-ue\Data`
8. All set. RTX Remix should be rendering now. If you want a starting place, then edit the file named `rtx.conf` and replace the contents with [this one](https://pastebin.com/raw/nr50q9tS)

---

# RTX Mods
Currently, I am working on getting lighting to look nicer and more stable. This involves using emissive materials and manually placing lights in each room if needed.

---
# SCP - Containment Breach Ultimate Edition Reborn

The game is based on the works of the SCP Foundation community (http://www.scp-wiki.net/).

This game and the source code are licensed under Creative Commons Attribution-ShareAlike 3.0 License.

http://creativecommons.org/licenses/by-sa/3.0/

Requirements:

-	[Blitz3D TSS (ZiYueCommentary)](https://github.com/ZiYueCommentary/Blitz3D/releases) v1.134

-	[IDEal for Blitz3D](https://web.archive.org/web/20130827150202/http://fungamesfactory.com/download.php?get=IDEalSetup_0.8.94.exe) v0.8.94

-	[BlitzPlus](https://www.blitzcoder.org/forum/downloads.php) v1.47 for Map Creator

Beware - the source code is perhaps more horrifying than the game itself!

Our Discord server: https://discord.gg/n7KdW4u
