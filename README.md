# Magnum Opus Readme

---

## Table of Contents

- [Magnum Opus Readme](#magnum-opus-readme)
  - [Table of Contents](#table-of-contents)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Packages](#installing-microsoft-visual-c-redistributable-packages)
        - [Visual Studio 2015, 2017, 2019, and 2022](#visual-studio-2015-2017-2019-and-2022)
        - [Visual Studio 2012 (VC++ 11.0) Update 4](#visual-studio-2012-vc-110-update-4)
      - [Steam Config](#steam-config)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Fallout 4](#clean-fallout-4)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
    - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Updating](#updating)
  - [Post Installation](#post-installation)
  - [FAQ](#faq)
  - [Widescreen Support](#widescreen-support)
  - [Contact](#contact)
  - [Donate](#donate)

---

## Preamble

Magnum Opus is one of the oldest premade modlists available for any game, which means there have been thousands of hours of work put into this. It is extremely stable, extremely fun, and packed with loads of new content for you to enjoy.

Magnum Opus runs on a downgraded version of Fallout 4. The downgrade is handled for you by Wabbajack; you do not have to do anything. This also means Magnum Opus does **not** use the Next-Gen update, and will not contain any Creation Club mods whatsoever. This includes the Anniversary Edition content and the Creation Content bundle - they won't be included any time soon, if ever.

This list is NOT built with Survival Mode in mind. I don't play it. I don't like it. If you choose to play Magnum Opus in Survival difficulty, I don't know if any issues may arise from that, and it is unlikely I can help with such issues.

Is Magnum Opus for you? I don't know, but [this video might help you decide](https://youtu.be/zpoeRvuHNpw).

**Please read this readme in its entirety.**

**Please [read the FAQ](https://github.com/LivelyDismay/magnum-opus/blob/main/faq.md) again before reporting an issue or asking me a question.**

**Please consult the in-game Magnum Opus Beginner's Guide terminal (which also has a holotape for a portable version of the terminal!) outside Vault 111 before alt-tabbing out to Discord to ask for my help.**

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

## Installation

---

### Pre-Installation

You need a legal copy of the latest version of Fallout 4 through **Steam** (not GOG, not Epic), with all DLCs as listed in Steam **EXCEPT** the High Definition DLC. The High Definition DLC is garbage and should not be used in any case ever. **You also do NOT need to own the Creation bundle that was released alongside Anniversary Edition.**

Here's how that works:
<details>
You update Fallout 4 in Steam to the latest version.
Wabbajack looks for Fallout 4 and finds it based on your registry (which is why you launch the game once prior to installing) and the file hashes (unique identifiers that tell Wabbajack which versions of the files you have).

Since Wabbajack is looking for one specific version, it will only work with the latest update.
Wabbajack then reads the files in my Stock Game folder (which are the previous Fallout 4 version), identifies those hashes, compares them to the hashes of the files it found in Steam, and "patches" the Steam files into the Stock Game files.

So what does this mean, in a nutshell? It means you need the latest version of Fallout 4 to install Magnum Opus. It also means Magnum Opus does not yet use the content from the update. This likely will not happen for several months (if ever), due to the nature of how these updates work.
</details>

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#updating).

#### Installing Microsoft Visual C++ Redistributable Packages

These packages are required for MO2 and for the BiRaitBec Texture Optimization step respectively, and you can download them from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads).

##### Visual Studio 2015, 2017, 2019, and 2022

Download the x64 version under [Visual Studio 2015, 2017, 2019, and 2022](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022).

[Direct Link](https://aka.ms/vs/17/release/vc_redist.x64.exe) if you can't find it.

##### Visual Studio 2012 (VC++ 11.0) Update 4

Download the x64 version under [Visual Studio 2012 (VC++ 11.0) Update 4](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2012-vc-110-update-4).

[Direct Link](https://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU_4/vcredist_x64.exe) if you can't find it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**. I really wish I could, but at this time, it simply isn't feasible.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Fallout 4

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Fallout 4` folder in `Documents/My Games/`. **Make sure you run the game once** to establish your registry path - otherwise, Wabbajack will be unable to locate the game directory, and thus cannot install the modlist.

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

### Using Wabbajack

---

#### Preparations

Let's get to the actual installation..

Grab the latest release of Wabbajack from [here](https://www.wabbajack.org/) (just click the big blue Download button) Place the `Wabbajack.exe` file in a blank folder at the root of a drive, such as `C:/Wabbajack/wabbajack.exe`. Please do not put it in a Windows Protected Directory, such as Program Files or your Desktop..  

---

Launch Wabbajack. The exe will download the rest of the program from Github and extract itself wherever you placed the exe. When it is finished extracting and installing itself, select the `Browse Modlists` option. Click the Download arrow for Magnum Opus, and you will be forwarded to the next screen when it is finished.
 - This exe will auto update itself as needed. This functionality may break if you try launching it from a shortcut. Please just use this one exe all the time, and you'll never have to worry about updating the program.

Set the `Installation Location` to a blank folder at the root of a drive, such as `D:\Magnum Opus`. The `Download Location` will update automatically. Again, please avoid using Windows Protected Directories. **You may have the Installation and Download locations on separate drives if you prefer, but your Installation folder should be on an SSD or NVME.** If you have the Installation on an HDD, you will experience stuttering and poor performance.

You may delete the Downloads folder after the installation is completed successfully, if you want to save space.

Click the `Play` arrow. If you have a Nexus Premium account, all of your downloads will be automated. Without Premium, you will need to manually click the Download button for each mod. Installation will be automated regardless of your account status.

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

- **I'm having problems downloading a few files**

The most common files that fail to download through Wabbajack are as follows:
- [More Hairstyles - Beards](http://www.mediafire.com/file/iztz7iidy6djz1e/MoreHairstyles-Beards.rar/file)
- [Misc Hairstyles 1.6](http://www.mediafire.com/file/kfac38dni6d53rp/MiscHairstyle1.6_by_Atherisz.7z/file)

Download these files manually, paste them into your `downloads` folder that you specified for Wabbajack, then rerun the installation.

Need help with something else? [Join my Discord server for live support.](https://discord.gg/livelymods)

- **I'm having problems downloading more than a few files**

If you have Nexus Premium but are getting a lot of "unable to download" errors in Wabbajack, then log out of Nexus within Wabbajack, then log back in. Once you've done that, try downloading again.

- **Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#pre-installation) step.

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

Magnum Opus updates based on a [Semantic Versioning](https://en.wikipedia.org/wiki/Software_versioning) system.

Generally speaking:  
- Full x.0 (2.0, 3.0, etc) updates requires a new game.  
- Major x.x (2.1, 2.2 etc) updates requires a new game.  
- Minor x.x.x (2.1.1, 2.1.2) updates can be applied to an ongoing playthrough.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

If you wish for Wabbajack to ignore any additional mods you've installed, rename them to say `[NoDelete]` at the beginning of the name.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

## Post Installation

This section includes things like the BiRaitBec textures/WorkBase Improved (WBI)/Mod Config Menu (MCM)/etc. and [has been moved to its own page, just to really make it stand out in its importance.](https://github.com/LivelyDismay/magnum-opus/blob/main/postinstall.md) **Magnum Opus WILL CRASH CONSTANTLY if you do not do this part.**

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

## FAQ

I've been doing this for a while now, so [I've compiled the most common questions into one handy spot!](https://github.com/LivelyDismay/magnum-opus/blob/main/faq.md) Please check this out first, then come on over to [my Discord](https://discord.gg/livelymods) if you need further assistance.

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

## Widescreen Support

I don't own a widescreen monitor, so I can't help directly. I don't mind you guys helping each other though, obviously. A generous discord user did write this for you:

For everyone using an ultra wide monitor with ratios 32:9 or 21:9 (3840×1080 / 5120×1440 / 3440×1440 / 2560 × 1080), here is the fix for a bulk of the most serious problems, such as not being able to distribute stats and name your character, or not being able to properly use the TAB menu.

The issue is fixed by using one of the two mods, based on your aspect ratio:  
- 32:9 [Super Ultra Wide Interface 32:9](https://www.nexusmods.com/fallout4/mods/56363)  
- 21:9 [Ultra Wide Interface 21:9](https://www.nexusmods.com/fallout4/mods/65677)  

Installing is a 3 step process, copy the inputs below.

Step 1:  
- XDI (Extended Dialogue Interface)  
- Another Mod  
- LooksMenu  
- Companion Command Menu Overhaul  
- Prewar Binoculars  

Step 2:
- FallUI - Inventory  
- FallUI - Workbench  
- FallUI - Confirm Boxes  
- FallUI - Sleep and Wait Menu  
- Vanilla  

Step 3:  
- (choose preference)  
- FallUI - HUD  
- (choose preference)  
- MCM Booster  
- (choose preference)  

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)

---

## Contact

I'm always available on [my own personal Discord Server](https://discord.gg/livelymods).

I stream most days [on Twitch](https://www.twitch.tv/livelymods) at 3:30 PM EST. Feel free to hang out, ask modding questions, or whatever. I like talking about modding stuff.

---

## Donate

Donations can be made via [Patreon](https://www.patreon.com/nicholasjae), [Ko-fi](https://ko-fi.com/livelymods), or Venmo (@Nicholas-Jae). Even $1/month makes a world of difference if enough people do it.

[[Top]](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#table-of-contents)
