---
layout: game-page
title: The Big Green Clean
permalink: /the-big-green-clean 
game-name: the-big-green-clean
---

## The Big Green Clean

The Big Green Clean is a game about who gets to live in places abandoned by others. You play as Hugh Mann, a goblin contractor who has just taken a job working for Sierra the Harpy, who has just recently purchased an abandoned castle tower in the area. However, there seems to be someone else currently living in the tower despite its abandoned state. 

The game was made in Phaser 3 and is currently available on my itch.io page [here](https://drslowpokephd.itch.io/the-big-green-clean).

The game was made as the final project for CMPM 120/ARTG 120 at UC Santa Cruz alongside my teammates Marc Anthony Cervantes, Johnny Choi, and Nanxiang Wang. I was the technical lead and lead programmer on the project. My job consisted of creating reusable code objects that would be used in the development of the game, as well as creating and deploying workflows for art asset implementation and playtesting. 

To help facilitate the playtesting process, I set up a Github Pages link that would automatically link to the latest build of the game posted to Github. This is a major advantage of working in Phaser over other game engines, as the time between pushing a new commit and getting a link into the hands of playtesters is near instantaneous, and at most takes a few minutes. Game physics are largely covered by Phaser's built-in Arcade Physics API, which provides a "good enough" simulation of 2D Kinematics for most arcade games. The one area that Phaser lacks in compared to other game engines is its UI, which is primitive at best. This was a challenge since I had to engineer a system that would create a dialogue box that would snap to characters and fit within the JSON Schema I wrote for dialogue implementation. It's simple, it works, and it can be expanded upon by replacing the filled in rectangle primitives with textures. 

One feature that I really wanted to see in the final product was JRPG-like scrolling text that would make it easier for the player to follow along with the text as it passes by. This would also be useful in emphasizing the character traits of whoever is speaking at the moment by playing a corresponding "talking" sound while the text is scrolling.


