---
title: Glorified Undo
subtitle: Use time travel to prevent mistakes
tags: [time travel, puzzles]
---

This model of time travel assumes the [growing block view](https://en.wikipedia.org/wiki/Growing_block_universe), in which time
is built moment by moment, with the 'active' growing part being by definition the present. It then asks a simple question: what
if we could undo this growth? That is, if the universe is a growing stack of instants, remove the top layers of this stack. Once
the removal of layers stops, new layers grow on top of the new present, overwriting the undone history. In contrast to the
[Spicy Undo](/time-genres/spicy-undo) model, nothing survives this undoing of history; only the player's memory, since they are external
to the game world.

This is a very natural and consistent model for time travel. There are no possible paradoxes: for example, an undoing-time machine can only
take the universe to states it has already experienced, so you can't go back and kill baby-you (since there never has been an
"adult-you interacting with baby-you" state for the machine to return to). Since the external player's experience is the only
thing not affected by the undo, such a machine in a video game is equivalent to a "see what would happen if you took these actions" machine.

In fact, you're probably extremely familiar with this mode of time travel: any game that has an undo or reset button, or a saving/loading
feature, fits into this category. It's a pet peeve of mine when [a list of games containing time travel as a gameplay element](https://en.wikipedia.org/wiki/List_of_games_containing_time_travel#Time_travel_as_a_gameplay_element)
arbitrarily includes [some games with undo](https://en.wikipedia.org/wiki/List_of_games_containing_time_travel#:~:text=Historia%20Crux%20system.-,Forza%20Motorsport%203,-2009)
but not others, simply because the undo is called "rewind" instead of "undo". Games about being stuck in a time loop also belong in this category,
since their underlying model of time is the same as any regular game with a reset button.
This entry will only list the few games that really focus on vanilla undoing/reseting, not those that simply relabel it as time travel. 

With this very basic model out of the way, we can now examine more interesting ideas. For example, what if not all in-game objects
are affected by the undo? We then get [Spicy Undo](/time-genres/spicy-undo).

<a name="save-scummer"></a>

-----

### [Save Scummer](http://www.zincland.com/7drl/savescummer/) by Jeff Lait

A tongue-in-cheek roguelike where most actions are done automatically, leaving the player the only truly important choice: when to save and load.
When the game's randomness conspires against you, simply undo a bit and try again until you get lucky! Fun short experience, highly recommended - thanks to JumbleTraveling for suggesting it.

![Save Scummer](../../assets/img/save-scummer.png){: .mx-auto.d-block :}

-----


## Variants & future work

In a fully deterministic universe, a time machine that was capable of undo would be
disastrous: once activated, it would erase some amount of history, leaving the universe in the exact same state that originally led
to the machine being activated. In other words, a time traveler whose memories don't survive the travel will always commit the same
mistake that makes them use the time machine, leaving the whole universe stuck in a loop. Games don't have this problem since
the player is immune to the in-game undo, meaning that they can make different choices. Could we make a game in which even the
external player was affected by the in-game undo? First, we would need another solution to the inescapable loop problem. What about a non-deterministic universe?
In that case, the machine could be used as follows: take an action at random; if the outcome isn't the desired one, activate the
machine and return the universe to the moment before taking the action. If there's some chance of success, however small, that will be
the resulting timeline. Inhabitants of this universe would have a very unique experience: from their point of view, the machine has
never been activated, but they've been much luckier since it was created. 
I haven't yet found a game that uses this real-player-also-affected-by-undo variant. Assuming it's impossible for a video game to mess with the actual
player's memories (or timeline!), the effect will have to be achieved by only letting the player see the final timeline, meaning that they will have to interact
with the mistaken-timelines without ever seeing them. How would such a game look? I think it could work well as a zachtronics game:
the player must design a contraption/program/etc with access to an undo machine and some source of randomness.
When the player executes their creation, they will either only see a
successful attempt in which all the randomness conspires to solve the problem, or be stuck in an unsuccessful timeline that failed to activate the undo machine.
I'm not sure that such a game would be interesting; besides, executing the players' creation and finding the appropriate timeline is in general an NP-hard problem.
Still, if you see (or create) a game like this, please contact me & I'll feature it here!

-----