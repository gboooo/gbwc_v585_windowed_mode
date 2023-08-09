# Windowed Mode for Gunbound WC v585
![shortcut](/Untitled2.png "shortcut")

## Installation for GunboundR(gunbound.ca)
1. Extract ddraw.dll and windowed.ini to the install directory.
2. Set desired resolution in "windowed.ini".

## Installation for GitzWC(gitzwc.com)
1. Extract ddraw.dll and windowed.ini to the install directory.
2. Enable windowed mode in launcher options.
3. Delete these files (or move to a different location):
```
 	dxwnd.dll
 	GitzWindowMode.dll
	wndmode.ini
```
4. Set desired resolution in "windowed.ini".
![shortcut](/Untitled.png "shortcut")
5. Create a shortcut for the launcher. Always launch the game from this shortcut
instead of the updater since it will replace our ddraw.dll with dxwnd.

## Usage
ALT+ENTER toggles fullscreen.
Click then drag anywhere within the top ~16 px of the window to reposition
in borderless windowed mode.
The game window will automatically snap to the edges of the screen
while repositioning. To prevent this from happening, hold SHIFT while
dragging the window.
