## INSTALLATION GUIDE

* Create a new folder for the full setup. You can name it anything you prefer.

* Install Morrowind GOTY.

* Delete all the files inside "Morrowind\Data Files\Splash", make a backup of them if you want to.

* Install the latest version of OpenMW 0.51 from here - https://github.com/OpenMW/openmw/releases.

* Run the game through OpenMW once to generate necessary files.

* Download and overwrite these files into the OpenMW folder -

      Enhanced Water for OpenMW 0.49-0.51 (install instructions inside the downloaded archive) -
  	  https://www.nexusmods.com/morrowind/mods/53667?tab=files&file_id=1000063189

	  Debanded or Disabled Fog for OpenMW 0.48 and 0.49 (install instructions inside the downloaded archive) -  
  	  https://www.nexusmods.com/morrowind/mods/53667?tab=files&file_id=1000055259

  	  (Use disabled fog)

      Liam's Kitbashed PBR (copy the shaders folder from inside "0.51\Core PBR Shaders" to inside "OpenMW 0.51.0\resources"), if copied correctly it should ask to overwrite existing files, click yes -  
      https://www.nexusmods.com/morrowind/mods/59113?tab=files&file_id=1000064688
      
	  Liam's Rafael Water Edits (follow install instructions as given inside and overwrite existing files) -  
	  https://files.nexus-cdn.com/100/59113/Liam's Rafael Water Edits-59113-1-1779831917.zip?md5=jCkw6mxuMixP3rp0AG1OdQ&expires=1780011774&user_id=139364848
      (Page Link if the above direct link does not work - https://www.nexusmods.com/morrowind/mods/59113?tab=files)

	  Edited lighting PBR settings file to use with NEMAS (Paste it inside "OpenMW 0.51.0\resources\shaders\lib\light" and overwrite) -
   	  https://www.nexusmods.com/morrowind/mods/58569?tab=files

* Create folders to use as download and install directories.

* Install modlist from Wabbajack.

* If Mod Organizer 2 doesn't automatically detect your OpenMW installation then go to Modify Executables (In the top-right dropdown) and add openmw-launcher.exe (not openmw.exe) from within your installed OpenMW folders.

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

* Error message saying openmw has frozen is nothing to worry about, this is common when using big modlists. Everything should load up properly within a minute or two after launching oppenmw.

* You can now finally actually play the game! However it is important you read the following instructions to have a smooth experience and avoid encountering already addressed issues. Please make sure your problem is not listed below before reporting any further issues.


 ---

* If Wareya's PBR shader hasn't been installed properly, PBR textures will result in a green/blue glow.

* Even though all the Tamriel Data races are available to choose from during character creation, it’s best to stick to the vanilla races from the base game if you want to minimize the chances of your playthrough bugging out. The new races haven’t been tested enough and are likely to run into issues sooner or later.

* If you get a giant transparent box on the left side of the screen when you first start -
      open the Options menu while ingame > go to the scripts tab > select Buff Timers and click on the box next to Show Buff Borders to disable it. Once you create a character re-enable it later to adjust the box's location to your liking.

* To disable depth of field press F2 while ingame and disable fuzdof.
    
* If you are seeing red textures ingame inplace of dark/black areas then go to the post processing menu again and disable both Multi-LUT_performance and Multi-LUT_interior_performance.

* If you encounter a green screen bug then refer to this - 
      go in-game and press F2 to bring up the post-processing HUD, then disable/enable Flip-V for Multi-LUT and Multi-LUT-interior.

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
	
