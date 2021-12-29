---
title: Glorified Undo
subtitle: Use time travel to prevent mistakes
tags: [time travel, puzzles]
---

This model of time travel assumes the [growing block view](https://en.wikipedia.org/wiki/Growing_block_universe), in which time
is built moment by moment, with the 'active' growing part being by definition the present. It then asks a simple question: what
if we could undo this growth? That is, if the universe is a growing stack of instants, remove the top layers of this stack. Once
the removal of layers stops, new layers grow on top of the new present, overwriting the undoed history.

This is a very natural and consistent model for time travel. There are no possible paradoxes: for example, an undoing-time maching can only
take the universe to states it has already experienced, so you can't go back and kill baby-you (since there never has been a
"adult-you interacting with baby-you" state for the machine to return to). Since the external player's experience is the only
thing not affected by the undo, such a machine in a videogame is equivalent to a "see what would happen if you took this actions" machine.

In fact, you're probably extremely familiar with this mode of time travel: any game that has an undo or reset button, or a saving/loading
feature, fits into this category. It's a pet peeve of mine when [a list of games containing time travel as a gameplay element](https://en.wikipedia.org/wiki/List_of_games_containing_time_travel#Time_travel_as_a_gameplay_element)
arbitrarily includes [some games with undo](https://en.wikipedia.org/wiki/List_of_games_containing_time_travel#:~:text=Historia%20Crux%20system.-,Forza%20Motorsport%203,-2009)
but not others, simply because the undo is called "rewind" instead of "undo". Which is why this particular entry wont list any games
(since the other option is to list [almost] every puzzle game).

With this very basic model out of the way, we can now examine more interesting ideas. For example, what if not all in-game objects
are affected by the undo? We then get [Spicy Undo](/time-genres/spicy-undo).

## Variants & future work

### External player isn't inmune to in-game undo
In a fully deterministic universe, if truly nothing was inmune to undoing, a time machine that was capable of undo would be
disastrous: once activated, it would erase some amount of history, leaving the universe in the exact same state that originally lead
to the machine being activated. In other words, a time traveller whose memories don't survive the travel will always commit the same
mistake that makes them use the time machine, leaving the whole universe stuck in a loop. Games don't get stuck in this state since
the player is inmune to the in-game undo, meaning that they can make different choices. If we want the player to also be susceptible
to the in-game undo, we will need another solution to the unscapable loop problem. What about a non-deterministic universe?
In that case, the machine could be used as follows: take an action at random; if the outcome isn't the desired one, activate the
machine and return the universe to the moment before taking the action. If there's some chance of success, however small, that will be
the resulting timeline. Inhabitants of this universe would have a very unique experience: from their point of view, the machine has
never been activated, but they've been much luckier since it was created.

I haven't yet found a game that uses this real-player-also-affected-by-undo variant. Assuming it's impossible to mess with the actual
player's memories (or timeline!), the player should only be able to see the final timeline, meaning that they will have to interact
with the mistaken-timelines without ever seeing them. How would such a game look? I think it could work well as a zachtronics game:
the player would be tasked with designing a contraption/program/strategy with the condition that it has some chance of success & that
if it doesn't suceed, it should activate the undo machine. When the player executes their creation, they will either only see the
successful attempt, or be stuck in a unsuccessful timeline that failed to activate the undo machine. There are some problems with this
game; first, I'm not convinced it would be terribly interesting; second, executing the players' creation and finding the appropiate
timeline is in general a NP-hard problem. Still, if anyone overcomes these hurdles, please contact me & I'll feature your game here!