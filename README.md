# RZ
Paper Mario Practice ROM<br/>

Star Rod 0.5.2 - https://drive.google.com/file/d/1jBuJD0BeuR1gyWi5E15wqzR7rCrJOPPv/<br/>
Star Rod Patcher - https://cdn.discordapp.com/attachments/455989477664620544/456888315371847681/StarRod_Patcher.zip<br/>
decomp repo: https://github.com/ethteck/papermario<br/>
star-rod-c repo: https://github.com/nanaian/star-rod-c<br/>

To use these assets to create the modded ROM, you'll need to provide an original, unmodified `Paper Mario.z64` ROM
<br/>
First of all, start by cloning the repo into a directory of your choice. This will be what is referred to as your `mod directory`
<br/>
Then create another folder to copy your original ROM to, this is where your `dump` folder will be
<br/>
<br/>
Once you have this set up, you can then open star rod. It will ask you to create a new config, hit yes
<br/>
It will then ask you to select a directory for your mod, this being wherever you copied the RZ repo to
<br/>
After selecting the mod directory, it will then ask you to select an original `Paper Mario.z64` ROM
<br/>
Once it has validated the ROM, it will immediately take you into the `Mod Manager` tab for dump/compile options
<br/>
The options button between `Dump ROM assets` and `Copy Assets to Mod` are the dump options. I generally click it and check `Dump everything`
<br/>
Now hit `Dump ROM Assets` and wait for the tool to finish dumping. (After doing this restarting star rod will have a lot more options when you start the program from now on)
<br/>
Generally after `Dump ROM Assets` you hit `Copy Assets to Mod` but since you pulled the RZ repo you dont need to do this
<br/>
You are now ready to compile the mod, just hit `Compile Mod` to have star rod create your new ROM in the `out` folder in your mod directory
<br/>
Package Mod is only used for distributing patch files (it creates a diff from the original ROM vs your ROM) to others without distributing copyrighted assets
<br/>



Mod Manager - Where you set compile settings/dump settings for your ROM
<br/>
Level Editor - Create/edit area folders and the map contained in them(a UI for editing maptable.xml)
<br/>
Map Editor - For editing/create maps
<br/>
Image Editor - For creating icons to be used in your mod
<br/>
Sprite Editor - For editing sprites found in the game/creating new ones
<br/>
Themes - Allows you to set the color the star rod UI will be
