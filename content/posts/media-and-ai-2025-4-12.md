
+++
title = "Media Manipulation With AI"
date = 2025-04-12
draft = false
[taxonomies]
tags=["AI","Politics","Media"]
+++

{{ figure(src="/images/broad_city_cringe.png", alt="Abbi and Ilana freak out over Hillary Clinton", caption="Believe it or not, no one is about to be arrested for public indecency in this scene.") }}

Last year, I attended the recording of a podcast called Austinprenure in Texas (episode is [here](https://podcasts.apple.com/us/podcast/combating-disinformation-with-knowledge-graphs-and-llms/id1446779826?i=1000670542827), my questions start at around the 35:00 mark). The guest described their work to trace the flow of radicalization through central europe. His description was very general (likely because much of it is classified), but from what I understand, it involved ingesting huge amounts of media content created in central europe and analyzing it for particular messages, then watching how those messages were propagated on social and traditional media to identify sources that were responsible for radicalization.

My question was whether this could be done in reverse. It seems like it could. I've heard image generation from plain text described as just the opposite of description generation for images. While it may not be *exactly* the reverse in a you-can-just-run-this-model-backwards sort of way, it seems obvious that if the technology exists to generate descriptions for images, then the technology *also* exists to generate an image from plain text descriptions. In the same way, if you have a model that can ingest media and then describe the radicalization that might result from it, then the technology *also* exists to describe radicalization and then generate media that pushes people toward it.

A system like this might even be able to influence political and cultural views without ever producing content that would be considered political (or even relevant). In [an old blog post](https://slatestarcodex.com/2014/09/30/i-can-tolerate-anything-except-the-outgroup/) by Scott Alexander, he writes-

> The Blue Tribe is most classically typified by liberal political beliefs, vague agnosticism, supporting gay rights, thinking guns are barbaric, eating arugula, drinking fancy bottled water, driving Priuses, reading lots of books, being highly educated, mocking American football...

It seems possible that making someone less interested in football might actually make them more liberal politically, in a tail-wags-dog sort of way. If someone who was a fan of the sport becomes less interested, they'll stop hanging out with friends who are still following the game. They may have fewer parties with those friends. They may be more willing to view and read content from *other* people (likely liberal) who dislike the game. Their friend group may slowly shift to the left, politically. Although it's difficult to find any research on this (if you have any, feel free to email me), just at first glance, this seems like something that could happen. The real question is- how do you reduce interest in football? 

Driving this change in interest is hard, but not impossible. If you have control of their social media feeds (which are almost always algorithmically driven to one degree or another), you might naively assume that you could just insert some anti-football content. This is unlikely to work, because people often become more entrenched in their views when those views are challanged[^1]. What likely *would* work is providing ostensibly pro-football content that's just... *cringe*. 

For an example of cringe, [here](https://www.youtube.com/watch?v=lJgM4_C3gvE) is the scene in [Broad City](https://en.wikipedia.org/wiki/Broad_City) where I totally lost interest in the show. Not because I especially dislike Hillary Clinton, but because this level of adoration toward *any* politician is unsettling and cringey to me. I understand they were playing it for laughs, but I didn't laugh. I winced.

{{ figure(src="/images/broad_city_comments.png", alt="Comments on the Broad City Hillary Clinton cameo", caption="So did everyone else.") }}

I don't want to pick on Broad City, specifically, but it was the first example that came to mind. I stopped watching the show after this scene. Did it make me more conservative? Not in any noticeable way. But what if I regularly viewed content that highlighted the most cringe-inducing, silly, or ridiculous people that share my own ideology, even while supposedly supporting them? I would like to believe that I'm immune to this sort of soft-propaganda, but I've met too many people who thought the same and were wrong. Given enough time, I think it might push me away from what I currently believe. 

And just to be clear, this is only *one* example of *one* way in which someone could be influenced. Maybe our model doesn't generate cringe- maybe it introduces them to local organizations that are A) related to something they're interested in, and B) already stacked with people slightly to one side of their current political alignment. Maybe it promotes content from friends they haven't seen in a while who share *most* of their views, but have crucial differences. Maybe they tend to match with people on Tinder that don't like football. There is a huge space of possible ways to influence someone when you're ingesting terabytes of data and mining it for fuzzy and exploitable relationships in order to do it.

Any organized attempt to do this at scale would be a massive undertaking, likely requiring access to huge amounts of user data, intimate control over the content that those users are consuming, and some serious improvements in AI technology. Unfortunately, all of those things are becoming easier with time. People are using social media more than ever before, and these platforms collect vast amounts of information on them[^2], while AI is only becoming more capable[^3]. The feeds that people use to discover new content are almost entirely algorithmic now, with only a few platforms stubbornly clinging to chronological or category-based recommendations, and the "algorithms" are more likely to be AI. At the same time, people are more likely to self-sort into [isolated](https://en.wikipedia.org/wiki/Filter_bubble) (read: vulnerable) communities that share common beliefs.

It would be difficult, but not impossible, even with current technology. And it's only going to become *more* possible.

Given enough data, enough control over what people see, and strong enough AI, you could build a system that generates content designed to sway an entire population into believing particular things. If such a system were controlled by the Metas and Tiktoks of the world, then it would probably be used to deliberately excise radical or undesireable elements from their platform, increase user engagement, and generate profit in various ways, all without ever doing anything that most users would recognize as manipulative. But once the tools are in place, how long would it take them to be used on behalf of the state? 

Social media companies have already been accused of censoring or de-emphasizing political views on the right and the left. Whether any particular accusation has merit or not, it's definitely something that *could* happen. If Twitter had a tool in place that could incrementally and almost unnoticeably shift the discourse in one direction or another, I have difficulty imagining that tool not eventually being used to placate the US government.

And if the content is funny and interesting, people will watch it. If, sometimes, a few people see an uptick in content that makes them roll their eyes at their own party, tribe, or demographic, who cares? It's not like they're going to go out and start campaigning for [insert other political party here].

Well, not the *first* time they see it. Or the second. But eventually? Maybe.

Do I think that anyone in the current administration would try to build something like this? No. This isn't because I have faith in their essential goodness, but because I don't think any of them understand that it's even possible. But some people working for the military or intelligence community likely have some idea that it is, and are competant enough to build it. As the barriers continue to lower, something like this will gradually become more and more likely.

{{ figure(src="/images/torment_nexus.jpeg", alt="Tech company builds the Torment Nexus", caption="Twitter would build the Torment Nexus for a 5% bump in user retention.") }}

Beyond companies influencing public opinion for engagement and money, beyond governments using the same tools to manipulate and control their citizens (I'm looking at you, China), there's the threat of rogue AI doing the same. 

While I'm not a fervent believer in the rise of superintelligent artificial intelligence, I don't entirely discount it. I've already discussed the [AI 2027](https://ai-2027.com/) scenario in another post, and if something even vaguely similar to that scenario were to occur, this is another way that an agentic AI could manipulate public opinion. Are people pissed over losing their jobs? Are they scared of a fully autonomous economy? If tools like this exist, then any agent worth it's compute would be able to paint dissidents as luddites and gather support without ever doing anything that a human being could point to as manipulative.

So anyway. That's it. Enjoy the existential dread.

[^1]: "...when exposed to arguments supporting positions different from their prior views, people often (though perhaps not always) become even more convinced of their prior views rather than being swayed by arguments" - [Can Arguments Change Minds?](https://academic.oup.com/aristotelian/article/123/2/173/7207975)
[^2]: "We collect information about how you use our Products, such as the types of content you view or engage with; the features you use; the actions you take; the people or accounts you interact with; and the time, frequency and duration of your activities." - [Facebook Data Policy](https://www.facebook.com/about/privacy/update/printable)
[^3]: "The overall performance of LMs gets reliably better as investment increases. Rapid progress in LMs has primarily come from simply training larger models on more data" - [AI Digest](https://theaidigest.org/progress-and-dangers)