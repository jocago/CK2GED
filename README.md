ck2\_ged for Crusader Kings II    

    Requires:         Crusader Kings II    
                      Python (2.7)    
    Utility version:  2017.08.31    
    Readme version:   2017.08.01    

----------------------------------------------------------------------
Description:

Converts a Crusader Kings II save file (.ck2) into a GEDCOM file
(.ged). This file can be interpreted by many different genealogy
software packages, providing the player a way to view the family
relations occuring within their game.

Can also produce .csv files for dynasties, characters, and families.

----------------------------------------------------------------------
Instructions:

Place copies of the following files into the same directory:
  - ck2\_ged.py
  - The .ck2 file you wish to convert

Open the script in your favorite text editor or word processor and make 
sure ck2\_install\_dir and mod\_dir are set to your CKII install directory 
and the directory where you install mods, respectively.  Set other 
options as you desire.

Run the script, follow the prompts, and wait a moment. When finished,
you will find a .ged file with the same name as the .ck2 file in the
directory.

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

2017.07.31 - Rewrote parser.  Updated to work with CK2 2.6.3 and 2.7.1.  Fixed some bugs.  Added primary titles and years of rule feature.

2013.03.26: -Updated code to work with newer updates of CKII. Changed behavior
of arrays that pulled info from dynastiesi.txt since they were being overwritten by information from the save file. Added code to proceed if a character has a single parent but not both.

2012.02.18: -.csv output for dynasties, characters, and families.
            -Minor changes.
2012.02.16: -Initial release.
