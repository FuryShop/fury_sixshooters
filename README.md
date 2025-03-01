Fury Six shooters
Both models are build from scratch and fully animated.


Name of the weapon: WEAPON_FURYMINIREV
Name of the weapon: WEAPON_FURYSHORTREV
Version: 1.0.0
Creation date: 01-03-2025

These are 2 seperate resources add them both in youre server.cfg
ensure WEAPON_FURYMINIREV
ensure WEAPON_FURYSHORTREV

--Ox Inventory -> data -> weapons.lua
-- add


	['WEAPON_FURYSHORTREV'] = 	{ 
		label = 'Short 6 shooter', 		  
        	weight = 3400, 
        	durability = 0.1, 
        	ammoname = 'ammo-38' 
 	},
 
	['WEAPON_FURYMINIREV'] = { 
        	label = 'Subnosed 6 shooter', 		
       		 weight = 3400, 
        	durability = 0.1, 
        	ammoname = 'ammo-38' 
	},


Only tested on OX-INVENTORY
- No support for other inventories
- If you want to change the ammo type change the ammoname in one you have installed on youre server

Contact by discord: https://discord.gg/DXe7vZwN2A

If you want to use this in one of youre free scripts please make a attribution. Not allowed to use in any paid scripts
only non-commercial purposes.
