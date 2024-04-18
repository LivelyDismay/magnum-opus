## Magnum Opus Frequently Asked Questions

---

### Table of Contents
- [Magnum Opus Frequently Asked Questions](#magnum-opus-frequently-asked-questions)
  - [Table of Contents](#table-of-contents)
  - [Hotkeys?](#hotkeys)
  - [My game crashes when I launch from MO2. Help!](#my-game-crashes-when-i-launch-from-mo2-help)
  - [My characters have black/brown/tan/bugged faces. What happened?](#my-characters-have-blackbrowntanbugged-faces-what-happened)
  - [Some people have weird black spots on their body, why don't you fix it?](#some-people-have-weird-black-spots-on-their-body-why-dont-you-fix-it)
  - [Controller support?!?](#controller-support)
  - [VAFS no work, plz fix](#vafs-no-work-plz-fix)
  - [I can't build anything / how do I increase settlement size?](#i-cant-build-anything--how-do-i-increase-settlement-size)
  - [I broke Workshop Plus and now I can't fly. What happened?](#i-broke-workshop-plus-and-now-i-cant-fly-what-happened)
  - [I am having random crashes. What do I do?](#i-am-having-random-crashes-what-do-i-do)
  - [I randomly have god mode / I take no damage or rads / my stamina doesn't drain anymore. What happened?](#i-randomly-have-god-mode--i-take-no-damage-or-rads--my-stamina-doesnt-drain-anymore-what-happened)
  - [When I start Magnum Opus, the game is zoomed in!](#when-i-start-magnum-opus-the-game-is-zoomed-in)
  - [How do I cap/uncap my FPS?](#how-do-i-capuncap-my-fps)
  - [How do I edit the volumes for things like radios and voices?](#how-do-i-edit-the-volumes-for-things-like-radios-and-voices)
  - [I hate the HUD overlays while I'm in Power Armor. Can these be safely disabled?](#i-hate-the-hud-overlays-while-im-in-power-armor-can-these-be-safely-disabled)
  - [Why is there a crosshair on my Pip-Boy?](#why-is-there-a-crosshair-on-my-pip-boy)
  - [Can I have multiple companions at the same time?](#can-i-have-multiple-companions-at-the-same-time)
  - [I don't like the flashlight.](#i-dont-like-the-flashlight)
  - [Can I add an ENB?](#can-i-add-an-enb)
  - [Can I add character presets?](#can-i-add-character-presets)
  - [Can I update \<...\> mod?](#can-i-update--mod)
  - [What if I want to change/add/remove mods? Can you help me?](#what-if-i-want-to-changeaddremove-mods-can-you-help-me)
  - [Does Magnum Opus have Ultrawide Support?](#does-magnum-opus-have-ultrawide-support)
  - [I'm having problems downloading files, how do I fix it?](#im-having-problems-downloading-files-how-do-i-fix-it)
  - [How do I change my FOV?](#how-do-i-change-my-fov)
  - [Is the BiRaitBec Texture Optimization step required?](#is-the-biraitbec-texture-optimization-step-required)
  - [But I want to use Cheat Terminal?](#but-i-want-to-use-cheat-terminal)
  - [Pressing F11 crashes my game though!](#pressing-f11-crashes-my-game-though)
  - [Hey Lively, is there a reason ... ?](#hey-lively-is-there-a-reason--)
  - [Can I buy you a drink?](#can-i-buy-you-a-drink)

---

### Hotkeys?

**C** - Activate Critical  
**V** - Toggle first/third person  
**B** - Toggle West Tek optics (if equipped)  
**N** - Upgrade SS2 plots with caps  
**F11** - Open ESP Explorer (see below)  
**Q** - VAFS (VATS must be unbound, or bound to a different key, to function).  
**Insert** - Extra object selection (Workshop Mode only) - recommend using for scrapping corpses. Don't use this to scrap buildings, roads, etc.  
**T** - Wait

I would also recommend setting up an Undo hotkey in the Workshop Plus MCM. I use Ctrl+Z personally. This can undo the last action you took in workshop mode, such as accidentally scrapping something you didn't want to scrap.

[[Top]](#table-of-contents)

---

### My game crashes when I launch from MO2. Help!

Make sure you disable any overlays - most notably, Medal.TV seems to cause this crash frequently for those with that program.

The other most common cause is an Antivirus (not Windows Defender; a third party antivirus like AVG, BitDefender, Kapersky, Webroot, etc). Disable those or exclude MO2/scriptextender/etc.

[[Top]](#table-of-contents)

---

### My characters have black/brown/tan/bugged faces. What happened?

First, ensure you do NOT have the High Definition DLC active in Steam. If you don't, then quite frankly, the so-called "Black Face Bug" can happen randomly. Saving and reloading should fix it. You can also use the console to disable then enable the NPC with the bug.

[[Top]](#table-of-contents)

---

### Some people have weird black spots on their body, why don't you fix it?

This is a CBBE issue with some outfits and quite frankly, I can look past it. I'm not super adept with bodyslide and outfit studio, so...it is what it is. If you fix it, feel free to pop it on Nexus and I'll add it to the modlist.

[[Top]](#table-of-contents)

---

### Controller support?!?

Nah, I don't use a controller. If someone else wants to set up a controller config, I can add it as an optional file.

If using a controller with Magnum Opus v7, you may find the map doesn't work. If you experience that, go into the MCM menu for Baka Fullscreen and check "Use Pip-Boy Color From Settings".

[[Top]](#table-of-contents)

---

### VAFS no work, plz fix

VATS needs to be unbound or bound to a different key. I thought this would transfer over from my own custom control map, but apparently I was mistaken. You can do this in your vanilla key binds menu under Settings, and the VAFS MCM.

[[Top]](#table-of-contents)

---

### I can't build anything / how do I increase settlement size?

If you can't build anything in Workshop mode, odds are you're at the Build Limit (that bar in the top right). To increase your build limit, approach a workshop and press Space, then Configure Build Limit.

Increasing this too much can harm performance. Use at your own risk.

[[Top]](#table-of-contents)

---

### I broke Workshop Plus and now I can't fly. What happened?

DO NOT enter Workshop Mode with a jet pack equipped. This will permanently break that jet pack's functionality.

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

If you've been unable to diagnose your issue after all that, feel free to upload your crash log to me on [Discord](https://discord.gg/yABEjwB). Maybe I can figure something out.

[[Top]](#table-of-contents)

---

### I randomly have god mode / I take no damage or rads / my stamina doesn't drain anymore. What happened?

Workshop Plus didn't uninitialize, apparently. Enter and exit workshop mode, that should fix it. Try not to open your Pipboy for a few seconds after exiting workshop mode.

[[Top]](#table-of-contents)

---

### When I start Magnum Opus, the game is zoomed in!

Windows Scaling is messing with the game. To fix this:

- Go the folder you installed Magnum Opus into
- Then go into the "Stock Game" folder
- Right click on the "Fallout4.exe" item
- Choose "Properties"
- Select the "Compatibility" tab at the top of that window
- Click the "Change high DPI settings" button
- Put a checkmark in the "Override high DPI scaling behavior" box
- Choose "Application" in the dropdown list just below the previous checkbox

Note: Wording may not be exact, but should be similar enough.

[[Top]](#table-of-contents)

---

### How do I cap/uncap my FPS?

In Mod Organizer, find the `High FPS Physics Fix` mod. Double click it. In the pop-up window, select the `INI Files` tab, then select the only INI listed. In the right pane, scroll down about halfway until you see `InGameFPS=`. Change the number to your liking.

[[Top]](#table-of-contents)

---

### How do I edit the volumes for things like radios and voices?

While in game, press Escape, then select `Mod Config`. Scroll down to the section entitled `Persistent Volume Sliders`. Adjust to your liking.

Audio sliders for True Storms are in the vanilla Audio settings.

[[Top]](#table-of-contents)

---

### I hate the HUD overlays while I'm in Power Armor. Can these be safely disabled?

You can use the Power Armor HUD Switcher holotape to disable them. Do not disable them while you're in Power Armor. I repeat: DO NOT disable them while you're in Power Armor.

[[Top]](#table-of-contents)

---

### Why is there a crosshair on my Pip-Boy?

A small side effect of the Power Armor HUD overlays. You can turn the Power Armor HUD Switcher holotape setting for `Hide Hud in Pipboy` to `Off` in order to hide the crosshair when not in Power Armor, but this also makes the Pip-Boy look pretty terrible when using it inside Power Armor. Your call.

[[Top]](#table-of-contents)

---

### Can I have multiple companions at the same time?

[Heather Casdin](https://www.nexusmods.com/fallout4/mods/23273) doesn't occupy a "follower" slot, so you can have Heather + one other companion. You cannot have multiple vanilla companions with you at the same time.

[[Top]](#table-of-contents)

---

### I don't like the flashlight.

I don't care. I do.

[[Top]](#table-of-contents)

---

### Can I add an ENB?

If you hate yourself, sure. Some people have added ENBs and reported consistent crashes, so your mileage may vary. Don't add an ENB and report bugs to me because I can't/won't help. This will void official support.

[[Top]](#table-of-contents)

---

### Can I add character presets?

If you ask about adding presets in my support channel, I'm going to give you the Rule 11 role. Why? Because 1. you're adding stuff, and 2. a lot of presets have other required mods in order to work. It's a slippery slope, and I'm extremely unwilling to deal with it. Plus, frankly, adding presets is the easiest thing in the world, so if you're asking how to do it, you obviously haven't bothered trying to do anything for yourself, and I'm not here to hold your hand.

[[Top]](#table-of-contents)

---

### Can I update <...> mod?

You can do whatever you want, but this will void any official support.

[[Top]](#table-of-contents)

---

### What if I want to change/add/remove mods? Can you help me?

Sometimes I [write guides on how to do these things](https://github.com/LivelyDismay/Learn-To-Mod/wiki). Please don't ask me "can I add" or "is it safe to add" or "is there a list of mods I can add" or "can I suggest this mod" because I don't want to make YOUR list. I want to make MY list. I'm happy to answer any *technical* questions you have. This will void official support.

[[Top]](#table-of-contents)

---

### Does Magnum Opus have Ultrawide Support?

No. I don't own an Ultrawide monitor. Some of the other people playing this list do, and one of them [wrote this guide](https://docs.google.com/document/d/1EbZ_DpyhctsrpBlylDYc2TXtm1NAOjkcYjRCNZsC958/edit) for their own Ultrawide setup. I make no guarantees on how accurate or up-to-date this information is, and I cannot help you troubleshoot any issues that arise from using an Ultrawide. This will not void official support, but I do expect you to learn how to utilize your own hardware. I can't do it for you.

[[Top]](#table-of-contents)

---

### I'm having problems downloading files, how do I fix it?

The most common files that fail to download through Wabbajack are as follows:
- [More Hairstyles - Beards](http://www.mediafire.com/file/iztz7iidy6djz1e/MoreHairstyles-Beards.rar/file)
- [Misc Hairstyles 1.6](http://www.mediafire.com/file/kfac38dni6d53rp/MiscHairstyle1.6_by_Atherisz.7z/file)

Download these files manually, paste them into your `downloads` folder that you specified for Wabbajack, then rerun the installation.

If you're getting a lot of "unable to download" errors in Wabbajack, then log out of Nexus within Wabbajack, then log back in. Once you've done that, try downloading again.

[[Top]](#table-of-contents)

---

### How do I change my FOV?

While in game, press Escape, select `Mod Config`, then head down to `Custom Camera`. **Save any changes you make in this MCM to its own Profile or the changes will not stick.**

Do note that increasing your FOV also increases the amount of objects being rendered on screen at once, which could potentially result in a drop in performance.

[[Top]](#table-of-contents)

---

### Is the BiRaitBec Texture Optimization step required?

Technically, no. But you should still do it.

[[Top]](#table-of-contents)

---

### But I want to use Cheat Terminal?

That's a shame. It'll break a lot of stuff in this list. Besides, half of what that mod does is already in Opus, like making various outfits and whatnot craftable. Use the console if you want to cheat, or press F11 to access the ESP Explorer. Don't blindly add stupid shit to the modlist.

[[Top]](#table-of-contents)

---

### Pressing F11 crashes my game though!

If ESP Explorer crashes when you push the hotkey (F11), check your ESPExplorer.ini in "%USERPROFILE%\Documents\My Games\Fallout4\F4SE". If there is anything else on the line "HotKey=..." besides something like 0x79 or 0x7A, remove it.

Good:
(start of line)`HotKey=0x79`(end of line)

Bad:
(start of line)`HotKey=0x79 ; 0x79 = F10`(end of line)

[[Top]](#table-of-contents)

---

### Hey Lively, is there a reason ... ?

No matter how this question ends, the answer is the same: Because I want to, or because I didn't want to.

[[Top]](#table-of-contents)

---

### Can I buy you a drink?

[Yep.](https://www.patreon.com/nicholasjae)

[[Top]](#table-of-contents)
