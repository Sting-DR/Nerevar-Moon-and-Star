## FAQ
- [OpenMW Crash / Not Launching / Shaders not working properly](#openmw-crash--not-launching--shaders-not-working-properly)
- [Automatically Disabled Plugins](#automatically-disabled-plugins)
- [New keybinds for added actions](#new-keybinds-for-added-actions)
- [Notable Gameplay and Balance Changes](#notable-gameplay-and-balance-changes)
- [Misaligned HUD](#misaligned-hud)
---

### OpenMW Crash / Not Launching / Shaders not working properly:  

* If OpenMW.exe refuses to launch through MO2 with any error mentioning antivirus preventing it,   
  Just restart MO2 and try launching it again.

* If your OpenMW.exe crashes on start with the text,   

  OpenMW: Fatal error
  failed initializing shader: objects   
  
  This almost always means you're on a wrong version of OpenMW, or something else went wrong with the OpenMW setup.   
  *Try re-downloading and re-installing the linked OpenMW and following the install guide to set it up again.*

* If Liam's Kitbashed PBR shader hasn't been installed properly, PBR textures will result in a **green/blue shine on most textures.**   
This is different from the cyan/green screen issue which is addressed below.

* If you encounter a **green/cyan screen bug** then you're probably *launching the game through the Openmw-launcher.exe instead of Openmw.exe*
  
* If you are seeing red textures ingame inplace of dark/black areas then go to the post processing menu again and disable both Multi-LUT_performance and Multi-LUT_interior_performance.

---
### Automatically Disabled Plugins

- When loading up your game if you happen to come across the issue of having multiple plugins disabled all you have to do is try 
  unchecking and checking back a random esp in the load order from mo2.  
    
  That should sync up your mo2 load order and openmw enabled esps again.

- If the plugins are somehow disabled in MO2 itself,  
  Right click on any plugin and select enable all.   
  Then manually disable all plugins from LefemmArmor.esp to groundcover.omwaddon.esp
---

### New keybinds for added actions:  

* Press **U** to Toggle Photo Mode  (*Photo Mode for OpenMW*)

* Press **N** to Undress or dress back up instantly (*Devilish Dress Undress Hotkey*)

* Press **V** to equip any Light sources you have (*LightHotkey*)

* Press **Q** to toggle lock-on (*Dynamic camera*)

* Press **C** to command followers depending on what you are looking at (*Follower Commands*)

* Press **R** while hovering over an item in your inventory to equip/use it (*Inventory Extender*)

* Press **Y** to bring up the Character Stats window (*Character Panel*)

* Press **Z** to bring up the added new Journal (*Questman - Modern Quest Journal*)

* Press **G** while focusing on an item (not owned by other npcs) to move it around (*Perfect Placement*)

* Press **G** when facing a locked door to knock on it, if the owner is inside they will open it shortly (*Devilish Knocking*)

* Press **Shift + F** to dispose of a body while looking at its inventory (*Quickloot*)
 
* Press **Shift + Space** to pick up a book instead of reading it, directly picking up instead of reading it first could break a few quest scripts (*Book Pickup*)

* Press **Left-Alt** to parry (*N'Garde*)
---

### Notable Gameplay and Balance Changes:

* **Game Difficulty** can be adjusted using the script settings in-game for *Harder Better Faster Stronger (HBFS)*

* **Sun's Dusk** adds several immersive survival mechanics to the game. All of them can be disabled or tweaked using the script settings if needed in *Sun's Dusk: Primary Needs*

* **Faction Favored Skills and Attributes** have been changed, check the mod-page for [Better Faction Favored Skills and Attributes](https://www.nexusmods.com/morrowind/mods/59168) to find the new joining requirements.

* All keys you pick up are automatically added to the **Keychain** in your inventory for easier management and usage.  
However if you come across any quest that relies on a specific key in your inventory that needs to be handed over or used by another character then you will have to open the Keychain and drag the required key to inside your inventory.

* **Damage to undead Creatures** is affected by **weapon type** and is dictated by common sense (words of the author), check the mod-page for [Logical Damage to the Undead](https://www.nexusmods.com/morrowind/mods/58722) for more information.

* Summoned Creatures cannot be soul trapped (*Friendlier Fire*)

* All **traps are hidden** initially, use related spells or try using a probe on a lock to have a chance of revealing the trap (*Hidden Traps*)   

* All **locks are breakable** by hitting them if you have enough strength (*Brute Force*)

* **Loitering around at night time in cities is prohibited**, allowed only if you carry a light source with you (Night Patrol)

* **Necromancy is prohibited** in most cities.

* You **take a portion of the damage dealt to each Daedra you summon**. Higher Conjuration skill reduces this unblockable damage.

* The **Open spell no longer automatically unlocks** doors or containers. Instead, it buffs your Security, but the mental strain drains your Fatigue. You need Security of at least 15 to understand how to exploit this.  

The three above settings can be toggled off/on through Sane Magic Overhaul's script settings in-game.

*To Customize further check the Scripts tab after you create a character to enable/disable or set key bindings for mods according to your liking*

---
### Misaligned HUD:  

If you are playing with any resolution other than 1080p you'll likely come across some of the HUD elements spread out weirdly on your screen.  
They can be easily adjusted through messing with the following script settings -  
- HUD Weapon Charge (enable Better Bars compatibility)
- TimeHUD
- LocationHUD
- BuffTimers for OpenMW
- Ammo Count HUD
- Nearby Doors (OpenMW)
- Sun's Dusk: UI (can be dragged around when the game is paused)
- Best Friends Forever: HUD (follower HUD that only appears when you have a companion in your party)

 ---
