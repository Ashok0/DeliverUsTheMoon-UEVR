## Deliver Us The Moon UEVR Plugin
Deliver Us The Moon is a third person adventure puzzle game which has a first person camera for select narrative sequences only.  This VR mod enables the game's native first person mode for the full campaign and also adds additional VR features including seperately tracked left and right hands.  The Astrotool PDA is now an in-game tool you can interact with directly from your left arm.

## Install
Make sure that you are using the very latest NIGHTLY version of UEVR from: https://github.com/praydog/UEVR-nightly/releases/latest/

Delete any previous UEVR profiles for this game.

1. Get the latest release zip and click "Import Config" in UEVR, then browse to the zip and click it.
2. For hiding the cursor, copy the optional PAK file to: C:\Program Files (x86)\Steam\steamapps\common\Deliver Us The Moon\MoonMan\Content\Paks
3. By default, the Astrotool PDA is attached to your left arm.  If you wish to use the Astrotool PDA with a fixed camera, open MoonMan.lua and set line 6 to: *local FLOATING_HANDS = false*

## Features
* First person support for full campaign.
* Environment viewed through astronaut visor.
* 6DOF motion controls with floating hands.
* The Astrotool PDA can be viewed on your left arm and the flashlight is attached to your right hand.
* Roomscale movement.
* UI hidden for improved VR immersion.
* Camera fixes for puzzles, menus, cutscenes, Zero-G, and ASE robot control.
* Third person camera for cutscenes and climbing.
* Hold LT to activate cursor for solving puzzles.

## VR Controls
* **LT**: Sprint / Show Cursor
* **LB**: Zero-G Roll Left
* **RT**: Zoom / Fire / Scan
* **RB**: Zero-G Roll Right
* **LS**: Move
* **LS (Dn)**: Sprint
* **RS**: Camera
* **RS (Dn)**: Flashlight
* **System**: Pause Menu
* **System (Hold 1s)**: Activate Astrotool
* **LS + Dpad (Right Thumbrest)**: Navigate Astrotool
* **X**: Interact
* **Y**: Control ASE
* **A**: Jump / Zero-G Move Up
* **B**: Exit / Zero-G Move Down

## Known Issues
* If you have issues with the cursor being offset from the world space, recalibrate your height in the UEVR overlay and it should work properly.
* Astrotool D-Pad controls are rotated.  UP/DOWN navigates left and right and LEFT/RIGHT navigates up and down the PDA menu. 

## Credits
Special thanks to Praydog and Jbusfield for their support while developing this VR mod!
