## Magnum Opus Frequently Asked Questions

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

---

### My characters have black/brown/tan/bugged faces. What happened?

First, ensure you do NOT have the High Definition DLC active in Steam. If you don't, then quite frankly, the so-called "Black Face Bug" can happen randomly. Saving and reloading should fix it. You can also use the console to disable then enable the NPC with the bug.

---

### Some people have weird black spots on their body, why don't you fix it?

This is a CBBE issue with some outfits and quite frankly, I can look past it. I'm not super adept with bodyslide and outfit studio, so...it is what it is. If you fix it, feel free to pop it on Nexus and I'll add it to the modlist.

---

### Controller support?!?

Nah, I don't use a controller. If someone else wants to set up a controller config, I can add it as an optional file.

If using a controller with Magnum Opus v7, you may find the map doesn't work. If you experience that, go into the MCM menu for Baka Fullscreen and check "Use Pip-Boy Color From Settings".

---

### VAFS no work, plz fix

VATS needs to be unbound or bound to a different key. I thought this would transfer over from my own custom control map, but apparently I was mistaken. You can do this in your vanilla keybinds menu under Settings, and the VAFS MCM.

---

### I can't build anything / how do I increase settlement size?

If you can't build anything in Workshop mode, odds are you're at the Build Limit (that bar in the top right). To increase your build limit, approach a workshop and press Space, then Configure Build Limit.

Increasing this too much can harm performance. Use at your own risk.

---

### I broke Workshop Plus and now I can't fly. What happened?

DO NOT enter Workshop Mode with a jetpack equipped. This will permanently break that jetpack's functionality.

---

### I am having random crashes. What do I do?

First, please make sure the crashes are repeatable. There is very little I can do for one-off crashes. Chalk those up to "shit happens."

One possibility is that your grenades got corrupted. I don't know how or why this happens, but it is possible. Unequip your grenades. If the crashes stop happening, toss that stack of grenades in the trash. Otherwise, keep reading.

Buffout 4 generates crashlogs for you in the `\Documents\My Games\Fallout4\F4SE` folder. These are vital to diagnosing the problem.

