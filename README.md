# football-squares
A python script for generating Superbowl Football (or basketball, any sport) game squares. It is suitable for any number of entries because it programatically scales / converts entries to a 10x10 grid and also allows for the empties after scaling to be assigned to a non-entrant.

Scaling: Game squares are assigned as the last number of a possible score (0-9) so the end result by definition has to be a 10x10 grid. It might not be possible to sell / assign 100 squares. This script scales for you. For example, let's say you sold / assigned 23 squares. The program automatically scales by a factor of 4 and assigns 4*23 = 92 squares. The 8 remaining are assigned to a non-player entity of your choosing.
 
Input: Accepts a csv file with a list of names and number of squares to assign to that person. No column headers should be used. File Name / Directory can be assigned.

Output: An excel file with with the names assigned. File Name / Directory can be assigned.

Libraries
random
datetime
time
pandas

## Current Release
Version 1.0

## Release 2 Possible Enhancements
api integration to consume game scores to automate winner selection.
