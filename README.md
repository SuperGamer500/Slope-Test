# Slope-Movement

Thank you for downloading this my assets. This series of assets will help make slope movment a lot easier.

Important Information (Read this part of this file)
1. Use the provided physics material 2D on every object that you want to use slopes. If you do not, there is a chance that objects will get caught on slopes. I would recommend setting the physics material as the default in Project Settings > Phyics2D > Default Material
2. Turn off Query Hit Triggers (Project Settings > Phyics2D) and Queries in Colliders (Project Settings > Phyics2D) to prevent slope raycasting to hit the current object and any trigger objects present
3. Make sure to set the player character's layer to one called "Player". If you don't do this, the script will not detect input from a keyboard or controller.
4. Create 2 objects for the slope and ground object or the script will not work. The slope check object determines when the obj will detect slopes, the length determines how long each ray will go downwards and its overall scale will determine if the object will use the slope information. IF the slope check is not overlapping with specified ground layers, slopes will not be calculated. 
5. I would recommend using tilemaps because it makes collision detection more smooth. Just make sure to link the tilemap collider to a composite collider and to set the geometry type to Outlines. 

Copyright Information
Dont worry about copyright for these assets. If you want to credit me you can copy/paste the text below.

"Slope-Movement" by SuperGamer500 https://www.youtube.com/channel/UCdIrqcHNYux_0OSNiFJHNZQ


    
    

