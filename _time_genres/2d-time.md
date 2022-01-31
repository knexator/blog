---
title: 2D Time
subtitle: Two different directions of time
tags: [time travel, puzzles]
---

[Playing with extra spatial dimensions is always fun.](https://4dtoys.com/) Will we get the same flavor by playing with extra
temporal dimensions? By this, I don't mean having 2 time-like dimensions in General Relativity (which is explored in Greg Egan's
[Dichronauts](https://www.gregegan.net/DICHRONAUTS/01/World.html)). Rather, I mean that objects have "worldplanes" instead of worldlines, or in other
words, that we must ask "Where is the object at time (t1, t2)?". This extra time coordinate has a lot of unexpected effects; let's explore them!
TLDR: the end result will be pretty disapointing, but the road to get there has some interesting twists.

Let's start by making some diagrams. One dimensional time might look something like this:

![1d-time](../../assets/img/time-2d-diagram-1.png){: .mx-auto.d-block :}

Each circle represents an event, and the arrows represent causality. The event A is caused to the event to its left, which is itself caused
by the event to its left, etc. The event A also causes the event to its right, which will cause the event to the right of that, etc. Taking
A as a reference point, all events are cleanly divided in two groups: those that cause A (the past), and those caused by A (the future).
(Sidenote: if you know about relativity and [light cones](https://en.wikipedia.org/wiki/Light_cone#Mathematical_construction), this is
a good moment to forget about them. "Speed of causality" doesn't apply since these diagrams have zero spatial dimensions, so all events
are either in the past or in the future of A, there are no events elsewhere)

Simple enough. Let's add an extra time dimension to the mix:

![2d-time](../../assets/img/time-2d-diagram-2.png){: .mx-auto.d-block :}

Causality now advances in two directions: left to right, and down to up. The first notable effect is that time no longer divides cleanly in
Past and Future: there's also the Weird Present. Let's consider the event B: it can't cause A, since A happens before it (with respect to horizontal time), and it can't be caused
by A since it happens after it (with respect to vertical time). We will say that B is in the Weird Present of A, meaning that  
there is no causal chain between A and B. Does this mean that these
two events are completely independent? No: observing one will tell us information about the other. To see this, consider the following example:

![2d-time](../../assets/img/time-2d-diagram-3.png){: .mx-auto.d-block :}

We start at A, wait a second in either direction, and flip a coin. At first sight, B1 and B2 seem like independent events (since no causal chain
connects them), so we could get heads in one and tails in the other. But then, what state will the coin have at C? If some irreversible action
depends on the coin's result, then the coin must give the same result B1 and B2. Thus, the states are correlated: knowing one tells us all about
the other. This is a good moment to feel cheated: our fancy 2-dimensional timeplane A-(B1-B2)-C seems to have collapsed into a boring 1-dimensional
timeline A-B-C.

It turns out that seeing events as points is a flawed idea. Consider this final diagram:

![2d-time](../../assets/img/time-2d-diagram-4.png){: .mx-auto.d-block :}

We start with a ball at rest, and kick it when our bi-watch shows 2,2 o'clock. Let's consider the state of the ball as a function of time(s), F(t1, t2).
The bare minimum we can ask of this function is continuity, that is, that the ball doesn't teleport around. Here are some values of that function: at (1,1),
the ball is at rest; an horizontal second later, at (1, 2), it's still at rest; a vertical second after that, at (2,2), we kick the ball, so we can expect
that a vertical second later, at (3,2), the ball is moving, and will keep on moving an horizontal second later, at (3,3). This is fun! Let's consider
more values: we start again at (1,1), with the ball at rest; 2 vertical seconds later, we get to (3,1), with the ball still at rest. And an horizontal
second later we get to (3,2), where the ball is... moving? Something went wrong: 



-----
