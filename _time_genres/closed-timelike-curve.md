---
title: Closed Timelike Curve
subtitle: Time travel in a single consistent timeline
tags: [time travel, puzzles]
---

Most time travel stories are about defying fate and changing the past. Does this mean that time travel is incompatible with [Eternalism](https://en.wikipedia.org/wiki/Eternalism_(philosophy_of_time)),
the view that the future is as real and fixed as the present or the past? Not at all! Even in an unchanging universe where all of time is already
laid out in a 4th dimension and fate can't be escaped, time travel could still be possible: not to alter the past, but to cause it. For example, someone
suddenly gets visited by their future self, who gives them the blueprints for a time machine; after some years building it, the machine is complete,
so they use it to visit their past self and give them the blueprints. This story is logically consistent and compatible with a fixed universe in which
time is an illusion and the past can't be changed. It presents an interesting question, though: who designed the time machine?

In a universe with Closed Timelike Curves (the fancy name for consistent time travel),
Nature must do some hard calculations to find a consistent timeline. In the same way that Nature must "compute" which is the shortest path for a light
ray to travel between two points, it must also find which contents of the time machine will be stable. The main difference is that finding such a stable
timeline is an NP-complete problem. For example, let's say we are given a sudoku puzzle. We start by getting a message from 5 minutes into the future:
a potential solution for the sudoku. We then spend 5 minutes checking if the solution is valid. If it is, we send the message 5 minutes back in time, unchanged.
If it isn't, we change some numbers randomly before sending it. This will lead to an inconsistent timeline (since the message we send isn't the same one
we receive), meaning that the only possible timeline is the one in which we get a valid solution. Thanks to the time machine, the hard work of solving a
sudoku is done by Nature, and we only have to do the easy part of verifying it (check out 
[Scott Aaronson's lecture](https://www.scottaaronson.com/democritus/lec19.html) for much more detail).

This suggests an interesting category for puzzle games: games where the player takes the role of Nature, and their only input is deciding when and what
messages/objects arrive from the future, with the goal of creating a consistent timeline. As the sudoku example shows, this can be easily applied to
already existing games (&lt;rant> maybe we will see [wikipedia's list of time travel games](https://en.wikipedia.org/wiki/List_of_games_containing_time_travel)
feature sudoku apps, complementing all the [Glorified Undo](/time-genres/glorified-undo) racing & action games </rant>). Games designed from the
ground up for this model of time travel can do much more exciting stuff: for example, objects arriving from the future might alter when and how far
back the next package is sent to the past. The player must be able to think about the whole timeline, so it's common for these games to not have an
avatar, and instead let the player freely scrub through time.

Here are some games with this model of time travel:
<a name="time-conundrum"></a>

-----

### [Time Conundrum](https://puzzles.mit.edu/2013/coinheist.com/get_smart/time_conundrum/) by MIT Mystery Hunt

Puzzle-hunt style conundrum about sending objects back and forward in time. Explores the theme to its full potential with mechanics such as 
calculating the age of a time travelling object. It's a bit grindy for my taste, but it does have several twists and eureka moments.
Highly recommended.

-----

## Variants and future work

A great way to understand the Eternalist view is by reading a comic: the comic book itself is fixed and unchanging, all frames are equally
real, and yet when reading it we are tricked into thinking there's a passage of time with a past, present, and future. If comics serve to
illustrate Eternalism, why not use them to illustrate Eternalism with Time Travel?
[![Comic strip](https://pbs.twimg.com/media/Ddqm4hpV4AEfoQZ?format=jpg&name=900x900 "Source: panistheman"){: .mx-auto.d-block :}](https://www.deviantart.com/panistheman/art/Comic-Strip-107321958)
I'm not sure of how a game based on this idea would look, but I bet it could be fun.

-----