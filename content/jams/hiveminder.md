---
title: "hiveminder"
period: "10 July - 14 July 2023"
goal: "what is the joy of a city builder?"
date: 2023-07-16T17:21:22+05:30
---

The goal for the first jam was to figure out how I can distill what I enjoy most about
city builders, and build the simplest version of that for the jam. When I say city builder,
I am mostly referring to games like [Pharaoh](https://store.steampowered.com/app/1351080/Pharaoh_A_New_Era/) and [Caesar 3](https://store.steampowered.com/app/517790/Caesar_3/).

What I like the most about the genre-
- Growth. Starting off with a small colony and then slowly watching it grow over time.
- Balance. As the settlement becomes bigger there are additional needs and requirements, so growth
needs to be balanced with maintainance.

### development

I decided that I would go with a colony of bees as my city builder. It was mostly because I
wanted to try out a hex grid, and playing around with that.

The first thing was setting up the hex grid, and getting all of that working. The rest of the
first day was spent on ideating and figuring how the whole thing would work.

The second day was the start of implementation. A lot of the day was realizing that most of the
planning on day one was wrong for various technical and gameplay reasons.

The third day was just a continuation of that. It was only at the end of day three that I even
had anything that I could compile, and see on screen. It was all wrong of course, but atleast it
was some bees on screen.

Day four was fixing all the issues, and adding in the rest of the mechanics.  At the
end of the day I had a mostly working system, where all the mechanics were implemented, and I
could finally see what the game was all about.

I spent day five just packaging the whole thing. Adding tooltips and trying to work on all the
other UI and UX things.

[play hiveminder](https://chapliboy.itch.io/hiveminder?secret=Fjx5iHuzia3TMHdVwpeJJmIhOk)

### conclusion

I am quite happy how it turned out, especially considering that I only had the one week to work
on it. It's not really much of a game. It's more of a toy. As long as you get off to a start before
the initial bees die off, it's quite easy to keep the hive alive.

I really like how the whole thing looks. It's a really clean aesthetic, and watching the bees move
around and do their tasks is really hypnotic and calming. It really scratches that itch of watching
what you have build slowly grow. Watching the bees build up new rooms, keep the food stores full and
maintain rooms that are deteriorating is really satisfying. You can see the situation develop, then
the bees all quickly go and handle the problem, and that's quite nice.

I don't think it's really possible for other players to experience it because it's not really
presented in the best way, and having to decipher why things don't work may not be intuitive. But
I think if it was a longer project, and they could be onboarded correctly, the goal of delivering
on an experience is met fairly well.

### takeaways

I think I underestimate just how front-loaded system driven games can be. A lot of the code and
systems have to be written for even the simplest prototype to come up and running. In a platformer / sokoban
you can atleast start off by writing the simple physics, and seeing your character move around, but
in such a systems heavy project, the "minimum viable product" requires a lot of time, code and
effort to set up.
And then suddenly you have a it up and running, and then iterating, and adding features
is super fast, as long as your systems have been set up correctly to handle that.

I shouldn't be trying to complete and package the game. I should be more focussed
on actually exploring the systems. I think day five would have been better spent if I had spent
all the time just playing with the prototype rather than creating the UI.

I think a lot of that comes from fear. The puzzle design / system exploration is very daunting and
intimidating for me. Writing code, making UI, "completing prototypes" are all skills that I have a
lot of experience in, and not so much with game design in general.

So when it came to pick a task to do on the final day, I picked the easy route and focussed on the
UI/UX, rather than doing the hard thing, and exploring the system.

That kind of puzzle design / system exploration was also daunting and intimidating when I was working
on KCPS. I think it's just something about actually having to face that fear of not being able to do it.
Once I have made the system, exploring it is terrifying.

_What if I don't find something interesting?_

_What if I just sit and stare at this, and nothing comes out?_

When it comes to all the skills required to make a game, you can learn most of them elsewhere. I
learnt how to program making websites and things. I learnt art in a bunch of sketchbooks. Music
on a mostly neglected guitar. Writing over a slew of abandoned stories and essays.

But when it comes to game design, there is no other place to gain that experience. You just gotta
do the hard work. And when the rest of the work is relatively easier, it gets even harder.

For me, searching for emergence is an almost existential fear. I don't know where it comes from.
I have seen it in many forms, but I can't manufacture it on demand. I can spend a week making
the systems, but have no way of knowing if anything beautiful will emerge from it.

And rather than facing that fear, I took the easy way out. Hmm. I gotta do better next time.

<br><br>
<div class="note">
note: The end of that got a little more than I had intended. But I will keep it in.
I think it's something that a lot of devs face, and maybe don't talk about. So hopefully it helps.
</div>
