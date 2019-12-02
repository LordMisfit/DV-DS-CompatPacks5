DV-DS-CompatPacks ["Aetherius" - Compatiblity Patches for Various mapsets]

- Includes compatiability patches and PK3 files for the following wads/etc. Though keep in mind some of these are currently incomplete.
	- "Doom Upstart Mapping Project: Episode 1" aka "DUMP" (loaded as a subfolder)
	- "Doom Upstart Mapping Project: Episode 2" aka "DUMP-2" (loaded as a PK3 file)
	- "Doom Upstart Mapping Project: Episode 3" aka "DUMP-3" (loaded as a subfolder)
	- Epic (loaded as a WAD file)
	- Epic 2 (loaded as a WAD file)


HOW TO INSTALL / RUN / ETC:

 - Important - Make absolutely sure you got DV-DS-ComboPack [@ https://github.com/LordMisfit/DV-DS-ComboPack ] working right before you do anything here. Refer to that repository's README.md file for more information.

 - Installing 1 - Make sure you unzip the entire "DV-DS-CompatPacks5" folder inside the zip file to your designated GZDoom folder. Do not try to install the subfolders within into "DV-DS-ComboPacks" or into your main GZDoom folder, or you've done flapped it up and have to do everything up to this point on both repositories over again. :V
 - TL;DR: So basically make sure "DV-DS-ComboPacks" & "DV-DS-CompatPacks5" are seperate subfolders in your main GZDoom folder. :P

 - Running - 1. There is no launcher packed for use with DV-DS-CompatPacks5, you'll have to rely on command lines for now. My general method is to create a batch [.bat] file and name it something you'll remember. Remember you can right click a .bat file and "edit" them to change the command line used inside.

 - Running - 2. To run DUMP-1 w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-Compatpacks5/DUMP1" +hud_scale 0 exit"
 - Important: DUMP-1, DUMP-2's & DUMP-3's "remove everything on level start" feature is removed in these versions due to the mod's RPG nature, and resetting everything per level would destroy the mod's main function gameplay wise.

 - Running - 3. To run DUMP-2 w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-Compatpacks5/DUMP2-dvds.pk3" +hud_scale 0 exit" 
 - Important: DUMP-1, DUMP-2's & DUMP-3's "remove everything on level start" feature is removed in these versions due to the mod's RPG nature, and resetting everything per level would destroy the mod's main function gameplay wise.

 - Running - 4. To run DUMP-3 w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-Compatpacks5/DUMP3" +hud_scale 0 exit" 
 - Important: DUMP-1, DUMP-2's & DUMP-3's "remove everything on level start" feature is removed in these versions due to the mod's RPG nature, and resetting everything per level would destroy the mod's main function gameplay wise.

 - Running - 5. To run Epic [1] w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-Compatpacks5/Epic" +hud_scale 0 exit" 

 - Running - 6. To run Epic 2 w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-Compatpacks5/Epic2" +hud_scale 0 exit" 

 - ABOUT LegenDoomLite: Can be added to any mode [or game type or even normal Doom1/2] essentially by adding "DV-DS-CompatPacks/LegenDoomLite" into the command line as the last file loaded. This one does NOT have to be loaded as a seperate mod from the above and is basically compatible with any of them and thensome. :V

