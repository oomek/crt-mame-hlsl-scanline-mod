# CRT HLSL mod for Mame

Conventional scanlines make the image darker by multiplying the screen with black and white stripes. This mod works in a similar way to an overlay effect in Photoshop, so it does not darken the screen.

It's compatible with Mame 0.202 and above and is tuned for 1080p


## Files

There are 2 versions of the mod: Trinitron's aperture grille and a conventional CRT slot mask

## Installation

Copy all the files from the CRT-Trinitron, or CRT-Slot-Mask folder into the mame's root folder. This mod will overwrite the following files, so make sure you've made a backup:
- hlsl/scanline.fx
- ini/presets/vertical.ini
- ini/presets/horizont.ini

It is also required to rename/remove the following files as they are overwriting the changes made by the vertical.ini and horizont.ini files:
- ini/presets/arcade.ini
- ini/presets/raster.ini