If your crashlog references `nvwgf2umx.dll` a bunch of times, that's an Nvidia Driver crash. Downgrading to pre-445 drivers will fix this. 442.74 versions seem preferable. [Here's a link for you](https://github.com/keylase/nvidia-patch/tree/master/win).

If your crashlog references `BGSSaveLoadManager` frequently, or `usvs::hook_DeleteFile`, or both, you are most likely running BitDefender. [Here's a link to help with that](https://www.bitdefender.com/consumer/support/answer/28557/).

If your crashlog references `PipboyMapData`, unequip your grenades. Sometimes (I have no idea why/how), a stack of grenades can become somehow corrupted. Throw those grenades in the trash. Don't use them. Spawn yourself new ones if you want. If anyone ever finds a reason that this happens, I'd love to know about it.

If your crashlog references an `xAudio dll` file, I have no idea how to fix this. I don't think anyone knows how to fix this. If you ever find a solution, I'd love to know about it.

Barring those reasons, there are still a plethora of other possibilities. [Auto Scanner](https://www.nexusmods.com/fallout4/mods/56255) can catch a ton of these. It is recommended you run your crashlog through this script (it's easy, you copy and paste the file, double click a thing, and press a button - no special knowledge required) and check the results. There is also a handy dandy `HOW TO READ CRASH LOGS.pdf` file you can reference.

If you've been unable to diagnose your issue after all that, feel free to upload your crashlog to me on [Discord](https://discord.gg/yABEjwB). Maybe I can figure something out.

---

### I randomly have god mode / I take no damage or rads / my stamina doesn't drain anymore. What happened?

Workshop Plus didn't uninitialize, apparently. Enter and exit workshop mode, that should fix it. Try not to open your Pipboy for a few seconds after exiting workshop mode.

---

### How do I cap/uncap my FPS?

In Mod Organizer, find the `High FPS Physics Fix` mod. Double click it. In the pop-up window, select the `INI Files` tab, then select the only INI listed. In the right pane, scroll down about halfway until you see `InGameFPS=`. Change the number to your liking.

---

### How do I edit the volumes for things like radios and voices?

While in game, press Escape, then select `Mod Config`. Scroll down to the section entitled `Persistent Volume Sliders`. Adjust to your liking.

Audio sliders for True Storms are in the vanilla Audio settings.

---

### I hate the HUD overlays while I'm in Power Armor. Can these be safely disabled?

You can use the Power Armor HUD Switcher holotape to disable them. Do not disable them while you're in Power Armor. I repeat: DO NOT disable them while you're in Power Armor.

---

### Why is there a crosshair on my Pip-Boy?

A small side effect of the Power Armor HUD overlays. You can turn the Power Armor HUD Switcher holotape setting for `Hide Hud in Pipboy` to `Off` in order to hide the crosshair when not in Power Armor, but this also makes the Pip-Boy look pretty terrible when using it inside Power Armor. Your call.

---

### Can I have multiple companions at the same time?

[Heather Casdin](https://www.nexusmods.com/fallout4/mods/23273) doesn't occupy a "follower" slot, so you can have Heather + one other companion. You cannot have multiple vanilla companions with you at the same time.

---

### I don't like the flashlight.

I don't care. I do.

---

### Can I add an ENB?

If you hate yourself, sure. Some people have added ENBs and reported consistent crashes, so your mileage may vary. Don't add an ENB and report bugs to me because I can't/won't help. This will void official support.

---

### Can I update [x] mod?

You can do whatever you want, but this will void any official support.

---

### What if I want to change/add/remove mods? Can you help me?

Sometimes I [write guides on how to do these things](https://github.com/LivelyDismay/Learn-To-Mod/wiki). Please don't ask me "can I add" or "is it safe to add" or "is there a list of mods I can add" or "can I suggest this mod" because I don't want to make YOUR list. I want to make MY list. I'm happy to answer any *technical* questions you have. This will void official support.

---

### Does Magnum Opus have Ultrawide Support?

No. I don't own an Ultrawide monitor. Some of the other people playing this list do, and one of them [wrote this guide](https://docs.google.com/document/d/1EbZ_DpyhctsrpBlylDYc2TXtm1NAOjkcYjRCNZsC958/edit) for their own Ultrawide setup. I make no guarantees on how accurate or up-to-date this information is, and I cannot help you troubleshoot any issues that arise from using an Ultrawide. This will not void official support, but I do expect you to learn how to utilize your own hardware. I can't do it for you.

---

### I'm having problems downloading a few files, how do I fix it?

The most common files that fail to download through Wabbajack are as follows:
  -  [More Hairstyles - Beards](http://www.mediafire.com/file/iztz7iidy6djz1e/MoreHairstyles-Beards.rar/file)
  -  [Misc Hairstyles 1.6](http://www.mediafire.com/file/kfac38dni6d53rp/MiscHairstyle1.6_by_Atherisz.7z/file)
  -  [FO4 Lodgen Resources](https://mega.nz/file/BZhlVCAJ#s-GqqbnJlZDvCLPiRw1Wm1EWGqMQCuh4CR8Zzn8POM4)

Download these files manually, paste them into your `downloads` folder that you specified for Wabbajack, then rerun the installation.

---

### How do I change my FOV?

While in game, press Escape, select `Mod Config`, then head down to `Custom Camera`. **Save any changes you make in this MCM to its own Profile or the changes will not stick.**

Do note that increasing your FOV also increases the amount of objects being rendered on screen at once, which could potentially result in a drop in performance.

---

### Is the BiRaitBec Texture Optimization step required?

Technically, no. But you should still do it.

---

### But I want to use Cheat Terminal?

That's a shame. It'll break a lot of stuff in this list. Besides, half of what that mod does is already in Opus, like making various outfits and whatnot craftable. Use the console if you want to cheat, or press F11 to access the ESP Explorer. Don't blindly add stupid shit to the modlist.

---

### Pressing F11 crashes my game though!

If ESP Explorer crashes when you push the hotkey (F11), check your ESPExplorer.ini in "%USERPROFILE%\Documents\My Games\Fallout4\F4SE". If there is anything else on the line "HotKey=..." besides something like 0x79 or 0x7A, remove it.

---

### Hey Lively, is there a reason --

No matter how this question ends, the answer is the same: Because I want to, or because I didn't want to.

---

### Can I buy you a drink?

[Yep.](https://www.patreon.com/nicholasjae)
