Fix blender 2.49b NIFscripts 2.5.9 Oblivion creature export crashes

- Replace collisonobject for creatures (flags=1)
- Add default NiTransformController+Interpolator to bones without IPO
- Disable skin partition
- Preserve NiTexturingProperty for glow materials
- Set collision layer via object property instead of global option

How to use; Locate Blender 2.49 scripts folder (e.g., Blender2.49\Bin\Blender\.blender\scripts\export\)

Backup original export_nif.py

Download modified version and overwrite.

Particles still don't work, iirc there was a civ4 script where it doess, might be an idea for a future update.

All credit to the Nifskope team, this is just a small patch for a very old tool for an even older gamee
