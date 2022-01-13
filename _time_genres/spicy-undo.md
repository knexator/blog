---
title: Spicy Undo
subtitle: Staying still in a moving world
tags: [time travel, puzzles]
---

At first sight, this model of time seems very close to the [Glorified Undo](/time-genres/glorified-undo) model: the universe is built
moment by moment, and an undo machine will remove the top layers of this stack. In this model, there might be objects that resist this undoing,
keeping their history intact. This apparently small change means that the undoed, discarded history can have effects on the actual history;
this opens up a lot of space for interesting consequences, while still being a pretty natural & understandable model for time travel (we 
will see in the extra section that it holds some extra surprises when trying to formalize it!)

Here are some games with this model of time travel:

-----

### [Braid - World 3](https://store.steampowered.com/app/26800/Braid/) by Jon Blow

Braid's World 3 features green glowing objects that are immune to the [Glorified Undo](/time-genres/glorified-undo) introduced in World 2.
I can't write anything about Braid that hasn't been writen before; if you're reading a blog about time travel puzzle games, you've played
it already. Higly recommended.

![Braid - World 3](https://cdn.akamai.steamstatic.com/steam/apps/26800/0000007898.1920x1080.jpg)

-----

### [At the Hedges of Time](https://galactical.itch.io/at-the-hedges-of-time) by galactical

Great short sokoban about undo-resistant boxes. Memorable levels, beautiful graphics, and a neat ending make for a compelling game. The move
counter works very well with the time travel mechanic, making it more intuitive and creating an interesting possibility space. Highly recommended.

![At the Hedges of Time](https://img.itch.zone/aW1hZ2UvMTA1MDA0OC82MDA0NzYwLnBuZw==/original/dUVX8c.png)

-----

### [So broken](https://coreymartin.itch.io/sobroken) by Corey Martin

Very enjoyable puzzle game that takes standard sokoban and transforms it by making the player immune to undo. Levels are manageable and 
well designed. The addition of a 'Redo' button gives the player a lot of power, once they learn to think about to not overwrite key moves.
Highly recommended.

![So broken](https://img.itch.zone/aW1hZ2UvOTU4MDcvNDUyNDY0LnBuZw==/original/M3HSAv.png)

-----

<!-- pending: sig.null -->

## Variants & future work

The model as explained at the top of the page is good enough to play, create, and understand these games, but it's not as solid as it might seem.
Let's think about the perspective of an in-world inhabitant, whose memories aren't undo-immune. They see an undo-resistant object at some position.
An instant later, that object teleports somewhere else: unbeknownst to them, the player moved that object around and then undoed back to that instant.
In other words, the world line of undo-resistant objects is discontinous:
![Paradox](/assets/img/spicy-undo-paradox.gif){: .mx-auto.d-block :}
The player never sees the object jump around since by the time they get back to the discontinuity, the object's history will have been rewriten.
The most consistent solution is to add [a hierarchy of extra time dimensions](/time-genres/serialism) (after, the gif above has 2 time dimensions!)

However, there's another path: let's try removing the time dimension from these objects. That is, we will see these objects as immutable: they have
had and always will have the same position:
![Immutable](/assets/img/spicy-undo-immutable.gif){: .mx-auto.d-block :}
"Wait", you might say, "that object is clearly moving!". Well, from our priviledged outside-the-game perspective it is, but not in the in-game
universe: take a screenshot of that gif and you'll have a stationary object's full timeline. With this view, moving the object means creating
a whole new timeline: not only is the object over there now, it has always been over there for the in-game world inhabitants. The undo machine
isn't actually a machine for undoing history: it's a machine for travelling to alternate timelines in which the immutable objects 
are (and have been, and will be) in a different state.

This model has some very interesting consequences. These time-immune objects would have puzzling and mysterious properties, like floating in mid-air
when their support is removed. Let's say that some religion decides to worship one of these objects, building a temple around it (the object can't be
brought to an altar, so the altar must be built around the object!). In each timeline the object has a different position, so from our priviledged
outside-the-game perspective moving that object around would make the temple look like this:

![Green Relic](https://www.unite.ai/wp-content/uploads/2021/12/latent-space-explore-live-gan-manipulation.gif){: .mx-auto.d-block :}

Most of the standard Spicy Undo shenanigans, like a normal and an undo-resistant object overlapping, aren't really possible with this model.
This territory for time travel puzzle games is, as far as I know, unexplored. I'd love to see someone explore this space; if you do,
please contact me & I'll feature your game here!
