## Performance Optimizations

> ### If you are experiencing performance issues, try the following steps

- **Reduce view distance** in the OpenMW launcher settings.

- **Disable texture mods** — mods under the `TexturePacks` separator, especially the two Landscape Remastered mods, can cause heavy GPU load.

- **Disable SSGI shaders** — press `F2` in-game to open the post-processing menu and turn them off.

- **Disable grass/groundcover**
```
Tools → Tools Plugins → OpenmwPlayer → OpenmwPlayer → Groundcover
```
Scroll the list to see which groundcover plugins are active and disable as needed. If disabling any groundcover mod, also    disable both `groundcover.omwaddon` and `deleted_groundcover.omwaddon` in the plugin load order.

- **Reduce shadow distance and resolution**
```
Tools → Tools Plugins → OpenmwPlayer → OpenmwPlayer → Settings.cfg → Shadows
```
- `maximum shadow map distance` — try **4000**
- `shadow map resolution` — try **1024**

- **Disable normal maps**
```
Tools → Tools Plugins → OpenmwPlayer → OpenmwPlayer → Settings.cfg → Shaders
```
Disable both `auto use object normal maps` and `auto use terrain normal maps`.

- **Reduce resolution** and use [Lossless Scaling](https://store.steampowered.com/app/993090/Lossless_Scaling/) to upscale and generate frames, or simply upscale.

---
