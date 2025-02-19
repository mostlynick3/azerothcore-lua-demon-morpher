<div align="center">
  <img src="https://raw.githubusercontent.com/mostlynick3/azerothcore-lua-demon-morpher/master/icon.png">
</div>

## AzerothCore Lua Demon Morpher Module

This module lets Warlocks kill demons and claim their models to apply on their own summoned demons.

Make your Felguard a Wrathguard, your Felhunter a Hellboar, and much, much more!

This module requires an item ID to open the morph menu. The Lua script will create the required character database table, item, and vendor for you, if you variables to do so are set to true. This means that for the inserts to be processed.

This isn't a finished product, it is missing some performance optimizations but works perfectly fine out of the box. 

### Steps:
1. Place script in your lua_scripts folder.
2. Reload Eluna.
3. If you are using the pre-made vendor and item, restart your server.
4. You may now use the module! Remember to add the vendor to world by doing ".npc add <vendor_id>" (e.g., ".npc add 190087" for the default vendor)

Morph selection menu:

![image](https://github.com/user-attachments/assets/73768023-368b-4049-a9ae-5343346f6dac)


Example item, created by script:

![image](https://github.com/user-attachments/assets/61c02426-9f1e-44dd-859b-31fa2ea288b4)


Example vendor, created by script:

![image](https://github.com/user-attachments/assets/f44f0865-d075-4676-83fd-663c598edaf5)

________________________________________
Name: AzerothCore Lua Demon Morpher

Author: mostlynick3

Repository: https://github.com/mostlynick3/azerothcore-lua-demon-morpher/

Download: https://github.com/mostlynick3/azerothcore-lua-demon-morpher/archive/refs/heads/main.zip

License: AGPL-3.0 license
