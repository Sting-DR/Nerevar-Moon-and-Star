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

* Total storage required is 95 GB, including 38 GB for downloads which you can delete later if you want.

* Install modlist from Wabbajack.

* If Mod Organizer 2 doesn't automatically detect your OpenMW installation then go to Modify Executables (In the top-right dropdown) and add both openmw.exe and openmw-launcher.exe from within your installed OpenMW folders.

* DO NOT activate any additional mods/plugins, leave everything as it is after installing through wabbajack.

* Copy my [shaders.yaml](https://github.com/Sting-DR/Nerevar-Moon-and-Star/blob/1ad984b23152ac317ee85a725295dc234927bc6a/shaders.yaml) to "Users\Admin\Documents\My Games\OpenMW" and replace the existing one.

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

* You can now finally actually play the game!

* Even though all the Tamriel Data races are available to choose from during character creation, it’s best to stick to the vanilla races from the base game if you want to minimize the chances of your playthrough bugging out. The new races haven’t been tested enough and are likely to run into issues sooner or later.

* If you get a giant transparent box on the left side of the screen when you first start -
      open the Options menu while ingame > go to the scripts tab > select Buff Timers and click on the box next to Show Buff Borders to disable it. Once you create a character re-enable it later to adjust the box's location to your liking. Or disable it entirely if you're not fond of it

* Check the Scripts tab after you create a character to enable/disable or set key bindings for mods according to your liking, notably the following -
      skill evolution : (only in Star profile)
            enable refund - yes
            enable MBSP - yes
      RUN :
            set key binding
            Maximum speed buff - 2000
      Harder Better Faster Stronger:
            Base Percent Diffculty Presets - Normal
      Dynamic Ambient Visual Effects:
            add smoke to candles - yes
            disable smoke for carriable candles - no
      Animated Levitation:
            SFX volume - 30
      Attend me:
            enable hud - no (its hud feels immersion breaking at times, keep it enabled if it doesn't bother you. It also teleports your followers so don't disable it altogether just keep the hud hidden)
      Buff timers:
            adjust hud to your liking and then disable the borders once you're done
      Friendly Autosave:
            adjust to your liking
      Daedra use bound equipment:
            (I'd set chance of removing weapons to 80%)
      Sun's Dusk: (only in Dusk profile)
            configure according to your liking, check their modpage for more information
      N'Garde:
            set keybinding 
      Gothic Style Knockout:
            if you notice npcs dying instead of getting knocked out when reaching 0 HP just try resetting or disabling and enabling the mod again
	    QuickSelectUltimate:
		        Hotbar Visibility mode - Never (if you don't want them showing on your screen), choose as you wish
	
