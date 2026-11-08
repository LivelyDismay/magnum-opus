## Magnum Opus Frequently Asked Questions

---

### 📋 Table of Contents

#### ⌨️ Controls & Keybinds
- [Hotkeys?](#hotkeys)
- [Controller support?!?](#controller-support)

#### ⚙️ Modlist & Versioning Info
- [What version of Fallout 4 does this list use?](#fo4-version)
- [Load order? / What mods are in this list?](#load-order)
- [Can I add an ENB? Character presets? Cheat Terminal? Can I update mods? Remove mods?](#adding-mods)

#### 🛠️ In-Game Configuration & Mechanics
- [My Pipboy is inaccessible / invisible / showing random stuff I don't want to see / something is wrong. Fix it!](#pipboy-fix)
- [How do I repair Power Armor?](#repair-power-armor)
- [How do I use the Livelier Perks profile?](#livelier-perks)
- [How do I change my FOV?](#change-fov)
- [How do I cap/uncap my FPS?](#cap-fps)
- [When I start Magnum Opus, the game is zoomed in!](#game-zoomed-in)
- [Can I turn on the option to see what I'm scrapping?](#scrapping-visibility)
- [My flashlight isn't working!](#flashlight-broken)

#### 🤠 Gameplay & Balance
- [Can I have multiple companions at the same time?](#multiple-companions)
- [I'm using two Stimpaks instead of one. What gives?](#double-stimpaks)
- [I can't build anything / How do I increase settlement size?](#settlement-size)
- [I broke Workshop Plus and now I can't fly. What happened?](#workshop-plus-flight)
- [I randomly have god mode / I take no damage or rads / my stamina doesn't drain anymore. What happened?](#god-mode-bug)
- [I can't seem to hurt enemies that are in power armor!](#power-armor-enemies)
- [Why are feral ghouls so hard to kill?](#feral-ghouls)

#### 🚨 Technical Troubleshooting & Bugs
- [My game crashes when I launch from MO2. Help!](#mo2-crash)
- [My characters have black/brown/tan/bugged faces. What happened?](#black-face-bug)
- [I am having random crashes. What do I do?](#random-crashes)
- [Does Magnum Opus have Ultrawide Support?](#ultrawide-support)
- [I'm having problems downloading files in Wabbajack, how do I fix it?](#wabbajack-problems)
- [Any support for Linux?](#linux-support)

#### 💬 Miscellaneous
- [Are achievements enabled?](#achievements)
- [Hey Lively, is there a reason ... ?](#reason-why)
- [Can I buy you a drink?](#buy-drink)

---

### ⌨️ Controls & Keybinds

<details id="hotkeys">
  <summary><b>Hotkeys?</b></summary>

- **V** - VATS
- **Q** - Left lean (only when aiming down sights)
- **E** - Right lean (only when aiming down sights)
- **B** - Toggle West Tek optics (if equipped)  
- **N** - Upgrade SS2 plots with caps
- **[** - Faster Workshop
- **F** - Favorites
- **LeftAlt** - Power attack/bash/grenade
- **.** - Toggle flight in Workshop Mode (please see the troubleshooting section below when toggling flight)
- **Insert** - Extra object selection (Workshop Mode only) - recommend using for scrapping corpses. Don't use this to scrap buildings, roads, etc  
- **T** - Wait
- **Mouse3** - Toggle POV
- **Mouse4** - Dodge (kinda sucks but it's a package deal with the crouch-slide so whatever)

There are more keybinds listed in the MCM, in the very bottom option. I would encourage you to take note of them.
</details>

<details id="controller-support">
  <summary><b>Controller support?!?</b></summary>

Nah, I don't use a controller. If someone else wants to set up a controller config, I can add it as an optional file.

Make sure the Controller option is enabled in your settings (`Escape > Gameplay > Settings`).

If you're playing on a controller, your map probably doesn't work correctly. To fix this, edit your `Fallout4Prefs.ini` in the `MagnumOpus/profiles` folder and edit the following lines under the `[Display]` section to read as follows:

`uPipboyTargetHeight=700`
`uPipboyTargetWidth=876`

Failing all that, open the MCM Config, go to Baka Fullscreen Pipboy, and disable the main option.
</details>

---

### ⚙️ Modlist & Versioning Info

<details id="fo4-version">
  <summary><b>What version of Fallout 4 does this list use?</b></summary>

1.10.163. Pre-NG. Wabbajack handles the downgrade for you, so please remember to keep your Steam version on the latest update. This information is only useful for adding version-dependent mods.
</details>

<details id="load-order">
  <summary><b>Load order? / What mods are in this list?</b></summary>

[Have a look.](https://loadorderlibrary.com)
</details>

<details id="adding-mods">
  <summary><b>Can I add an ENB? Character presets? Cheat Terminal? Can I update mods? Remove mods?</b></summary>

If you hate yourself, sure. Some people have added ENBs and reported consistent crashes, so your mileage may vary. Don't add an ENB and report bugs to me because I can't/won't help. This will void official support.

If you ask about adding presets in my support channel, I'm going to give you the Rule 11 role. Why? Because 1. you're adding stuff, and 2. a lot of presets have other required mods in order to work. It's a slippery slope, and I'm extremely unwilling to deal with it. Plus, frankly, adding presets is the easiest thing in the world, so if you're asking how to do it, you obviously haven't bothered trying to do anything for yourself, and I'm not here to hold your hand.

You can update and remove whatever you want, but this will void any official support. Sometimes I [write guides on how to do these things](https://github.com).
</details>

---

### 🛠️ In-Game Configuration & Mechanics

<details id="pipboy-fix">
  <summary><b>My Pipboy is inaccessible / invisible / showing random stuff I don't want to see / something is wrong. Fix it!</b></summary>

Open your MCM Configs, select the Baka Fullscreen Pipboy entry, and deactivate it.
</details>

<details id="repair-power-armor">
  <summary><b>How do I repair Power Armor?</b></summary>

Craft Power Armor Repair Kits at the Engineering Workbench, or purchase them from applicable vendors (such as the Atom Cats or Brotherhood of Steel). [More information available here.](https://youtu.be)
</details>

<details id="livelier-perks">
  <summary><b>How do I use the Livelier Perks profile?</b></summary>

It's a little complicated because I can't really provide direct patches/support for this mod in a Wabbajack list, but let's go through it step by step.
- Launch Fallout 4 through Steam.
- Open the Creations storefront.
- Download Livelier Perks.
- Close Fallout 4.
- Back in Steam, in your Library tab, right-click on `Fallout 4`.
- Navigate to `Manage > Browse local files`. This will open a Windows Explorer.
- Double click the `Data` folder.
- Scroll down until you find `livckperkoverhaulfinalihope.esp` and select it. You do not need the ba2 for Magnum Opus. You can delete it if you wish to keep your game folder clean.
- Copy (ctrl+c) or Cut (ctrl+x) this file.
- In Magnum Opus' Mod Organizer 2, change the profile at the top from `Magnum Opus` to `Magnum Opus - Livelier Perks`.
- Scroll to the bottom of the mods in the left pane, and go to the section labeled `Lively's VC Shenanigans`.
- Inside that section, you'll see a mod called `Livelier Perks`. Right-click this mod and select `Open in Explorer`.
- Paste (ctrl+v) the file you copied/cut a few moments ago.
- Back in Mod Organizer 2, press F5 to refresh the program.
- Scroll down to the bottom of the Plugins list on the right to make sure `LivCKPerkOverhaulFinalIHope.esp` is active.
  - Your Plugins need to be sorted by Priority here. This is the default setting, so no need to do anything. But if you changed it, then change it back to Priority.
- Back in the left pane of Mod Organizer 2, activate the next mod below Livelier Perks, entitled `Sorter - Livelier Perks Profile`.
- Enjoy the game.

I know it sounds like a lot, but it seriously takes like 30 seconds. I'm just writing this to be as foolproof as possible. And thanks for your support!

The bottom of your Plugins pane should look like this:  
![alt text](https://github.com)  

It's okay if the perk overhaul is higher up, as long as it remains above the ones in the screenshot.
</details>

<details id="change-fov">
  <summary><b>How do I change my FOV?</b></summary>

While in game, press Escape, select `Mod Config`, then head down to `Simple FOV Slider`.

Do note that increasing your FOV also increases the amount of objects being rendered on screen at once, which could potentially result in a drop in performance.
</details>

<details id="cap-fps">
  <summary><b>How do I cap/uncap my FPS?</b></summary>

In Mod Organizer, find the `High FPS Physics Fix` mod. Double click it. In the pop-up window, select the `INI Files` tab, then select the only INI listed. In the right pane, scroll down about halfway until you see `InGameFPS=`. Change the number to your liking (0 = uncapped).
</details>

<details id="game-zoomed-in">
  <summary><b>When I start Magnum Opus, the game is zoomed in!</b></summary>

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
</details>

<details id="scrapping-visibility">
  <summary><b>Can I turn on the option to see what I'm scrapping?</b></summary>

Yeah. Open your MCM and head down to FallUI Confirm Boxes. Options are in there.
</details>
<details id="flashlight-broken">
  <summary><b>My flashlight isn't working!</b></summary>

If you're just starting the game and you're still in Vault 111, know that the your Pipboy flashlight will not work between the time you pick it up and the time you press the button to open the vault door. It genuinely amazes me how many people report this to me. Just press the button, it's right there.

Otherwise, some weapons that have flashlight attachment hijack the Pipboy flashlight, so even if you have the weapon holstered it still activates. Either change weapons, or use a different attachment.
</details>

---

### 🤠 Gameplay & Balance

<details id="multiple-companions">
  <summary><b>Can I have multiple companions at the same time?</b></summary>

[Heather Casdin](https://nexusmods.com) doesn't occupy a "follower" slot, so you can have Heather + another companion. You can also have Dogmeat alongside a companion.
</details>

<details id="double-stimpaks">
  <summary><b>I'm using two Stimpaks instead of one. What gives?</b></summary>

Sporadic issue that happens to a few users. Don't know why. There is a mod in the Optional section of Mod Organizer 2 entitled `Double Stimpak Bug Fix - Remove Stimpak Animation on Use` which will negate the issue, but will also remove the Stimpak animation on use (obviously). Enable it to fix this bug (and remove the animation...obviously).
</details>

<details id="settlement-size">
  <summary><b>I can't build anything / How do I increase settlement size?</b></summary>

If you can't build anything in Workshop mode, odds are you're at the Build Limit (that bar in the top right). To increase your build limit, approach a workshop and press Space, then Configure Build Limit.

Increasing this too much can harm performance. Use at your own risk.
</details>

<details id="workshop-plus-flight">
  <summary><b>I broke Workshop Plus and now I can't fly. What happened?</b></summary>

DO NOT enter Workshop Mode with a jet pack equipped. This will permanently break that jet pack's functionality.
</details>

<details id="god-mode-bug">
  <summary><b>I randomly have god mode / I take no damage or rads / my stamina doesn't drain anymore. What happened?</b></summary>

Workshop Plus didn't uninitialize, apparently. Enter workshop mode, sit tight for a few seconds, then exit workshop mode. That should fix it. Try not to open your Pipboy for a few seconds after exiting workshop mode.
</details>

<details id="power-armor-enemies">
  <summary><b>I can't seem to hurt enemies that are in power armor!</b></summary>

This modlist uses a really cool mod called [Bastion](https://nexusmods.com) that makes power armor actually prevent damage taken on a body part until the piece of armor covering that part is destroyed. This works for both you _and_ enemies. Some weapons also have built in armor penetration, mostly based on caliber (think .50 cal and 2mm EC for example).
</details>

<details id="feral-ghouls">
  <summary><b>Why are feral ghouls so hard to kill?</b></summary>

They're basically zombies. Go for the head. Other body parts have a pretty high damage resistance.
</details>

---

### 🚨 Technical Troubleshooting & Bugs

<details id="mo2-crash">
  <summary><b>My game crashes when I launch from MO2. Help!</b></summary>

Make sure you disable any overlays - most notably, Medal.TV seems to cause this crash frequently for those with that program.

The other most common cause is an Antivirus (not Windows Defender; a third party antivirus like AVG, BitDefender, Kapersky, Webroot, etc). Disable those or exclude MO2/scriptextender/etc.
</details>

<details id="black-face-bug">
  <summary><b>My characters have black/brown/tan/bugged faces. What happened?</b></summary>

First, ensure you do NOT have the High Definition DLC active in Steam. If you don't, then quite frankly, the so-called "Black Face Bug" can happen randomly. Saving and reloading should fix it. You can also use the console to disable then enable the NPC with the bug. Most common cause is fast traveling, which will force the game to load a lot of stuff at once, and NPCs tend to get kinda left behind. But regardless, it's pretty random.
</details>

<details id="random-crashes">
  <summary><b>I am having random crashes. What do I do?</b></summary>

First, please make sure the crashes are repeatable. There is very little I can do for one-off crashes. Chalk those up to "shit happens."

Buffout 4 generates crash logs for you in the `\Documents\My Games\Fallout4\F4SE` folder. These are vital to diagnosing the problem.

One possibility is that your grenades got corrupted (your crash log may have references to `PipboyMapData` if this crash happens). I don't know how or why this happens, but it is possible. Unequip your grenades. If the crashes stop happening, toss that stack of grenades in the trash. Spawn yourself new ones if you want. Otherwise, keep reading. (If anyone ever finds a reason that this happens, I'd love to know about it.)

If your crash log references `nvwgf2umx.dll` a bunch of times, that's an Nvidia Driver crash. Downgrading to pre-445 drivers will fix this. 442.74 versions seem preferable. [Here's a link for you](https://github.com).

If your crash log references `BGSSaveLoadManager` frequently, or `usvs::hook_DeleteFile`, or both, you are most likely running BitDefender. [Here's a link to help with that](https://bitdefender.com).

If your crash log references an `xAudio dll` file, I have no idea how to fix this. I don't think anyone knows how to fix this. If you ever find a solution, I'd love to know about it.

Barring those reasons, there are still a plethora of other possibilities. [Auto Scanner](https://nexusmods.com) can catch a ton of these. It is recommended you run your crash log through this script (it's easy, you copy and paste the file, double click a thing, and press a button - no special knowledge required) and check the results. There is also a handy dandy `HOW TO READ CRASH LOGS.pdf` file you can reference.

If you've been unable to diagnose your issue after all that, feel free to upload your crash log to me on [Discord](https://discord.gg). Maybe I can figure something out.
</details>

<details id="ultrawide-support">
  <summary><b>Does Magnum Opus have Ultrawide Support?</b></summary>

No. I don't own an Ultrawide monitor. Some of the other people playing this list do, and one of them [wrote this guide](https://google.com) for their own Ultrawide setup. I make no guarantees on how accurate or up-to-date this information is, and I cannot help you troubleshoot any issues that arise from using an Ultrawide. This will not void official support, but I do expect you to learn how to utilize your own hardware. I can't do it for you.
</details>

<details id="wabbajack-problems">
  <summary><b>I'm having problems downloading files in Wabbajack, how do I fix it?</b></summary>

If the files that Wabbajack is getting stuck on are base game files, you should make sure to follow **all** the [Pre-Installation instructions in the README](https://github.com).

The most common files that fail to download through Wabbajack are as follows:
- [More Hairstyles - Beards](http://mediafire.com)
- [Misc Hairstyles 1.6](http://mediafire.com)

Download these files manually, paste them into your `downloads` folder that you specified for Wabbajack, then rerun the installation.

If you're getting a lot of "unable to download" errors in Wabbajack outside of the base game files and the files mentioned above, or Wabbajack is saying it failed to find a Nexus login token, then log out of Nexus within Wabbajack, then log back in. Once you've done that, close and reopen Wabbajack, then try downloading the modlist again.
</details>

<details id="linux-support">
  <summary><b>Any support for Linux?</b></summary>

No. I'm told you have to disable MCM Booster. Other than that, there is a linux-support channel in the [Wabbajack Discord](https://discord.gg). I'd recommend heading there. Omni really knows his stuff.
</details>

---

### 💬 Miscellaneous

<details id="achievements">
  <summary><b>Are achievements enabled?</b></summary>

Yes.
</details>

<details id="reason-why">
  <summary><b>Hey Lively, is there a reason ... ?</b></summary>

No matter how this question ends, the answer is the same: Because I want to, or because I didn't want to.
</details>

<details id="buy-drink">
  <summary><b>Can I buy you a drink?</b></summary>

[Yep.](https://patreon.com)
</details>

---


