# DungeonMod
The official repository for Nova's DungeonMod.

# What is this?

DungeonMod is a modern rogue-like game that combines core aspects like text-based graphics and gameplay, leveling up and improving skills, with new features like dynamic gameplay, building and crafting, multi-player dungeon raids, and perhaps even planetary travel.

# Game info and controls

DungeonMod uses a variety of new game mechanics that were not traditionally included in roguelikes. First and foremost is frame handling. In the original Rogue, the entire game would update when the player moved. In DungeonMod, there is a frame handler that can be edited in the options menu. By default, the frame handler updates the game at 4 frames per second.

Another planned feature is hosting and joining multiplayer servers. Servers would seem almost like an impossibility with the original frame handler, because if every player is moving basically constantly, the game and server would update so quickly it would become unplayable.

Frame limiting is a mechanic that allows the player to play at a certain framerate. By default this is set to 4 frames, or ticks, per second. for slower gameplay, the frame limit could be set to something like 2, and for a faster experience, a user could set the limiter to something like 6-8.

# The Project
DungeonMod started as an idea back in 2010 to create a text-based inter-galactic adventure game. I called this game Andromeda. 

Andromeda actually was a viable roguelike, but the problem is that the galactic travel never actually made it into the game. Eventually, I shut down Andromeda and put the source code on an 80GB disk that currently resides in my garage. I am completely rewriting the code and calling it DungeonMod.
