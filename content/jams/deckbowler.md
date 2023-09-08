---
title: "deckbowler"
period: "7 Aug -  18 Aug 2023"
goal: "bowling deckbuilder"
date: 2023-08-21T09:50:53+05:30
---

I really like the concept of deckbuilders. I think there is something really
satisfying with a game where you have to adapt your playstyle on the fly, as
you get different abilities, and then figure out how they all work together.

I thought it might be interesting to have a bowling game based around the same
concept. Where you can have different goals every frame, and adapt your bowling
strategy as you collect more abilities.

### development

Though the jam was two weeks long, I was really only able to work on it for a few
days.

Initially I wanted to have the concept of a "shop" where you can purchase your abilities.
And the currency would be something unrelated to your final score. The idea would be that
in the early game, you would be focussing on building up your currency, and in the later game
you would focus on score, and would have to balance those two things out.

Unfortunately
time didn't permit me to really follow this approach. In the end it is just a basic high score
game.

[play deckbowler](https://chapliboy.itch.io/deckbowler?secret=CoiPuilspa1vGHDawzM7x7H8)

### conclusion

The game really didn't turn out the way I had hoped. In the final version, there is far too
much randomness and the whole thing is just based on the luck of the draw. The whole idea of
multiple viable builds really didn't come into play.

Also, there are only frame-long effects in this version. So the concept of a "build" doesn't
even really exist. I had very few ideas for effects that would last the whole game, so I wasnt
able to add those in.

Overall, it's far too much about luck.

On one lucky run, my score ran into the trillions, but most runs, you're scoring in the mid
thousands. I wanted to include these kinds of exponential effects, but since its random, the
whole thing becomes more luck based...

<img class="essay-image" alt="highscore screenshot" src="/img/deckbowler_highscore.png"/>

I think the bowling concept has some potential, but this was just the wrong route to go down.
I didn't really have enough time to course correct, but that's okay.

### takeaways

In a game like this, everything needs to be parameterized, so that cards can effect everything.
For example, in bowling a strike adds the score of the next two rolls, and spares
adds the score of the next roll to that frame. This was
hardcoded, so I wasn't able to have an effect where you can increase the scoring of a spare to
make it eventually more valuable than a strike. Or to have a way to have only gutterballs score
incredibly well.

Since some of those things got hard coded fairly early on, it was hard to add them in later. I think
having a good understanding of all the things that you might want to change with effects is
something that I needed to have a grasp of earlier in development.

There also needs to be more decisions that can be made, as well as a way to counter the randomness.
Right now, everything depends on the cards, and that is all fully random. There needs to be more
player agency, so that they can build around the cards that they draw.

Overall, I think I just need a lot more time to really figure some of these things out, and hopefully
the next time I try something like this out, I will be able to find some interesting ideas.
