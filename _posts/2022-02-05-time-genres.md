---
title: Puzzles About Time Travel
subtitle: Subgenres of the subgenre
tags: [time travel, puzzles, meta]
---

Inspired by [Joel's blog on Snake Puzzle Games](https://joelthefox.github.io/2019-08-21-Snake-Puzzle-Games/), an encyclopedic collection
of all things snake-puzzle-related, I'm starting a blog for time travel games. Time travel is a Pandora's box of paradoxes; each author
must choose how to solve or sidestep them. Each set of choices leads to a different model of Time; each model has its own interesting
consequences, and it's my belief that puzzle games are the best way to explore them.

My main goal with this blog is to properly categorize all the different flavors of time travel and how they are used in puzzles.
This blog will try to be an exhaustive list of all these flavors, but it won't try to be an exhaustive list of time travel puzzle games
(or creating & maintaining it would be a full time job). In no particular order, these are all the unique models I've found so far:

{% capture time_genre_names %}
glorified-undo
spicy-undo
serialism
closed-timelike-curve
standard
past-clones
fake-causal-loop
past-and-future
tenet
multiverse-time-travel
linear-time
slow-down-time
2d-time
{% endcapture %}
{% assign time_genre_names = time_genre_names | strip | newline_to_br | strip_newlines | split: "<br />" %}

{% assign done_time_genres = "" | split: ',' %}
{% assign pending_time_genres = site.time_genres %}
{% for cur_name in time_genre_names %}
  {% assign cur_url = cur_name | prepend: "/time-genres/" | append: "/" %}
  {% assign cur_time_genre = site.time_genres | where: "url", cur_url | first %}
  {% assign done_time_genres = done_time_genres | push: cur_time_genre %}
  {% assign pending_time_genres = pending_time_genres | where_exp: "item", "item.url != cur_url" %}
{% endfor %}

{% for time_genre in done_time_genres %}
  - [{{ time_genre.title}}]({{ time_genre.url }}) - {{ time_genre.subtitle }}
{%- endfor -%}

{% for time_genre in pending_time_genres %}
  - (WIP) [{{ time_genre.title}}]({{ time_genre.url }}) - {{ time_genre.subtitle }}
{%- endfor -%} <!-- -->

-----

Here's all the games listed on those articles:
 - [Braid - World 3](/time-genres/spicy-undo#braid-world-3)
 - [At the Hedges of Time](/time-genres/spicy-undo#at-the-hedges-of-time)
 - [So broken](/time-genres/spicy-undo#so-broken)
 - [Tres Undos](/time-genres/serialism#tres-undos)
 - [Time Conundrum](/time-genres/closed-timelike-curve#time-conundrum)
 - [Vision Soft Reset](/time-genres/standard#vision-soft-reset)
 - [Too Many Daves](/time-genres/standard#too-many-daves)
 - [The Company of Myself](/time-genres/past-clones#the-company-of-myself)
 - [Braid - World 5](/time-genres/past-clones#braid-world-5)
 - [The Misadventures of P.B. Winterbottom](/time-genres/past-clones#some-other-games)
 - [Time Master](/time-genres/past-clones#some-other-games)
 - [Chronotron](/time-genres/past-clones#some-other-games)
 - [Cursor*10](/time-genres/past-clones#some-other-games)
 - [The Talos Principle](/time-genres/past-clones#some-other-games)
 - [Holosaur](/time-genres/past-clones#some-other-games)
 - [Induction](/time-genres/fake-causal-loop#induction)
 - [Block Pushing Puzzle Game But With Time Travel](/time-genres/fake-causal-loop#block-pushing-puzzle-game-but-you-can-time-travel)
 - [Portal Reloaded](/time-genres/past-and-future#portal-reloaded)
 - [Day of the Tentacle](/time-genres/past-and-future#day-of-the-tentacle)
 - [Chiasm](/time-genres/tenet#chiasm)
 - [5D Chess With Multiverse Time Travel](/time-genres/multiverse-time-travel#5d-chess-with-multiverse-time-travel)
 - [400 Years](/time-genres/linear-time#400-years)
 - [Velocity Raptor](/time-genres/linear-time#velocity-raptor)
 - [A Slower Speed of Light](/time-genres/linear-time#velocity-raptor)
 - [Braid - World 6](/time-genres/slow-down-time#braid-world-6)
 - [Timespinner](/time-genres/slow-down-time#timespinner)

-----

And here's my TODO list:
 - [Relash](https://store.steampowered.com/app/1713260/Relash/)
 - [Sig.NULL](https://store.steampowered.com/app/501930/SigNULL/)
 - [Causality](https://store.steampowered.com/app/559930/Causality/)
 - [Z-Time](https://www.youtube.com/watch?v=ONOc7IND58w)
 - [Thanks for Playing](https://www.youtube.com/watch?v=P3yvqo5mHnw)
 - [Save Scummer](http://www.zincland.com/7drl/savescummer/)
 - [Minit](https://store.steampowered.com/app/609490/Minit/)
 - [DROD: The Second Sky](https://store.steampowered.com/app/351320/DROD_The_Second_Sky/)
 