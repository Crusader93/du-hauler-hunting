Dual Universe Pirate Hauler Hunting script.

 I don't play DU anymore, so maybe this code will be useful to someone someday.

Connection:

1. Link programming board to the screen, databank and core unit.
2. Paste PB.json in programming board.
3. Copy and paste the folder "DUPIRATE" into the "custom" folder into the following game directory.

Controls:

1. G (gear) - export saved coordinates from the databank to the screen
2. B (booster) - enable/disable the current target position
3. Alt+G (antigravity) - enable/disable coordinate export mode (manual or auto by default)
4. Left alt + Left shift - marker to the center of the nearest pipe
5. Option-4 - Toggle between estimated target speed and maximum speed of 29999 km/h
6. Alt+ ← / Alt + → - move waypoint +- 10 su
7. Alt+ ↑ / Alt + ↓ - move waypoint +- 2.5 su
8. To clear the saved coordinates in memory, send the "n" command to the LUA chat
9. To get the ::pos at the desired calculated waypoint, use the "mar" command. For example, the "mar25" command will return to the LUA chat the calculated position 25 su ahead, and the "mar-25" will return position 25 su behind

Usage:

Switch to manual mode by pressing ALT+G , copy the targer pos 1, then send this pos to the lua chat, then copy pos 2 and send it to the lua chat.<br/> 
Move the waypoint along the entire length of the calculated target vector.<br/>
You can copy the current vector to share it with your friends by pressing G (gear) and then copy the vector data from the screen.

