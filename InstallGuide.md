## INSTALLATION GUIDE

* Create a new folder for the full setup. You can name it anything you prefer.

* Install Morrowind GOTY.

* Delete all the files inside "Morrowind\Data Files\Splash", make a backup of them if you want to.

* Install OpenMW 0.51, this one seems to work fine with my list and should also help with performance gains - 
      https://www.nexusmods.com/morrowind/mods/58699?tab=files&file_id=1000062789

* Run the game through OpenMW once to generate necessary files.

* Download and overwrite these files into the OpenMW folder -

      Enhanced Water for OpenMW 0.49-0.51 (install instructions inside the downloaded archive)- https://www.nexusmods.com/morrowind/mods/53667?tab=files&file_id=1000063189

      Debanded or Disabled Fog for OpenMW 0.48 and 0.49 (install instructions inside the downloaded archive) - https://www.nexusmods.com/morrowind/mods/53667?tab=files&file_id=1000055259
	(Use disabled fog)

      Wareya’s PBR for OpenMW 0.51 (extract all its content inside "OpenMW 0.51.0\resources") -
      https://codeload.github.com/wareya/OpenMW-PBR/zip/refs/heads/0.51
      (Link to the github page - https://github.com/wareya/OpenMW-PBR/tree/0.51)


* Head over to “OpenMW 0.51.0\resources\shaders\lib\light”,
and open the newly copied file “lighting_pbr.glsl” with a text editor and change the value next to 
“#define PBR_IM_USING_BROKEN_AO_MAPS_PLS_TRASH_THEM_KTHX” from 0 to 1. 

* Create folders to use as download and install directories.

* Install modlist from Wabbajack.

* If Mod Organizer 2 doesn't automatically detect your OpenMW installation then go to Modify Executables (In the top-right dropdown) and add both openmw.exe and openmw-launcher.exe from within your installed OpenMW folders.

* DO NOT activate any additional mods/plugins, leave everything as it is after installing through wabbajack.

* Download and copy my [shaders.yaml](https://www.nexusmods.com/morrowind/mods/58569?tab=files) to "Users\Admin\Documents\My Games\OpenMW" and replace the existing one.

* To disable enemy health bars since the mod Dynamic Reticle already covers it:

      1. Find “mods\Simple HUD for OpenMW\mygui\openmw_hud.layout".
      2. Open the file with a text editor
      3. Find an element with a name EnemyHealth (name="EnemyHealth")
      4. In the "position" property of that element - 3rd number is this element's length - set it to 0 to hide the element
      e.g you might find an element that looks like this
      <Widget type="ProgressBar" skin="MW_EnergyBar_Yellow" position="0 131 80 12" align="Center Bottom" name="EnemyHealth">
          <Property key="Visible" value="false"/>
      </Widget>

      inside position = "..." change 80 to 0. Save the file.

* In the OpenMW launcher Data Files > Navigation Mesh Cache, click on Update. This will reduce stutter and loading times while playing.

* You can now finally actually play the game! However it is important you read the following instructions to have a smooth experience and avoid encountering already addressed issues. Please make sure your problem is not listed below before reporting any further issues.


 ---

* If the openmw.exe does not open directly try opening the openmwlauncher.exe.

* Error message saying openmw has frozen is nothing to worry about, this is common when using big modlists. Everything should load up properly within a minute or two.

* If Wareya's PBR shader hasn't been installed properly, PBR textures will result in a green/blue glow.

* Even though all the Tamriel Data races are available to choose from during character creation, it’s best to stick to the vanilla races from the base game if you want to minimize the chances of your playthrough bugging out. The new races haven’t been tested enough and are likely to run into issues sooner or later.

* If you get a giant transparent box on the left side of the screen when you first start -
      open the Options menu while ingame > go to the scripts tab > select Buff Timers and click on the box next to Show Buff Borders to disable it. Once you create a character re-enable it later to adjust the box's location to your liking.

* The SSGI shaders can be a bit performance heavy so disable them in shader settings if needed, pressing F2 while in-game will bring up the post processing menu.

* If you are seeing red textures ingame inplace of dark/black areas then go to the post processing menu again and disable both Multi-LUT_performance and Multi-LUT_interior_performance.

* If you encounter a green screen bug then refer to this - 
      go in-game and press F2 to bring up the post-processing HUD, then disable/enable Flip-V for Multi-LUT and Multi-LUT-interior.
    
* Important texture replacers and replacers with plugins have been separated and placed under Misc Textures, now you can safely disable all the mods under the TexturePacks category to get some performance gain if needed.
  
---

* Press X while viewing a book to start playing its Audiobook.

* Press N to Undress or dress back up instantly.

* Press X to bring up the OpenMW Quest Menu.

* Press V to equip a Light sources you have.
  
*Check the Scripts tab after you create a character to enable/disable or set key bindings for mods according to your liking, notably the following* -
-  RUN :  
            set key binding  
            Maximum speed buff - 2000
   
-  Harder Better Faster Stronger :  
            Base Percent Diffculty Presets - Normal
   
-  Animated Levitation :  
            SFX volume - 30
   
-  Attend me :  
            enable hud - no (its hud feels immersion breaking at times, keep it enabled if it doesn't bother you. It also teleports your followers so don't disable it altogether just keep the hud hidden)
   
-  Buff timers :  
            adjust hud to your liking and then disable the borders once you're done
   
-  Friendly Autosave :  
            adjust to your liking
   
-  Daedra use bound equipment :  
            (I'd set chance of removing weapons to 80%)
   
-  Sun's Dusk :  
            configure according to your liking, check their modpage for more information
   
-  N'Garde :  
            set keybinding  
   			Glancing blows (choose as you wish)
   
-  OpenMW Quest Menu :  
  			set keybinding (since its default binding X conflicts with Audiobook play button you might want to change this)
   
-  Gothic Style Knockout :  
            if you notice npcs dying instead of getting knocked out when reaching 0 HP just try resetting or disabling and enabling the mod again
   
-  Devilish Dress Undress Hotkey :  
			set keybinding
   
-  Protection from Sun Damage :  
  			Require Closed Helmet - no
   
-  QuickSelectUltimate :
		    Hotbar Visibility mode - Never (if you don't want them showing on your screen), choose as you wish
  ---
	
