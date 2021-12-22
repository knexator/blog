---
title: Puzzles About Time Travel
subtitle: Subgenres of the subgenre
tags: [time travel, puzzles, meta]
---

Inpired by [Joel's blog on Snake Puzzle Games](https://joelthefox.github.io/2019-08-21-Snake-Puzzle-Games/), an encyclopedic collection
of all things snake-puzzle-related, I'm starting a blog for time travel games. Time travel is a pandora's box of paradoxes; each author
must choose how to solve or sidestep them. Each set of choices leads to a different model of Time; each model has its own interesting
consequences, and it's my belief that puzzle games are the best way to explore them.

My main goal with this blog is to properly categorize all the different flavors of time travel and how they are used in puzzles.
This blog will try to be an exhaustive list of all these flavors, but it wont try to be an exhaustive list of time travel puzzle games
(or creating & maintaining it would be a full time job). In no particular order, these are all the unique models I've found so far:

{% for time_genre in site.time_genres %}
 - [{{ time_genre.title}}]({{ time_genre.url }}) - {{ time_genre.subtitle }}
{%- endfor -%}