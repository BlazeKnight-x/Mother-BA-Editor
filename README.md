figure out how to use it yourself lol

Okay, there is a couple of tips I can give.
- ALWAYS MAKE A BACKUP. The program writes to 2 separate banks, and it can run out of space. The EVE Explosion cannot be edited - the pointer used by it is hard coded into the battle engine for whatever reason.
- Read the arguments list to figure out what is valid.
- Read the existing BattleActions.txt file in Data. That's what the program uses to write to your ROM.
- Format the data similarly. setNum uses an integer, all other numeric inputs are hex (iirc). Spacing is mandatory.
- You can create labels by putting Label = LabeName at the end of the line anywhere with any amount of spaces between. Use labels in your Jumps.
- Jumps can also jump for the nearest command (add minus sign - to scroll backwards, otherwise looks forwards.
