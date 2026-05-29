# Valid-Weapons-Spawner
Valid Weapons Spawner for STALKER GAMMA (And maybe anomaly)

By Verdatim

# MODDING TOOL!

Not really anything too fancy, just combs through the npc_loadouts.ltx file and spawns all valid guns onto the player, useful for some maybe.

Valid guns are considered valid if the gun can be found in a section that is mentioned at least once in a 'primary', 'secondary' or 'extra' field in at least one other section AND if the gun isn't a part of any sections listed in the `loadouts_per_name` section (i.e. the scripted ones). The first check is to prevent a random section with weapon fields in it from being considered if its not actually referenced.

To use, press numpad 3 on your keyboard while in game, then spawn the weapon class you want via the UI. You can also spawn all weapons and clear all weapons from your inventory

Might work for other modpacks / base anomaly  
