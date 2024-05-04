---
layout: post
title:  "Revamping My Music Library"
date:   2023-01-11
tags: [music, tech]
---

Embracing a New Music Organizer

As I set out to bring order to my music library, I knew I needed to make a change. Having used iTunes for the past 13 years, I decided it was time to switch to a more specialised software – Traktor, the same platform I use for my DJ performances.

Untangling the Chaos

The transition, however, was not without its challenges. My music collection, consolidated by iTunes, had all the files named simply by their titles, with no artist information. The folder structure also left much to be desired. I knew I needed to take a more hands-on approach to reorganise my library.

How the files looked when they were sorted by iTunes:
![iTunes Library](/images/library_itunes.png)

To tackle this daunting task, I turned to Python and wrote a script that would go through my entire music collection, renaming the files to include the artist's name and organising them into a more logical folder structure. This not only streamlined the process but also ensured consistency across my library.

How the files looked when organised by my script:
![New Library](/images/library_now.png)

I named my script MdCR (aka Music deConsolidator) and published it to my [GitHub](https://github.com/matis-io/MdCR){:target="\_blank"} page where you can see it in action and read more about it.

Integrating with Traktor

With the files now properly named and organised, I pointed Traktor to my newly created music folder and let it import and analyse the collection. I also had to export individual playlists from iTunes and import them into Traktor, but this step was relatively straightforward.
To take my library management to the next level, I decided to run my music through a free and open-source software called MusicBrainz Picard. This tool helped me fill in any missing ID3 data, ensuring that each track had comprehensive metadata, making it easier to navigate and manage my collection.

Now all that was left was to start playing some music!

![TraktorDJ](/images/traktorDJ.png)