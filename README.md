# bwh14
Automatically exported from code.google.com/p/bwh14


BWH 1.4b2 Crappy Readme
-----------------------
Another beta version, it's basically the first runnable version that came together for client 1.5. Keeping this short because this is still in development so maybe some things will change before I write the final readme.

Installation:
0. This will ONLY work if you are running in Direct3D mode. It's not going to do squat if your running in OpenGL and no there will never be support for it.
1. Run bwh_setup.exe
  1a. Ensure the path to your World of Warcraft executable is correct. (It's autodetected).
  1b. Click the 'Scan' button.
  1c. If enough pointers were found the 'Save' button should enable itself.
  1d. Double check the hotkey and font settings and adjust them to your preference.
  1e. Hit the 'Save' button to create a bwh.ini file.
2. Run World of Warcraft
3. Run bwh_loader.exe
  3a. Should see World of Warcraft listed in the list box.
  3b. Select either 'Injection' or 'Loader'
     3ba. Injection: You should normally run in this mode because it is less detectable.
     3bb. Loader: This is for debugging purposes, and can possibly be a tad more stable.
  3c. Hit the 'Install / Remove' button ONLY once.
4. Switch to the World of Warcraft window and see if the ShowHide hotkey pop's up the interface (default F12).

FAQ
---
Q. I use Windows (95/98/ME), will this be a problem?

A. Yes it will. Windows 9X sucks and you should upgrade to Windows 2000 or Windows XP. You will experience problems on Windows 9X systems, but you should still be able to use the hack... just very carefully =)

Q. This hack makes World of Warcraft crash; what can I do about it?

A. First you want to run bwh in "Loader" mode. When World of Warcraft crashes copy and paste that long ass crash dump that World of Warcraft spits out into a private message to me. You can reach me at http://rpg-exploiters.shoq.net/ under the username "bubba". Make sure the crash dump you send me was created when running in "Loader" mode or else the crash dump is useless to me. Also, go click crazy on the banners at http://rpg-exploiters.shoq.net/ will ya? =P

Q. The hack doesn't load and I get no errors; what can I do about it?

A. If you have pointer failures with bwh_setup.exe then pm me and we'll discuss them (unless Present or Reset fails; if this happens then update directx instead of pming me). If you have no pointer errors and you are running a NT based machine (Ex. Windows XP), try logging on as Administrator and trying again.

Q. I have some other question...

A. Go to http://rpg-exploiters.shoq.net/, find the bwh thread, and post a reply. Can also pm me if you want, np.


https://www.ownedcore.com/forums/world-of-warcraft/world-of-warcraft-bots-programs/15210-source-bwh-bubbas-hack-source-code.html
[Source] BWH Bubba's Hack Source Code
For compiling this beast you need Visual Studio .NET 2003 and the DirectX SDK December 2004 edition. You can probably compile in some other environment, but I can only guarantee that it will compile normally under that environment.

Use of the original program:

Track Pattern: If you enter some text in this textbox then any npc or pc name that contains that string will be shown on your minimap. So, if you type in "a", then any character with an "a" in their name will show up. This works regardless of what tracks you have enabled or disabled. This is added for when you need to find a certain character for a quest or something.

Speed Hacking: Speed hacking is controled with the S textbox and buttons and with the speed up/down hotkeys. You actually have 5 different speeds associated with your character...
Run speed: default is 7 and it changes when you have some run speed buff or debuff applied to your character.
Walk speed: default is 2.5 and it never changes.
Backward speed: default is 4.5 and it never changes.
Swim speed: default is 4.722222 and it changes when you have some swim speed buff or debuff applied to your character.
Backward swim speed: default is 4.5 and it never changes.
The speed displayed by the hack is your run speed. When you change your run speed, the hack also changes all of your other speeds. So, if you double your run speed then the hack will also double your walk speed. If the game changes your run or swim speed then hack will reset all other speeds to their default values. This is because if your run speed is "supposed" to be different that 7, then having adjusted values for the other speeds will make your character appear like hes running weird.
Note that the normal speed hotkey resets your run speed to 7 and all other speeds to their default values. If your on a mount, have aspect of the cheeta, or something like that normal speed will not set your speed to default mount/aspect/whatever speed. It will set it to 7 always.


Disable Hotkeys: Pretty simple. Checking this will disable all hotkeys except for the ShowHide hotkey. Hotkeys that are trapped by bwh are not sent along to WoW. So, use this if you have some conflicting hotkeys with WoW and don't feel like rerunning setup to fix it.

No Fall Damage: Check this and you will no longer take fall damage.

Mountain Climb: Check this and you will be able to climb really steep slopes.

Lock Speed: Check this and you WoW will be unable to change your speed in response to a speed buff or debuff. This includes stuff like getting on your mount, stealthing, etc...

Zero Gravity: Check this and you will no longer "fall". Note that you also cannot jump; this is on purpose because jumping while using this hack makes you go crazy for some reason.

Teleport to Plane: I still don't know really what this is. Some people requested it so there it is. Supposedly you can run around unseen with this on, but I am not sure if that's really what's happening. I don't use it so... whatever.

Follow NPC: This will allow you to follow npc's and enemy faction pc's around. It also takes out the distance requirement. As long as you can target what you want to follow, then you can follow it. To activate it, select the character you want to follow and type "/follow"


Please note that this hack was originally made for the version v1.7 client of wow.
Now with the source code developers can really start working on it again 

Enjoy :wave:
-=Tehavatar=-

Source.zip




-----)(Please leave the copyright text intact)(-----
This post is copyright by the user posting it and MMOwned.com - World of Warcraft Exploits,Hacks, Bots and Guides, where it was posted. You may not copy or reproduce this information on any other site without written permission from both the poster and MMOwned.com
