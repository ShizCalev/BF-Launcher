v1.1.1 
------
- Added support for Mass Effect 3, Titanfall 2, and Star Wars Battlefront

v1.1.0 
------
- Added support for all versions of BF 1 & 4 titles. (Standard, Deluxe, Premium, etc.)
- Arguments are no longer case sensitive.

Description
-----------
- Launcher for Origin games that don't like loading directly through Steam. More games can be added at request.

- Intended to be added to Steam as a Non-Steam game.

- Supports Steam overlay, Steam big picture, and streaming.

- Will automatically open and close Origin before opening and after exiting your desired game.

Instructions
------------

1. Extract Origin-Launcher.zip

2. Place Origin-Launcher.exe where ever you'd like to keep it

3. Add Origin-Launcher.exe as a Non-Steam game on Steam

4. Right-click the shortcut in your Steam library and click Properties

5. Rename from "Origin-Launcher" to "Battlefield 1" or "Battlefield 4", ect.

6. Under Target add one of the following arguments seperated by a space:
	```
	For Battlefield 1 - Ultimate Edition: BF1-U
	For Battlefield 1 - Deluxe Edition: BF1-D
	For Battlefield 1 - Standard Edition: BF1-S

	For Battlefield 4 - Premium Edition: BF4-P
	For Battlefield 4 - Deluxe Edition: BF4-D
	For Battlefield 4 - Standard Edition: BF4-S
	
	For Mass Effect 3: ME3
	For Star Wars Battlefront - Ultimate Edition: SWBF1-U
	For Titanfall 2: TF2
	
	Example: "G:\OriginLibrary\Origin-Launcher.exe" bf1-u
	```
7. All Done. Launching the shortcut will launch the respective Origin game.

An example image can be found here; https://i.imgur.com/6pkh5d0.png

Other Notes
-----------
If you happen to have Origin installed somewhere other than the default Programs folder, 
you will need to add the path of Origin.exe as a second argument.

Example:
`"G:\OriginLibrary\Origin-Launcher.exe" bf1-u G:\Origin\Origin.exe`

Troubleshooting
-----------
If the game crashes on load, right click the game within the origin window, go to game properties, and uncheck the "Enable Origin In Game for *" checkbox.