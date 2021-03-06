ck2\_ged for Crusader Kings II    

    Requires:         Crusader Kings II (version 2.6.3 through 2.8.3.2)   
                      Python (version 3.6)    
    Utility version:  2018.08.12
    Readme version:   2018.08.12    

----------------------------------------------------------------------
Description:

Converts a Crusader Kings II save file (.ck2) into a GEDCOM file
(.ged). This file can be interpreted by many different genealogy
software packages, providing the player a way to view the family
relations occuring within their game.

----------------------------------------------------------------------
Instructions:

Place copies of the following files into the same directory:
  - ck2\_ged.py
  - settings.py
  - gamedata.py
  - gedcomwriter.py
  - The .ck2 file you wish to convert

Open settings.py in your favorite text editor or word processor and make 
sure ck2\_install\_dir and mod\_dir are set to your CKII install directory 
and the directory where you install mods, respectively.  Set other 
options as you desire.

Run ck2\_ged.py, follow the prompts, and wait a moment. When finished,
you will find a .ged file with the same name as the .ck2 file in the
directory.

Report any problems to the Paradox Interactive Forums thread: 
https://forum.paradoxplaza.com/forum/index.php?threads/tool-script-to-export-family-trees-from-your-savefile.1037854/.  
I probably need you to upload your save and tell me what mods you are using.

----------------------------------------------------------------------
Credits:

- Leyic
- Shawn Moore
- Ruth Morrison
- Paradox Interactive / the Crusader Kings II team
- Everyone who developed GEDCOM

----------------------------------------------------------------------
Permissions:

So long as you give credit where credit is due, you are free to use,
redistribute, and modify this mod however you wish. I'd appreciate it
if you'd let me know of any changes you make and release, however.

----------------------------------------------------------------------
History:

After this, the script was moved to github.

2018.08.12 - (jocago) Forked on github. Altered print statements to work with py3. Altered each python file to conform 
better with python norms. Also updated the settings file to accept a save_file parameter. Finally, set the unicode mode
based on the ck2 files (not sure if this is a macos or a py3 requirement).

2017.07.31 - Rewrote parser.  Updated to work with CK2 2.6.3 and 2.7.1.  Fixed some bugs.  Added primary titles and 
years of rule feature.

2013.03.26: -Updated code to work with newer updates of CKII. Changed behavior
of arrays that pulled info from dynastiesi.txt since they were being overwritten by information from the save file. 
Added code to proceed if a character has a single parent but not both.

2012.02.18: -.csv output for dynasties, characters, and families.
            -Minor changes.
2012.02.16: -Initial release.
