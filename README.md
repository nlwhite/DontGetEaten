# DontGetEaten
A mini text based adventure game

Goal - Find a way to escape the cell before the monsters return and eat you. 

Elements required:
 - User (Inventory, location)
 - Inventory (list of items)
 - Room Tiles (Inventory, location, description index)
 - Items (Name, description index)
 - Description/repsonse library (directory of descriptions/prompts/responses)

Actions:
 - Movement - Input w/a/s/d, check new tile, output description
 - Look - Check present tile, output description
 - Look at - Check item, output description
 - Take - Inupt take/grab/steal item, check item, output either 
 - Check Inventory - Input I/i/inventory, output list of inventory items
 - Throw
 - Kick/attack/poke
 
 
*Room Outline*  

+|A|B|C
-----|-----|-----|-----
**1** |Bones and rat | scratchings on wall | Dark Corner 
**2** |Half eaten sandwich | start | Cell Door 
**3** |Thin Blankets (note in pillowcase) | slightly creaky floor | Really creaky floor and gravel


