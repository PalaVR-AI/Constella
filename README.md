# Constella

## "The Settled Systems are full of fascinating scenery and interesting people..."

## Preamble

**This Modlist contains mods with sexual content, and you must be of legal age in your country (most Western countries: 18+, some Eastern ones: 21+)**.

_Constella_ is one of _Wabbajack's_ first Starfield modlists, and the long term goal is to use it in conjunction with a Starfield-specific version of [Mantella - Bring NPCs to Life with AI](https://www.nexusmods.com/skyrimspecialedition/mods/98631/?tab=description).

### System Specifications

The recommended setup for an enjoyable experience **at 1080p** is at least

- intel i7 or AMD Ryzen 5 5000 or later
- NVIDIA RTX 2070 SUPER or AMD Radeon 5700 XT or later with **AT LEAST 12GB OF DEDICATED VRAM**
- **40GB PAGEFILE, NO EXCEPTIONS**

**IF YOU DO NOT AT LEAST MEET THESE TARGETS, THE MODLIST WILL PLAY LIKE A HARD FREEZING CRASH-PRONE PIECE OF CRAP.**

Remember that higher resolutions require more powerful Hardware.

### Requirements

- [Nexus Account](https://nexusmods.com/)

This account is mandatory; it must be created before continuing. Nexus Premium is *strongly* recommended or the installation will take many more hours (possibly days).

## Installation

Before you do anything with _Wabbajack,_ ensure that your Steam Library containing _Starfield_ is installed in a non-protected folder (such as the root of your drive, like `C:\Steam\steamapps\common\Starfield`). The Steam Library **cannot** be located in the default Steam install location of `C:\Program Files\Steam\steamapps\common\Starfield` or the list will not function. Relocate the game as necessary.

For _Wabbajack_ to match its files, _Starfield_ needs to be set to the English language. Other languages will not work.

Create a directory on the root of one of your Solid State drives (such as `D:\Constella`) where you wish the modlist to be installed. You need at least **600GB** free for this modlist and a few GBs in the _Wabbajack_ and _OS_ drives for caches. About half of these GBs are mod downloads; the downloads folder can be deleted or relocated after installation.

Ensure you have set antivirus exceptions for this folder, the _Starfield_ vanilla game folder, and the _Wabbajack_ folder, or the installation will fail. Certain antivirus packages do not properly respect exceptions and cannot be fully disabled (_Webroot_ and _Bitdefender_ are examples of these). These tools must be uninstalled from your system.

Ensure that you pause _OneDrive_ syncing while playing. This program can lock some of _Starfield_'s configuration files while in use and can cause the modlist to experience errors.

The _Microsoft Visual C++_ redistributable package is required for _Mod Organizer 2_ and you can download it from _Microsoft._ Download the x64 version of "Visual Studio 2015, 2017, 2019 and 2022" [here](https://aka.ms/vs/17/release/vc_redist.x64.exe).

You must set your Advanced Memory Pagefile to at least 40GB or the modlist will constantly crash. On _Windows 11_ you can find this setting in the About page for your PC. [Here](https://www.windowscentral.com/software-apps/windows-11/how-to-manage-virtual-memory-on-windows-11) is a document to find the specific option; other versions of Windows are similar. Setting the minimum and maximum pagefile size to `40,960` on one Solid State Drive is recommended. 

##  Using Wabbajack

Login to _Nexus_ with the _Wabbajack_ app. This login can be found by clicking the **GEAR** icon in the top right. It will toggle over to "logged in" when successful.

Depending on your system specs and network connection, the download and installation process can take a long time. 

##  Problems with Wabbajack

There are many different scenarios where _Wabbajack_ will produce an error. This is so common that it's expected. Wabbajack has robust error-correction and recovery built in. Just re-run _Wabbajack_ before seeking assistance. _Wabbajack_ will only download and reinstall the minimum necessary to get the modlist working. 

**Wabbajack could not find my game folder:**

_Constella_ will not work with a GOG or pirated game version. If you own the game on _Steam,_ return to the Installation step. If this still doesn't work, ensure you are not running Wabbajack as Administrator. **Asking for help with pirated copies of the game will get you banned from Discord Support.**

## Post-Installation

### Verifying the Modlist

**DO NOT OPEN MOD ORGANIZER 2 AFTER INSTALLATION.** This will cause the Verification to fail.

To verify the modlist, launch the _Wabbajack_ app again after installation is complete.

Ensure that all the same settings are used as during the installation process. You need the **SAME** `.Wabbajack` file and the **SAME** Modlist and Downloads folders.

Click the **VERIFY** button in the Lower Right Corner of _Wabbajack._

Wait for the process to complete. It can take quite some time.

You **MUST** receive a popup webpage that is **BLANK** with **ZERO ERRORS** or you will have horribly weird bugs and crashes that are impossible to troubleshoot.

If you receive **ANY** errors you **MUST** reinstall the list with the "Overwrite" checkbox selected. Do not worry, it will not redo everything. _Wabbajack_ can scan itself to see what's wrong and repair only what needs to be repaired. 

**YOU MUST RECEIVE ZERO ERRORS. THIS IS NOT OPTIONAL.**

This may be much more difficult if your Internet connection is poor, or the _Wabbajack_ app is frequently interrupted.

### Tweaking the Modlist

If you wish to change your game's resolution, select the "INI Editor" from the _Tools_ menu along the icon bar of MO2 and change it via the `SkyrimPrefs.ini` file. Scroll down until you see the `[Display]` header and look for the `iSize` values. Note that the TYPICAL ORDER IS REVERSED, the HEIGHT is listed BEFORE the WIDTH.

### Launching the Modlist

Launch _ModOrganizer.exe_ from the directory in which you installed the list. Launch the game from the **SKSE** entry in the drop-down menu.

### Configuring MCMs for the Modlist

## FINAL NOTES

## TROUBLESHOOTING

Refer to [Troubleshooting](TROUBLESHOOTING.md) for answers to common problems with the modlist.

## Updating the Modlist

Download the modlist's `.wabbajack` file again and specify the same directories. _Wabbajack_ will only update what has changed, it will not repeat the entire installation. It is rarely recommended to continue a save when you update a modlist.

## Removing the Modlist

You can just remove the _Constella_ folder. 
