## Performance Optimizations

> ### If you are experiencing performance issues, try the following steps

- Install [Rubic0n - OpenMW Lua Go Vroom](https://www.nexusmods.com/morrowind/mods/58557) —  
installation is simple just copy over the files located in `sandboxed\extract into your OpenMW install` to inside your OpenMW install folder and choose to overwrite.

- An [Occlusion Culling fork of OpenMW](https://www.nexusmods.com/morrowind/mods/58699) (Free FPS for OpenMW) is available to download on Nexus but its based on a pre release version of OpenMW 0.51 so use it at your own risk.  
  - I'm not yet aware of any problems but its probable you would run into one or two.  
  - Its however almost guaranteed to give results and will help with FPS improvement.  
  - You will obviously have to follow the steps for setting up OpenMW from the InstallGuide again.  
  - *Use this fork with Rubic0n for the best performance results*.

- **Reduce view distance**  
  Alternatively you can use [Horiz0n](https://www.nexusmods.com/morrowind/mods/59668) which dynamically adjusts your view distance based on your performance.

- **Disable AA shaders** — press `F2` in-game to open the post-processing menu and disable both EdgeAA and SMAA.

- **Disable SSGI shaders** — press `F2` in-game to open the post-processing menu and turn them off.

- **Install Medium Quality Landscape Textures** — Install [Optimized SaintJ'S Landscape Remastered 2.0](https://www.nexusmods.com/morrowind/mods/58569?tab=files) from the Optional files.  
Keep it at the very bottom of the load order.  

- **Disable HarderBetterFasterStronger** — disable the plugin HBFS.esp

- **Reduce grass/groundcover** —  
You can reduce groundcover density by going to -  
`Tools → Tools Plugins → OpenmwPlayer → OpenmwPlayer → Settings.cfg → Groundcover`  
Adjust the values to your liking, reducing density and rendering distance should help.

- **Disable grass/groundcover**  
`Tools → Tools Plugins → OpenmwPlayer → OpenmwPlayer → Groundcover`  
All the active groundcover plugins are at around the top of the loadorder, disable as needed.  
If disabling any groundcover mod, also disable `groundcover.omwaddon` from the same *OpenmwPlayer → Groundcover list*  and `deleted_groundcover.omwaddon` in the plugin load order if they are included.

- **Reduce shadow distance and resolution**  
`Tools → Tools Plugins → OpenmwPlayer → OpenmwPlayer → Settings.cfg → Shadows`  
- `maximum shadow map distance` — try **4000**
- `shadow map resolution` — try **1024**

- **Disable normal maps**  
`Tools → Tools Plugins → OpenmwPlayer → OpenmwPlayer → Settings.cfg → Shaders`  
Disable both `auto use object normal maps` and `auto use terrain normal maps`.

- **Reduce resolution** and use [Lossless Scaling](https://store.steampowered.com/app/993090/Lossless_Scaling/) to upscale and generate frames, or simply upscale.

---
