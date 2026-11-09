<h1 align="center">Frequently Asked Questions</h1>


#### ⌨️ Controls & Keybinds
- [Hotkeys?](#hotkeys)
- [Controller support?!?](#controller-support)

#### ⚙️ Editing the List
- [What version of Fallout 4 does this list use?](#what-version-of-fallout-4-does-this-list-use)
- [Load order? / What mods are in this list?](#load-order--what-mods-are-in-this-list)
- [Can I add an ENB? Character presets? Cheat Terminal? Can I update mods? Remove mods?](#can-i-add-an-enb-character-presets-cheat-terminal-can-i-update-mods-remove-mods)
- [Can I adjust Community Shaders' settings?](#can-i-adjust-community-shaders-settings)
- [Does Magnum Opus have Upscaling and/or FrameGen?](#does-magnum-opus-have-upscaling-andor-framegen)

#### 🛠️ In-Game Configuration & Mechanics
- [How do I repair Power Armor?](#how-do-i-repair-power-armor)
- [What is the Livelier Perks profile? How do I use it?](#what-is-the-livelier-perks-profile-how-do-i-use-it)
- [How do I change my FOV?](#how-do-i-change-my-fov)
- [How do I cap/uncap my FPS?](#how-do-i-capuncap-my-fps)
- [When I start Magnum Opus, the game is zoomed in!](#when-i-start-magnum-opus-the-game-is-zoomed-in)
- [Can I turn on the option to see what I'm scrapping?](#can-i-turn-on-the-option-to-see-what-im-scrapping)
- [My flashlight isn't working!](#my-flashlight-isnt-working)

#### 🤠 Gameplay & Balance
- [Can I have multiple companions at the same time?](#can-i-have-multiple-companions-at-the-same-time)
- [I'm using two Stimpaks instead of one. What gives?](#im-using-two-stimpaks-instead-of-one-what-gives)
- [I can't build anything / How do I increase settlement size?](#i-cant-build-anything--how-do-i-increase-settlement-size)
- [I broke Workshop Plus and now I can't fly. What happened?](#i-broke-workshop-plus-and-now-i-cant-fly-what-happened)
- [I randomly have god mode / I take no damage or rads / my stamina doesn't drain anymore. What happened?](#i-randomly-have-god-mode--i-take-no-damage-or-rads--my-stamina-doesnt-drain-anymore-what-happened)
- [I can't seem to hurt enemies that are in power armor!](#i-cant-seem-to-hurt-enemies-that-are-in-power-armor)
- [Why are feral ghouls so hard to kill?](#why-are-feral-ghouls-so-hard-to-kill)

#### 🚨 Technical Troubleshooting & Bugs
- [Do I have to follow safe saving practices?](#do-i-have-to-follow-safe-saving-practices)
- [My Pipboy is inaccessible / invisible / showing random stuff I don't want to see / something is wrong. Fix it!](#my-pipboy-is-inaccessible--invisible--showing-random-stuff-i-dont-want-to-see--something-is-wrong-fix-it)
- [My game crashes when I launch from MO2. Help!](#my-game-crashes-when-i-launch-from-mo2-help)
- [My characters have black/brown/tan/bugged faces. What happened?](#my-characters-have-blackbrowntanbugged-faces-what-happened)
- [I am having random crashes. What do I do?](#i-am-having-random-crashes-what-do-i-do)
- [Does Magnum Opus have Ultrawide Support?](#does-magnum-opus-have-ultrawide-support)
- [I'm having problems downloading files in Wabbajack, how do I fix it?](#im-having-problems-downloading-files-in-wabbajack-how-do-i-fix-it)
- [Any support for Linux?](#any-support-for-linux)

#### 💬 Miscellaneous
- [How is Magnum Opus different from this other modlist I saw?](#how-is-magnum-opus-different-from-this-other-modlist-i-saw)
- [Are achievements enabled?](#are-achievements-enabled)
- [There are so many mods, where do I even get started?](#there-are-so-many-mods-where-do-i-even-get-started)
- [Why are you so rude? I hear so many negative things about you.](#why-are-you-so-rude-i-hear-so-many-negative-things-about-you)
- [Hey Lively, is there a reason ... ?](#hey-lively-is-there-a-reason--)
- [Can I buy you a drink?](#can-i-buy-you-a-drink)

---

<br>
<p align="center">◆ ═════════ ⌨️ ═════════ ◆</p>
<br>

<h3 align="center">Controls & Keybinds</h3>

<br>
<p align="center">◆ ═════════ ⌨️ ═════════ ◆</p>
<br>

---

### Hotkeys?

- **V** - VATS
- **Q** - Left lean (only when aiming down sights)
- **E** - Right lean (only when aiming down sights)
- **B** - Toggle West Tek optics (if equipped)  
- **N** - Upgrade SS2 plots with caps
- **[** - Faster Workshop
- **F** - Favorites
- **LeftAlt** - Power attack/bash/grenade
- **.** - Toggle flight in Workshop Mode (please see [this issue]((#i-randomly-have-god-mode--i-take-no-damage-or-rads--my-stamina-doesnt-drain-anymore-what-happened)) below when toggling flight)
- **Insert** - Extra object selection (Workshop Mode only) - recommend using for scrapping corpses. Don't use this to scrap buildings, roads, etc  
- **T** - Wait
- **Mouse3** - Toggle POV
- **Mouse4** - Dodge (kinda sucks but it's a package deal with the crouch-slide so whatever)

There are more keybinds listed in the MCM, in the very bottom option. I would encourage you to take note of them. This also tells you which keybinds are from which mods, so you can change them if you so desire.

Please be wary when changing keybinds. If a key is set to two functions, it will not do either thing. You'll have to resolve these issues on your own if you encounter them.

[[Top]](#table-of-contents)

---

### Controller support?!?

Nah, I don't use a controller. If someone else wants to set up a controller config, I can add it as an optional file.

Make sure the Controller option is enabled in your settings (`Escape > Gameplay > Settings`).

If you're playing on a controller, your map probably doesn't work correctly. To fix this, edit your `Fallout4Prefs.ini` in the `MagnumOpus/profiles` folder and edit the following lines under the `[Display]` section to read as follows:

`uPipboyTargetHeight=700`
`uPipboyTargetWidth=876`

Failing all that, open the MCM Config, go to Baka Fullscreen Pipboy, and disable the main option.

[[Top]](#table-of-contents)

---

<br>
<p align="center">◆ ═════════ ⚙️ ═════════ ◆</p>
<br>

<h3 align="center">Editing the List</h3>

<br>
<p align="center">◆ ═════════ ⚙️ ═════════ ◆</p>
<br>

---

### What version of Fallout 4 does this list use?

1.11.240. This is the latest version at the time of this writing. This information is only useful for adding version-dependent mods. If you are adding mods, please remember to use the Rule-11 channels in Discord if seeking support.

[[Top]](#table-of-contents)

---

### Load order? / What mods are in this list?

[Have a look.](https://loadorderlibrary.com/lists/magnum-opus)

[[Top]](#table-of-contents)

---

### Can I add an ENB? Character presets? Cheat Terminal? Can I update mods? Remove mods?

Magnum Opus now comes with Community Shaders as of version 9.6.0. ENBs will not work, and adding one will force Community Shaders to disable itself. Do not add an ENB.

If you ask about adding presets in my support channel, I'm going to give you the Rule 11 role. Why? Because 1. you're adding stuff, and 2. a lot of presets have other required mods in order to work. It's a slippery slope, and I'm extremely unwilling to deal with it. Plus, frankly, adding presets is the easiest thing in the world, so if you're asking how to do it, you obviously haven't bothered trying to do anything for yourself, and I'm not here to hold your hand.

You can update and remove whatever you want, but this will void any official support. Sometimes I [write guides on how to do these things](https://github.com/LivelyDismay/Learn-To-Mod/wiki).

[[Top]](#table-of-contents)

---

### Can I adjust Community Shaders' settings?

Yes. Press `End` to open Dear Modding UI and select the Community Shaders option. The `Home` section is for enabling/disabling specific features. Advanced is primarily for information. Each subsection has various settings you can adjust or toggle.

The only potentially problematic setting I've come across is for Screen Space Reflections under Dynamic Cubemaps. If your water is flickering or looking like it has stripes, disable this setting. I've left it on for now as the issues with water seem to be mostly resolved with the latest version of CS, though there are times when I can see how others may still be bothered by it.

Toggling any settings in the `Home` section requires you to restart the game before any changes take effect.

[[Top]](#table-of-contents)

---

### Does Magnum Opus have Upscaling and/or FrameGen?

Yes. Both are features of Community Shaders, which I've left enabled by default, against my better judgment. Like above, these can be adjusted in the Dear Modding UI (`End`) menu.

[[Top]](#table-of-contents)

---

<br>
<p align="center">◆ ═════════ 🛠️ ═════════ ◆</p>
<br>

<h3 align="center">In-Game Configuration & Mechanics</h3>

<br>
<p align="center">◆ ═════════ 🛠️ ═════════ ◆</p>
<br>



### How do I repair Power Armor?

Craft Power Armor Repair Kits at the Engineering Workbench, or purchase them from applicable vendors (such as the Atom Cats or Brotherhood of Steel). [More information available here.](https://youtu.be/OX2jOp9wrKs)

[[Top]](#table-of-contents)

---

### What is the Livelier Perks profile? How do I use it?

I'm a part of Bethesda's Verified Creator program. This means I can release mods on their storefront.

[Livelier Perks](https://creations.bethesda.net/en/fallout4/details/3b19ee36-06b9-45cb-985c-fd1720636d99/Livelier_Perks) is a mod I made for that program. Magnum Opus has a secondary profile to support this mod if you choose to purchase it. If you try to use this profile without Livelier Perks, the game will just crash, so please stick to the regular profile until you decide to purchase this.

If you choose to do this, launch Magnum Opus as you normally would and select the Creation Club menu option. Find Livelier Perks, buy it, and download it, then exit the game.

Back in Mod Organizer 2, make sure the left pane is sorted by "Priority." In the left pane, scroll all the way down until you see `Overwrite`. Right click on `Overwrite` and select `Open in Explorer`. Select the files named `LivCKPerkOverhaulFinalIHope` (there will be an .esp and a .ba2 file), then press Control+X to Cut them.

Back in MO2, just above the `Overwrite` section from earlier, there is a mod called `[NoDelete] Livelier Perks`. Right click this and open in explorer, then press Control+V to paste the files into here.

Back in MO2, click on `Profile` at the top and change it to `Magnum Opus - Livelier Perks`.

I know it sounds like a lot, but it seriously takes like 30 seconds. I'm just writing this to be as foolproof as possible.

Enjoy the game, and thank you for your support.

[[Top]](#table-of-contents)

---

### Can I swap profiles mid-save?

Probably not. Sorry. That would be quite problematic. You *might* be able to get away with it via using Livelier Perks to reset your perk chart, but I have not tested this and wouldn't recommend it.

[[Top]](#table-of-contents)

---

### How do I change my FOV?

While in game, press Escape, select `Mod Config`, then head down to `Simple FOV Slider`.

Do note that increasing your FOV also increases the amount of objects being rendered on screen at once, which could potentially result in a drop in performance. Changing your FOV may also result in buggy See-Through-Scopes. Consider yourself warned.

[[Top]](#table-of-contents)

---

### How do I cap/uncap my FPS?

In Mod Organizer, find the `High FPS Physics Fix` mod. If you can't find it, look at the box that says `Filter` in the bottom of the Mod Organizer 2 window and start typing the name of the mod. Once you find it, double click it. In the pop-up window, select the `INI Files` tab, then select the only INI listed. In the right pane, scroll down about halfway until you see `InGameFPS=`. Change the number to your liking (0 = uncapped).

[[Top]](#table-of-contents)

---

### When I start Magnum Opus, the game is zoomed in!

Windows Scaling is messing with the game. To fix this:

- Go the folder you installed Magnum Opus into
- Then go into the `Stock Game` folder
- Right click on the `Fallout4.exe` item
- Choose `Properties`
- Select the `Compatibility` tab at the top of that window
- Click the `Change high DPI settings` button
- Put a checkmark in the `Override high DPI scaling behavior` box
- Choose `Application` in the dropdown list just below the previous checkbox

Note: Wording may not be exact, but should be similar enough.

[[Top]](#table-of-contents)

---

### Can I turn on the option to see what I'm scrapping?

Yes. Open your MCM and head down to `FallUI - Confirm Boxes`, then the Workshop tab. Options are in there. You're looking for the `Skip dialog` setting under the `Scrap entity` header.

[[Top]](#table-of-contents)

---

### My flashlight isn't working!

If you're just starting the game and you're still in Vault 111, know that the your Pipboy flashlight will not work between the time you pick it up and the time you press the button to open the vault door. It genuinely amazes me how many people report this to me. Just press the button, it's right there.

Otherwise, some weapons that have flashlight attachment hijack the Pipboy flashlight, so even if you have the weapon holstered it still activates. Either change weapons, or use a different attachment.

[[Top]](#table-of-contents)

---

<br>
<p align="center">◆ ═════════ 🤠 ═════════ ◆</p>
<br>

<h3 align="center">Gameplay & Balance</h3>

<br>
<p align="center">◆ ═════════ 🤠 ═════════ ◆</p>
<br>

---

### Can I have multiple companions at the same time?

[Heather Casdin](https://www.nexusmods.com/fallout4/mods/23273) doesn't occupy a "follower" slot, so you can have Heather + another companion. You can also have Dogmeat alongside a companion.

[[Top]](#table-of-contents)

---

### I'm using two Stimpaks instead of one. What gives?

Sporadic issue that happens to a few users. Don't know why. There is a mod in the Optional section of Mod Organizer 2 entitled `Double Stimpak Bug Fix - Remove Stimpak Animation on Use` which will negate the issue, but will also remove the Stimpak animation on use (obviously). Enable it to fix this bug (and remove the animation...obviously).

[[Top]](#table-of-contents)

---

### I can't build anything / How do I increase settlement size?

If you can't build anything in Workshop mode, odds are you're at the Build Limit (that bar in the top right). To increase your build limit, approach a workshop and press Space, then Configure Build Limit.

Increasing this too much can harm performance. Use at your own risk.

[[Top]](#table-of-contents)

---

### I broke Workshop Plus and now I can't fly. What happened?

DO NOT enter Workshop Mode with a jet pack equipped. This will permanently break that jet pack's functionality.

[[Top]](#table-of-contents)

---

### I randomly have god mode / I take no damage or rads / my stamina doesn't drain anymore. What happened?

Workshop Plus didn't uninitialize, apparently. Enter workshop mode, sit tight for a few seconds, then exit workshop mode. That should fix it. Try not to open your Pipboy for a few seconds after exiting workshop mode.

[[Top]](#table-of-contents)

---

### I can't seem to hurt enemies that are in power armor!

This modlist uses a really cool mod called [Bastion](https://www.nexusmods.com/fallout4/mods/75184) that makes power armor actually prevent damage taken on a body part until the piece of armor covering that part is destroyed. This works for both you _and_ enemies. Some weapons also have built in armor penetration, mostly based on caliber (think .50 cal and 2mm EC for example).

[[Top]](#table-of-contents)

---

### Why are feral ghouls so hard to kill?

They're basically zombies. Go for the head. Other body parts have a pretty high damage resistance. Explosions also work well.

[[Top]](#table-of-contents)

---
<br>
<p align="center">◆ ═════════ 🚨 ═════════ ◆</p>
<br>

<h3 align="center">Technical Troubleshooting & Bugs</h3>

<br>
<p align="center">◆ ═════════ 🚨 ═════════ ◆</p>
<br>

---

### Do I have to follow safe saving practices?

Oh boy. [Here we go again.](https://github.com/LivelyDismay/magnum-opus/blob/main/safesaving.md)

[[Top]](#table-of-contents)

---

### My Pipboy is inaccessible / invisible / showing random stuff I don't want to see / something is wrong. Fix it!

Open your MCM Configs, select the Baka Fullscreen Pipboy entry, and deactivate it.

[[Top]](#table-of-contents)

---
### My game crashes when I launch from MO2. Help!

Make sure you disable any overlays - most notably, Medal.TV seems to cause this crash frequently for those with that program.

The other most common cause is an Antivirus (not Windows Defender; a third party antivirus like AVG, BitDefender, Kapersky, Webroot, etc). Disable those or exclude MO2/scriptextender/etc.

If you swapped to the Livelier Perks profile and you don't own Livelier Perks, then the game will instantly crash.

[[Top]](#table-of-contents)

---

### My characters have black/brown/tan/bugged faces. What happened?

First, ensure you do NOT have the High Definition DLC active in Steam. If you don't, then quite frankly, the so-called "Black Face Bug" can happen randomly. Saving and reloading should fix it. You can also use the console to disable then enable the NPC with the bug. Most common cause is fast traveling, which will force the game to load a lot of stuff at once, and NPCs tend to get kinda left behind. But regardless, it's pretty random.

[[Top]](#table-of-contents)

---

### I am having random crashes. What do I do?

First, please make sure the crashes are repeatable. There is very little I can do for one-off crashes. Chalk those up to "shit happens."

Buffout 4 generates crash logs for you in the `\Documents\My Games\Fallout4\F4SE` folder. These are vital to diagnosing the problem.

One possibility is that your grenades got corrupted (your crash log may have references to `PipboyMapData` if this crash happens). I don't know how or why this happens, but it is possible. Unequip your grenades. If the crashes stop happening, toss that stack of grenades in the trash. Spawn yourself new ones if you want. Otherwise, keep reading. (If anyone ever finds a reason that this happens, I'd love to know about it.)

If your crash log references `nvwgf2umx.dll` a bunch of times, that's an Nvidia Driver crash. Downgrading to pre-445 drivers will fix this. 442.74 versions seem preferable. [Here's a link for you](https://github.com/keylase/nvidia-patch/tree/master/win).

If your crash log references `BGSSaveLoadManager` frequently, or `usvs::hook_DeleteFile`, or both, you are most likely running BitDefender. [Here's a link to help with that](https://www.bitdefender.com/consumer/support/answer/28557/).

If your crash log references an `xAudio dll` file, I have no idea how to fix this. I don't think anyone knows how to fix this. If you ever find a solution, I'd love to know about it.

Barring those reasons, there are still a plethora of other possibilities. [Auto Scanner](https://www.nexusmods.com/fallout4/mods/56255) can catch a ton of these. It is recommended you run your crash log through this script (it's easy, you copy and paste the file, double click a thing, and press a button - no special knowledge required) and check the results. There is also a handy dandy `HOW TO READ CRASH LOGS.pdf` file you can reference.

If you've been unable to diagnose your issue after all that, feel free to upload your crash log to me on [Discord](https://discord.gg/livelymods). Maybe I can figure something out.

[[Top]](#table-of-contents)

---

### Does Magnum Opus have Ultrawide Support?

No. I don't own an Ultrawide monitor. Some of the other people playing this list do, and one of them [wrote this guide](https://docs.google.com/document/d/1EbZ_DpyhctsrpBlylDYc2TXtm1NAOjkcYjRCNZsC958/edit) for their own Ultrawide setup. I make no guarantees on how accurate or up-to-date this information is, and I cannot help you troubleshoot any issues that arise from using an Ultrawide. This will not void official support, but I do expect you to learn how to utilize your own hardware. I can't do it for you.

[[Top]](#table-of-contents)

---

### I'm having problems downloading files in Wabbajack, how do I fix it?


If the files that Wabbajack is getting stuck on are base game files, you should make sure to follow **all** the [Pre-Installation instructions in the README](https://github.com/LivelyDismay/magnum-opus/blob/main/README.md#pre-installation).

If you're getting a lot of "unable to download" errors in Wabbajack outside of the base game files and the files mentioned above, or Wabbajack is saying it failed to find a Nexus login token, then log out of Nexus within Wabbajack, then log back in. Once you've done that, close and reopen Wabbajack, then try downloading the modlist again.

The most common files that fail to download through Wabbajack are as follows:
- [More Hairstyles - Beards](http://www.mediafire.com/file/iztz7iidy6djz1e/MoreHairstyles-Beards.rar/file)
- [Misc Hairstyles 1.6](http://www.mediafire.com/file/kfac38dni6d53rp/MiscHairstyle1.6_by_Atherisz.7z/file)

Download these files manually, paste them into your `downloads` folder that you specified for Wabbajack, then rerun the installation.

[[Top]](#table-of-contents)

---

### Any support for Linux?

No. There is a linux-support channel in the [Wabbajack Discord](https://discord.gg/wabbajack). I'd recommend heading there. Omni really knows his stuff.

[[Top]](#table-of-contents)

---

<br>
<p align="center">◆ ═════════ 💬 ═════════ ◆</p>
<br>

<h3 align="center">Miscellaneous</h3>

<br>
<p align="center">◆ ═════════ 💬 ═════════ ◆</p>
<br>

---

### How is Magnum Opus different from this other modlist I saw?

Well, the short answer is, I don't really know. I have very little idea of what goes on with other lists. I prefer to stay in my own little corner and mind my own business.

I do catch wind of things on occasion though, so I guess the long answer is more fragmented:

- I avoid AI slop bullshit whenever possible. Magnum Opus will never have vibe coded plugins from people I don't trust can read and troubleshoot the code. So any of those magic-sounding mods that people like Asciimov make are out of the question.
- I patch and test extensively. This is a passion project. It's not a door into anything else. It's not something I aim to monetize. It's not a portfolio piece. I've been working on this list since 2020 with no breaks. Even if the list isn't being actively updated, I still do support every single day. Every. Single. Day. Because I genuinely just want you to have a good time. But most importantly, I want me to have a good time. And for me to have a good time, the list needs to be the best it can be. This means I have to check every record, every cell, every door, every tree, every line of dialogue...just everything. It also means I don't abandon my modlist then only come back to it when it's convenient for me to do so.
- I don't steal shit from other people or scam users out of money. There has never been a single instance of me taking credit for someone else's work, or spamming so many micro-patches on Nexus and scamming them for so many Donation Points that the owners had to revamp the entire system. I've never tried to use my "position" to scam people for money. There was a time I relied heavily on donations, and I'm grateful I was able to do so, but even then, I've always said to take care of yourselves first. 

If you're ever mildly curious about some behind-the-curtains type of look into this list, pop open the `Lively's Patches` folder and see what's in there. That's years of work in one folder, none of which is on Nexus. If they were, I'd probably make thousands of dollars more from Donation Points, but it just doesn't seem like the right thing to do, so here it stays, a Magnum Opus exclusive.

And if you're reading this and think I'm talking about you, you're probably right. If not, then enjoy the list. It's the best one there is by a long shot.

[[Top]](#table-of-contents)

---

### Are achievements enabled?

Yes.

[[Top]](#table-of-contents)

---

### There are so many mods, where do I even get started?

Once you exit the Vault, you will be prompted to apply the MCM Preset. Please do this. You'll also have a quest enabled by default with a marker that's like five feet away from you. This leads you to the Beginners Guide Terminal, which I keep updated with tips on what to do and where to go in the early game.

Other than that, I try to make the modlist as cohesive as possible. I don't like when things stand out and are very obviously "modded content," so I would simply encourage you to explore naturally and let things happen as they may. Play like you've never seen this world before; you're sure to find lots of new things. 

[[Top]](#table-of-contents)

---

### Hey Lively, is there a reason ... ?

No matter how this question ends, the answer is the same: Because I want to, or because I didn't want to.

[[Top]](#table-of-contents)

---

### Why are you so rude? I hear so many negative things about you.

I've been making this modlist for about six years now. I've done free support that whole time. I've met a countless number of people from all walks of life. I've learned most people are rude, selfish, and treat me like an IT employee, despite the fact that this is entirely a volunteer project from me.

As such, I have learned to be as straight to the point with my responses as I can be until I get a better grasp of what type of person you are. You'll warm up to me, I'm sure of it. Eventually.

[[Top]](#table-of-contents)

---

### Can I buy you a drink?

[Yep.](https://www.patreon.com/nicholasjae)

[[Top]](#table-of-contents)
