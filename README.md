figure out how to use it yourself lol

Okay, there is a couple of tips I can give.
- ALWAYS MAKE A BACKUP.
- Read the arguments list to figure out what is valid.
- Read the existing BattleActions.txt file in Data. That's what the program uses to write to your ROM.
- Format the data similarly. setNum uses an integer, all other numeric inputs are hex (iirc). Spacing is mandatory.
- You can create labels by putting Label = LabeName at the end of the line anywhere with any amount of spaces between. Use labels in your Jumps.
- Jumps can also jump for the nearest command (add minus sign - to scroll backwards, otherwise looks forwards.
