# Performance

## Resources

+ <https://sims.fandom.com/wiki/Game_guide:Multiple_ways_to_improve_The_Sims_3%27s_performance>
+ <http://simswiki.info/wiki.php?title=Game_Help:Improving_Sims_3_Performance>
+ <https://www.nraas.net/community/TIPS-FOR-BETTER-GAME-PERFORMANCE>
+ <https://www.neoseeker.com/Articles/Games/Guides/sims3performance/>

## Documents\Electronic Arts\The Sims 3\DCBackup

+ Delete everything EXCEPT ccmerged.package

## Documents\Electronic Arts\The Sims 3

+ Delete the following packages:
  + CasPartCache.package
  + compositorCache.package
  + scriptCache.package
  + simCompositorCache.package
  + socialCache.package
  + Script_Error.xml files
+ Delete any unused files from the folders:
  + Custom Music
  + Downloads
  + Exports
  + FeaturedItems
  + Screenshots

## Documents\Electronic Arts\The Sims 3\FeaturedItems

Steps to disable the automatic download of Featured Items files

1. Right-click FeaturedItems folder
2. Properties
3. Security
4. Select the User with which you play the game
5. Edit
6. New window should appear
7. Select the User with which you play the game again
8. Find the Write
9. Check the box for Deny
10. Okay
11. Read the Windows Security popup
12. Yes
13. Okay

## Program Files (x86)\Steam\steamapps\common\The Sims 3\Game\Bin

Open GraphicsRules.sgr with a text editor ( such as Notepad )

1. Find this:
   + seti cpuLevelUber  4
   + seti cpuLevelHigh  3
   + seti cpuLevelMedium 2
   + seti cpuLevelLow  1
2. Change to
   + seti cpuLevelUber  4
   + seti cpuLevelHigh  3
   + seti cpuLevelMedium 3
   + seti cpuLevelLow  3
3. Find this
   + seti cardLevelUber  5
   + seti cardLevelHigh    4
   + seti cardLevelMedium 3
   + seti cardLevelLowmedium 2
   + seti cardLevelLow  1
4. Change to
   + seti cardLevelUber   5
   + seti cardLevelHigh   4
   + seti cardLevelMedium 3
   + seti cardLevelLowmedium 3
   + seti cardLevelLow  3
5. Save the file

## In-Game Options

+ Graphics Tab
  + Lowest setting for all
+ Enable Object Hiding
  + Fullscreen = less frames per second = slower
+ General Settings Tab
  + Disable these if you don't need / use them:
    + Shop Mode
    + Lessons
    + Memories
    + Usage Sharing
    + Interactive Loading Screens

## Disabling the Launcher

1. Go to C:\Program Files (x86)\Steam\steamapps\common\The Sims 3\Game\Bin
2. Rename the Sims3Launcher.exe to Sims3LauncherOld.exe ( or anything you want )
3. Rename TS3.exe to Sims3Launcher.exe

## NRaas Mods

+ <https://www.nraas.net/community/Mods-List>
+ Purpose
  + Resetting sims, towns, objects, etc.
  + Catching errors, resolving them
  + Cleaning up broken objects, finding missing sims, etc.
+ MasterController
+ Overwatch
+ Error Trap

## How to get Mods

<https://modthesims.info/wiki.php?title=Game_Help:Installing_Sims_3_Package_Files/Setup_and_Files>

1. Download the framework
2. Extract
3. Move the Mods Folder to Documents\Electronic Arts\The Sims 3
4. Move your mod packages to Packages folder
5. Start game
6. Mod Scripts Found DIALOG
7. Packages loaded
8. Start save file

## Combine all your custom content packages with S3PE

Opens one file instead of multiple = runs faster with the same amount of space taken up

1. Download your custom content + mods
2. Extract it into .package files
3. Download: <https://sourceforge.net/projects/sims3tools/>
4. Install S3PE
5. Run S3PE
6. File >> New  OR CTRL + N
7. Resource >> Import >> From Package
8. Select your packages
9. Open
10. Import
11. No
12. Select File >> Save As
13. Name your file
14. Wait for S3PE to combine it all
15. Move the new file to the mods or custom content folder

## Other General Actions

+ Not running any other applications in the background as you play
+ Loading a different save game or creating a new game
  + DON'T: Switch in main menu
  + DO: Quit the entire game completely and reload the game
  + This prevents file corruption, bloating, and other detrimental errors
+ Don't have too many role giving objects on a single lot
  + Cash Registers
  + Barista Bars
+ Don't overload your Sim's inventory with a lot of items
+ World Adventures DLC
  + Use Chests to store your items
  + Chests can save the items when moved into the Family Inventory
