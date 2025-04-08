+++
title = "Building An Organic MMORPG"
date = 2025-04-06
draft = true
[taxonomies]
tags=["Tinker","Game Design","MMORPGs"]
+++

In a [previous post](@/posts/mmorpgs-2025-4-5.md), I mentioned that I would follow up with
a description of a system that would allow an MMORPG world to be organic and constantly changing. 
I don't like the methods that current generation multiplayer games use to do this (artificial 
faction war systems or regular releases of new content). This is that follow up.

There seem to be two broad approaches to doing this- manual and generative. Generative
suffers from a same-y feel that's hard to get away from. Many games use procedural generation for
dungeons or their entire map, and done well, it's not *terrible*. Even when it's done well, it can
start to feel repetitive after a while- maybe dungeons have a tunnel that goes *this* way instead 
of *that* way, but it's recognizeable as the same dungeon, regardless of the precise details of
the layout. When it's done badly, it's almost as repetitive as not having procedurally generated 
dungeons at all. Who remembers the *exact* layout of a dungeon? The monsters are the same, the 
aesthetics of the location are the same, and the loot, despite being random, is roughly the same 
each time. 

The alternative is to have a game world that can be updated and redesigned without bringing the 
servers down, and as far as I know, no one does this. Probably because it's considered too manpower
intensive to pull off. You would need teams of game designers who do nothing except rebuild dungeons 
and move monster camps around. 

I think that this is possible though, if tools are built to make it easier to do. 

Imagine a game where there are two separate clients. One of them is the standard client that the
players use to access the game. The other is used by game masters to manage the game. From the game
master's client, it's possible to design and stage changes to the game world, which are only applied
when particular things happen. Before they're staged, they can be tested automatically and reviewed
by other game masters, and once applied, the game master will be responsible for tracking player 
interaction with the changes to make sure that nothing unexpected happens.
