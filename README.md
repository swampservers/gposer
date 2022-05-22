# GPoser
A Garry's Mod addon to control your character's body and hands using your webcam. A spiritual successor to [FlexPoser](https://www.flexposer.com/) which also permits control of the hands and body. (facial expression control isn't actually implemented yet, but it will be). It's also a replacement for the Kinect integration built into GMod -  **All you need is a webcam!**

![pose](https://i.gyazo.com/598809cab7885951c78442c0a37b1e96.png)

GPoser uses [MediaPipe](https://google.github.io/mediapipe/) to bring cutting edge AI into Garry's Mod.

# Installation

1. Switch your Garry's Mod to the x86-64 branch as described [here](https://swamp.sv/video/plugin-guide.html). Currently, only Windows is supported and you must run the game in 64 bit mode!

2. Download the two .dll files above (click on them, then click download).

3. Navigate to C:/Program Files (x86)/Steam/steamapps/common/GarrysMod (or whereever the game is installed) and place **opencv_world3410.dll** in this folder. There should be an "hl2.exe" in this folder already.

4. From that folder, navigate to garrysmod/lua, then create a folder called "bin" and place **gmcl_gposer_win64.dll** in that folder.

5. Join the server (it only works on [Swamp Cinema](https://swamp.sv/) currently) and in the shop, select the ✌GPoser tab to control it. Your webcam will start controlling your player once it loads. Look in the bathroom mirror or use thirdperson (F4). Other players will see you!

***

The addon is currently in a very alpha state, and is only released as a binary for now, which only works on [Swamp Cinema](https://swamp.sv/). I plan to release this with source code in the future (I can't right now because it's built out of the mediapipe repository, so I have to figure out how to split them, and the code needs to be cleaned up a lot).
