# Scatter Spawn
A custom *mod* for allowing separate spawn locations in multiplayer. Designed for Co-op and PvE. 

Only supports 0.15.x at this time!

## Instructions

### STEP 1

Download the zip. 

Windows: Place it in your %appdata%\Factorio\mods folder.

### STEP 2

Open the game and edit the configuration via Options > Mods

### STEP 3

Generate a new map; use that save file to host if you want to.

## Configuration

Configuration is accessible via Options > Mods.

Look in config.lua for some controls over the different modules.  

Not all configurations have been fully tested so modify at your own risk.

If you want to change the RSO config, look for the rso_config and rso_resource_config files.

## TODO

- [ ] Actually move all the configuration to Options > Mods via settings.lua. For now, you may need to edit config.lua as well.

- [ ] Add actual RSO mod support.

## Credit

RSO is not my own creation. It was done by Orzelek. I requested permission to include it in my scenario.  

https://mods.factorio.com/mods/orzelek/rso-mod

Several other portions of the code (tags, frontier style rocket silo) have also been adapted from other scenario code.

Credit to 3Ra for help as well: https://github.com/3RaGaming

Praise be to Mylon


## Random Notes

While it is an option to disable RSO, I would not recommend doing that. I can't guarantee any bugs or issues as I focus mostly on testing with RSO enabled.

Feel free to submit bugs/fixes/requests/pulls/forks whatever you want.

I do not plan on supporting PvP, but I will help anyone who wants to make it a configurable option.

## Known incompatible mods

- The Ruins Mod
- The real RSO, probably
- Angel's
- Bob's
- Anything that affects world generation or adds naturally spawning resources