+++
title = "Building An Organic MMORPG"
date = 2025-04-09
draft = false
[taxonomies]
tags=["Tinker","Game Design","MMORPGs"]
+++

![Wizard casting a spell]({{ image(name="wizard_casting.jpg") }})
<small>Fireball level 2, same as fireball level 1 but with 23% more particle effects.</small>

In a [previous post](@/posts/mmorpgs-2025-4-5.md), I promised that I would try to lay out a way that an MMORPG could have an ever changing world. Monsters and herds of animals should slowly migrate, dungeons should change or even gradually empty and become abandoned before disappearing entirely, forests could spread or shrink as players harvest wood, and rivers would flood or even change course in response to in-game events.

This is tricky, because it's almost impossible to implement convincingly if you want to do it automatically, and game developers are understandably nervous about creating games that require constant human oversight to run. I think the dangers of building a game that has to be managed is worth the risk when it comes to MMORPGs, because these games *already* require constant oversight.

Blizzard, the company behind World of Warcraft, has ~500 developers[^1] working on the game, while Sandbox Interactive (Albion Online) has 100[^2] or so, according to some quick googling. These developers are *already* responsible for implementing new features and releases for these games. If a game could be created that is manually altered at runtime to create an organic, responsive world for players, and if that manual alteration could be overseen by a relatively small handful of dedicated game designers, then much of this ongoing development wouldn't be necessary. The game wouldn't require regular, major releases of new content to keep drawing players in, because the game would be gradually changing all of the time, often in response to player actions.

A team of developers would still be necessary to fix bugs, gradually add or update mechanics, and improve performance, but the massive teams of developers working on new content would be unnecessary. They would be replaced by game designers working within the game world itself to manage the player experience.

While I don't have hard numbers on exactly what the ongoing expense would be for the company that developed such a game, I think it would at least be comparable to the costs of maintaining a more traditional MMORPG, and the difference to the players would be *massive*.

> "given the opportunity, players will optimize the fun out of a game" - [Soren Johnson](https://en.wikipedia.org/wiki/Soren_Johnson)

In traditional MMORPGs (by which I mean *all* existing MMORPGs), the game world is fully-knowable. This means that players gradually converge on optimal builds for characters, create patterns to optimize the grind for resources, and develop strategies for high speed leveling. Players that don't have this deep knowledge of the game mechanics are hopelessly outmatched by players that do. This is fun in a way, because part of the fun of playing an MMORPG is gradually acquiring that knowledge. In another sense, it's *relentlessly boring*, because once you know that an optimal path exists, you feel compelled to follow it, and more dedicated players will create (and publish) that optimal path almost immediately.

If the game world is slowly, but constantly changing, it subverts this pattern. Experienced players can still be caught off guard by changes, and new players have the opportunity to discover things that even veterans don't know or haven't seen before.

Table top games like [Dungeons & Dragons](https://en.wikipedia.org/wiki/Dungeons_%26_Dragons) have a game master who orchestrates the world. They're responsible for telling you where the monsters are, what the dungeons are like, and how the NPCs are behaving. The role of the game master *exists* to keep secrets from the players- if everyone playing knew up front where the monsters were, and why the NPCs were behaving the way that they were, then the game would be boring. 

So why not reintroduce them to MMORPGs?

![Albion Online World Map]({{ image(name="albion_map.jpeg") }})
<small>The world map of Albion Online with five rough regions that each have different terrain, biomes, and monsters. Image taken from a quick google search.</small>

We can divide the world map of our hypothetical game up into regions, each of which is managed by one or two game masters, and give them creative control over the dungeons, monsters, resources, and quests in their region. They would, in a way, be "playing" the game, except their goals would be different from that of the player. They would be trying to provide fresh and interesting experiences, to tell little stories through the game world that players can discover, and occasionally work together to tell larger narratives.

The difficult part of doing this is creating the tools that make it possible. Game masters would need specialized software that would let them create these changes in the world and review them before they're made available to players. Below, I've written a short (and incomplete) list of features that this sort of software would likely need, in no particular order:

* Detailed information on historical player behavior in the game
* The ability to playtest changes inside the current game world
* Tools to alter terrain, place buildings, and script NPC interaction
* A way to review and approve each others changes
* Automated testing to find performance and rendering issues
* Changeover triggers to automate publishing of related changes
* Chat and communication with other game masters
* A pipeline to request and insert new assets from artists

Obviously, there's a catch here. The software that the game masters use to interact with the world would require development itself, which seems to contradict my earlier assertion that the ongoing development effort would be lower on an MMORPG like this. I still believe that the *ongoing* effort would be lower, but the trade-off would be more up-front work. I don't think that there would be as much up-front work as you might think, though.

While I don't have inside knowledge about how World of Warcraft developers construct new regions or quests in the game, I assume that they have internal tools that do some of this. Most developers build tools to make their development process easier as they go along- things like map editors, quest designers, and import utilities. Rather than build these things haphazardly, I'm arguing that they could be combined into a single application and become a deliberate part of the game itself, even after launch.

The result would likely be worth it. 

Dungeons would be intentional and noticeably different, they would appear as the undead dug their way out of the ground or in mines that players have long since emptied of resources. They would fade as players raid them, becoming first abandoned and then only jumbled rocks over old entrances. Herds of animals would migrate, and monsters would invade. Resources in some areas would gradually disappear as players harvest them, and be replaced by resources in new areas, or not replaced at all, leading to shortages and encouraging players to travel further afield to find new forests and mines. Orcs might invade, attacking towns that players believed to be entirely safe, or disappear suddenly, only to return as part of a horde in a different region.

The game would always be different, but never randomly so- it would be different because there are global narratives on top of a hundred little stories and secrets crafted by human storytellers, each of whom is hoping that players will discover and follow those stories to the end.

<small>(I plan to write another post discussing how this can be done from a technical perspective. I'll add a link here when I do.)</small>

[^1]: "...over 500 World Of Warcraft developers have voted to form their own union..." - [RockPaperShotgun](https://www.rockpapershotgun.com/over-500-world-of-warcraft-developers-at-blizzard-have-voted-to-form-microsofts-biggest-wall-to-wall-union)
[^2]: "...and now employ an international team of more than 100 people." - [albiononline.com](https://albiononline.com/jobs)