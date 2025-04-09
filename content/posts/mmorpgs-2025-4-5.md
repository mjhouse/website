+++
title = "Player Limitations in MMORPGs"
date = 2025-04-05
draft = false
[taxonomies]
tags=["Tinker","Game Design","MMORPGs"]
+++

![Level 1 MMO characters](/images/lvl1_mmo_characters.jpg)
<small>Just nine more giant crabs, man, and then I'll turn in the quest, get a beginners sword 
and move on to killing giant rats...</small>

I've been playing a lot of [Albion Online](https://albiononline.com/home). It's... not very good.
That's not to say that it's *bad*, really, but it's just not a particularly compelling game. I'm
never caught up in thinking about the next thing I should do in the game while I'm not playing
it, or trying (and failing) to convince myself to stop playing and do something more productive. 
Unlike addictive drugs and better made games, where you tell yourself (and everyone else)
that you can stop whenever you want, man, I swear- I actually *can* stop playing whenever I want, 
because it's just not very engaging. I described it to a friend as "slightly more fun than 
doing nothing at all", which about sums up the entire experience, I think.

I do spend a lot of time thinking about how it could be made better, and for a while I had a document
where I was listing all of the things that could be done to make the game more compelling. Some of
those changes are listed below (if you don't know anything about MMOs in general, or Albion Online
in particular, feel free to skip the following list).

* Random monsters are scattered about the map, and they attack you when you're travelling or gathering
  nearby. I would group them into camps and thin out the random individual monsters. It would make
  both travelling and gathering less annoying and would look much more natural.

* Monsters attack you when you get too close, but in Albion, you have to get *very* close before they
  attack. It looks silly, but happens accidentally all the time because there are so many of them 
  standing around. After I grouped them into camps, I would increase aggro distance to make camps
  more dangerous.

* When monsters attack you, their attacks *always* land. This is never more noticeable and aggravating
  than when you're just running by and a golem takes a shambling swipe at you that lands when you're 
  already fifty feet away. For bonus annoyance, it also removes the speed buff that you get from
  riding. I would make attacks fail if you're out of range.

* Recalling to town in Albion costs money based on weight and distance to town, and takes you back
  to the last town you were in, rather than your home city. I would do away with this and add 
  craftable recall scrolls that take you home (or maybe to a particular city).

There were were more notes, but you get the idea. The recall problem, in particular, was grating to me- 
nothing about the game is improved by forcing players to pay increasingly large amounts to recall
based on distance or weight carried. The only real reason it would be designed that way is to 
force players with no money to spend fifteen minutes running back to town, and allow players *with*
money to avoid that annoyance. Maybe as a bid to push players toward paying real money for in-game
gold? I don't know. And because recalling takes you back to the last city you were in, *not* your 
home city, if you make the mistake of walking into a strange city a long way from home, your 
recall now takes you *there* instead of home.

On the other hand, recall scrolls immediately make the game more interesting. If you're poor, you
can still avoid that run back to town with a little planning, but you have to invest some time in
crafting scrolls, which could be interesting in it's own right. If you're rich, of course, you can 
just buy the scrolls from the auction house. If the scrolls are locked to a particular town instead
of to the home city of the player who uses them, then things get even more interesting. Players 
would be able to buy scrolls for a particular city and transport them to another city to be sold for
a profit, creating a niche market in fast-travel. You could even travel to dangerous and exotic
locations to create recall scrolls and then sell them for a large profit in the main cities.

Of course, Albion already has fast travel, and it's provided by an NPC in each city who charges
you based on weight. Presumably another attempt to push players toward purchasing in-game gold with
real money.

All of this got me thinking about creative constraints, and how they might drive interesting gameplay
in an MMORPG.

One good example of this are maps. In most MMORPGs, there's a world map that the player can use to get 
an idea of where they are in the game, and where everything else is. It might be simplified or highly 
detailed, but it's the same level of detail for all of the players at all times. You're using the same 
map at max level as you are when you start the game. Imagine if, instead of being a constant part of
the game, the map had to be *crafted*. Now you have a bunch of new, interesting ways that the players
can interact with the game-

* New players only have the sketchiest of ideas where they are and what else is out there, which makes 
  the world seem big and mysterious. 
* Players with the appropriate skills (scouts, cartographers and the like) would become valuable as 
  party members because they could guide the group to dungeons or points of interest in the world. 
* Players who can create maps have a reliable source of income that doesn't rely on combat ability, 
  *and* a good reason to go out and explore the world.
* The game has a new secondary market in maps of varying levels of detail, or with different features 
  (think enchanted maps with resource locations).
* Acquiring rare or highly detailed maps would give players goals to work toward that are more nuanced
  and interesting than "kill ten rats, XP number goes up"

This one small constraint on the players opens up a world of options for interesting gameplay. This could 
become even more elaborate if the game designers really leaned into these new features. Players with pets could 
scout an area quickly and make highly detailed maps more easily. Players with particular skills might be 
able to create enchanted maps that not only show where buildings are, but have detailed information about 
resources and monsters. Maps could be bought piecemeal for different regions, making the world seem mysterious 
and large even to experienced players, when they venture outside of the areas where they normally play. 

The possiblities are endless. 

Of course, all of these features take time and effort on the part of the game developers, but even the 
simplest, most easily implemented version of this makes the game vastly more interesting. This general approach 
can be applied to any number of other cases in MMORPG game development, so much so that I feel that it's 
almost a general rule, some sort of fundamental law of game design. I would be surprised if it's not, and I
suspect this is one of those things where an experienced and knowledgeable game designer would roll their
eyes at me and say "yeah, *we know*". I think it just strikes me like a revelation because I'm not an
experienced and knowledgeable game designer.

> Limiting the information that a player has, then providing a way to get that information through gameplay, 
  makes the game more fun.

I recently started working on a design document for an MMORPG that I'd like to make at some point, and this
rule features prominently in that design. While I don't think I have the technical chops to make an MMO 
from scratch (in any reasonable amount of time), I needed some way to scratch the itch that I get in the back 
of my head when I'm playing games that are only slightly more interesting than doing nothing at all.

The other major component of the MMORPG design (which is codenamed "Tinker" because, well, it's just me 
*tinkering*) is to build a system where the world itself is slowly but constantly changing. I think this
is something that MMORPGs in particular struggle with. World of Warcraft tries to do this by releasing new 
content at regular intervals, with repeatable quests and new regions. Other games try to do this by adding 
in some sort of faction warfare system where areas change hands between different (artificial, game-enforced)
groups of players. Neither of these approaches really feels right to me, and I think some more drastic 
and organic system could be created that makes the game world seem more real. Vital. Flexible. Players should
*actually* be able to affect the world in a way that makes a good story

They should be able to point to a place in the world and tell their friends "see that overgrown hill there? 
That's the skeleton of a dragon that someone accidentally unleashed. Fifty players banded together 
and took it down after it destroyed two small villages."

Making that possible is the real trick, and I think I'll be following up with another post where I describe 
an approach that I think would work.

<small>The next post is available [here](@/posts/mmorpgs-2025-4-9.md)</small>