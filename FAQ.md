## FAQ
- [OpenMW Crash / Not Launching / Shaders not working properly](#openmw-crash--not-launching--shaders-not-working-properly)
- [Automatically Disabled Plugins](#automatically-disabled-plugins)
- [New keybinds for added actions](#new-keybinds-for-added-actions)
- [Notable Gameplay and Balance Changes](#notable-gameplay-and-balance-changes)
- [Misaligned HUD / Transparent box on screen](#misaligned-hud--transparent-box-on-screen)
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
  Then manually disable all esps from right under the last esm (which should be Vvardenfell On Vellum.esm for now) to groundcover.omwaddon.esp
---

### New keybinds for added actions:  
| Key | Action | Mod |
|---|---|---|
| U | Toggle Photo Mode | Photo Mode for OpenMW |
| N | Undress or dress back up instantly, helpful for taking baths | Devilish Dress Undress Hotkey |
| V | Equip any Light sources you have | LightHotkey |
| Q | Toggle lock-on | Dynamic camera |
| C | Command followers depending on what you are looking at | Follower Commands |
| R | While hovering over an item in your inventory, equip/use it | Inventory Extender |
| K | While hovering over an item in your inventory, mark it as junk | Loot n Dump - Mark as Junk and Autosell Items |
| M | Bring up the Dynamic Map | Dynamic Map |
| Y | Bring up the Character Stats window | Character Panel |
| Z | Bring up the added new Journal | Questman - Modern Quest Journal |
| K | While hovering over an item in the inventory, mark it as junk (makes it easier to sell later) | Loot n Dump - Mark as Junk and Autosell Items |
| G | While focusing on an item (not owned by other NPCs), move it around | Perfect Placement |
| G | When facing a locked door, knock on it — if the owner is inside they will open it shortly | Devilish Knocking |
| Shift + 1/2/3 | Switch the active quick-select hotbar | QuickSelect Ultimate |
| Shift + F | Dispose of a body while looking at its inventory | Quickloot |
| Shift + R | Open the vanilla looting window while looking at a container | Quickloot |
| Shift + Space | Pick up a book instead of reading it (may break a few quest scripts) | Book Pickup |
| Hold R | Bring up spell wheel | Handy Stylish Quick Access Wheels |
| Hold F | Bring up weapon wheel | Handy Stylish Quick Access Wheels |
| X | While raising a weapon for attack, attempt a spellstrike — combine weapon and spell attacks together | Spellstrike |
| Left-Alt | Parry | N'Garde |
---

### Notable Gameplay and Balance Changes:
| Feature | Description | Mod / Source |
|---|---|---|
| Game Difficulty | Game Difficulty can be adjusted using the script settings in-game | Harder Better Faster Stronger (HBFS) |
| Survival Mechanics | Several immersive survival mechanics added to the game. All of them can be disabled or tweaked using the script settings if needed in Sun's Dusk: Primary Needs | Sun's Dusk |
| Death Consequences | Death has consequences, tho not permanent | Death Reflections |
| Faction Requirements | Faction Favored Skills and Attributes have been changed, check the mod-page to find the new joining requirements. | Better Faction Favored Skills and Attributes |
| Undead Damage | Damage to undead Creatures is affected by weapon type and is dictated by common sense (words of the author), check the mod-page for more information. | Logical Damage to the Undead |
| Summoned Creatures: Soul Trap | Summoned Creatures cannot be soul trapped | Friendlier Fire |
| Summoned Creatures: Obedience | Summoned Creatures may act disobedient depending on enemy level | Disobedient Summons |
| Hidden Traps | All traps are hidden initially, use related spells or try using a probe on a lock to have a chance of revealing the trap | Hidden Traps |
| Lock Breaking | All locks are breakable by hitting them if you have enough strength | Brute Force |
| NPC Behavior | Harsh weather will make wandering NPCs go to their homes / taverns or kind of disappear for the duration of the weather. | Lua NPC Schedule |
| Owned Books | NPCs no longer allow you to read owned books for free. Either befriend them (80 disposition), or sneak to read the book illegally | Shelf Control |
| Item Ownership | When an NPC dies or disappears, they lose ownership of all previously owned items | Dead Mer Tell No Tales |
| Night Curfew | Loitering around at night time in cities is prohibited, allowed only if you carry a light source with you | Night Patrol |
| Vampirism & Helmets | Wearing Helmets will hide your vampirism from all NPCs | Hiding Vampirism Under Helmets |
| Vampire Sun Protection | You can protect yourself from sun damage as a vampire by completely covering your body with clothing or armor | Protection From Sun Damage |
| Necromancy Prohibition | Necromancy is prohibited in most cities. | Sane Magic Overhaul |
| Daedra Summoning Damage | You take a portion of the damage dealt to each Daedra you summon. Higher Conjuration skill reduces this unblockable damage. | Sane Magic Overhaul |

---
### Misaligned HUD / Transparent box on screen:  

If you are playing with any resolution other than 1080p you'll likely come across some of the HUD elements spread out weirdly on your screen.  
They can be easily adjusted through messing with the following script settings -  
- HUD Weapon Charge (enable Better Bars compatibility)
- TimeHUD
- LocationHUD
- Buff Timers
- Ammo Count HUD
- Nearby Doors
- Sun's Dusk: UI (can be dragged around when the game is paused)
- Best Friends Forever: HUD (follower HUD that only appears when you have a companion in your party)

**Buff Timers** is also what causes the large transparent box on screen when starting a new game sometimes, toggle off the *Size and Positioning mode* in its script settings to remove that.

 ---
