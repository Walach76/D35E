# DnD 3.5e implementation for [Foundry VTT](http://foundryvtt.com).
Created from love for old DnD editions, this systems aims to provide full 3.5e SRD implementation and system flexible enough for anything else, with useful automations to help smooth out the gameplay both for GMs and Players.

![screen](docs/system-screen-skin.png)

This system provides character sheet support for Actors and Items, suport for systems like Psionics, Containers and Shapechange and ever growing compendiums with data on Monsters, Classes (along with features), Spells, Feats, Magic Items*!  (Plus we have a custom skin, if you are into those kind of things.)

*Some of them are currently descriptive only, as system is in heavy developement.
## Installation
Just search for DnD 3.5e in foundry system browser and click install! It is that simple!

### Manual Install

Install the following game system in FoundryVTT's game system tab: [https://www.dragonshorn.info/dnd35e/system.json](https://www.dragonshorn.info/dnd35e/system.json)

If you wish to manually install the system, you must clone or extract it into
the Data/systems/D35E folder. You may do this by cloning the repository or
downloading a zip archive from the [here](https://www.dragonshorn.info/dnd35e/dnd35e.zip).

## Documentation
You can find documentation on [wiki](https://dnd35e.dragonshorn.info/). Be advised that this is heavy work in progress. You can find FAQ [here](https://github.com/Rughalt/D35E/wiki/FAQ)

## Progress
You can track SRD implementation progress [here](https://github.com/Rughalt/D35E/projects/1)

### Systems
Most of the stuff that is the same as in PF1 works. For things that are different:
- Psionics - Implemented base system
- Shapechange - Implemented Wildshape, Polymorph, Alter-self

### Compendium

- Base classes - Done
- Base NPC classes - Done
- Feats - In Compendium, partially implemented
- Racial Traits - Partially done
- Racial HD - Done
- Monsters - Dome (there may be minor errors as they are imported using tool)
- Items, Magic Items - Partially done, Shields and Weapons implemented
- Spells - Partially done, most of the work done by BigSexy#9434


## Support
This project is done in my free time and for free. You can discuss it, post bugs and get in tough with me on projects official [Discord Community](https://discord.gg/wDyUaZH)

If you enjoy it you can support me on [Patreon](https://www.patreon.com/rughalt)

## Packtool
As changing compendiums is not very fun in foundry and nedb is not a proper json, packtool.py can be used to pack and unpack data to sources directory.
Use `packtool unpack <compendium file>` to unpack to json and `packtool pack <compendium file>` to pack to db (generating proper random nedb ids).

## Credits

The software component of this system is distributed under the GNUv3 license
while the game content is distributed under the Open Gaming License v1.0a.

The entire base work of this system is based on Furyspark's 
on the PF1 system made over [here](https://gitlab.com/Furyspark/foundryvtt-pathfinder1)  and LoopeeDK#9498 work 

Icons provided in source distribution (on this github repository) by 
- J. W. Bjerk (eleazzaar) -- www.jwbjerk.com/art  -- find this and other open art at: http://opengameart.org - CC-BY 3.0
- Various authors at [game-icons.net](https://game-icons.net/)

Rest of icons - provided in binary distribution - are used with persmission of the authors and licensed to use only in this application. Any other use is prohibited.

