---
layout: post
title: Boomerangers
description: A splitscreen FPS with a unique weapon.
---

![Key Art](https://img.itch.zone/aW1hZ2UvMTQ1OTY3OC84NTg3MzIyLnBuZw==/original/pXkMxy.png "Boomerangers")

[Itch.Io Link](https://kanomisu.itch.io/boomerangers){:target="_blank"}

### NOMINATED FOR BEST SECOND YEAR GAME AT GAMECON 2022 ###

Boomerangers is a fast paced head to head arena shooter where players fight using a unique to control boomerang. The boomerang is a complex but skillful weapon that is easy to learn and hard to master. Become the master of your weapon, and leave no place for your enemy to hide, even out of your sight!

My Role
------------

Boomerangers was a super complex title to create, we didn't even have a functional game engine for the first 4-5 months of game development. Building the technology along side the game was a difficult but satisfying challenge.

I was in charge of creating the main mechanic of the game, the boomerang. The original design had the boomerang fly towards the center of the player's view, but it made it impossible to effectively hit targets hiding behind cover. Part way through development, we switched to a model that had the boomerang fly towards a point in front of the player that would increase distance until it hits something or was commanded to return, when it would do the opposite. This allowed players to hit players in the back more effectively, which was rewarded with a damage bonus.

I also got to give level design a go, as I was not satisfied with the first level built for the game. It was built before we had the game in a playable state and was too big for what we actually needed. This new level was built and implemented in one night, and doubled the amount of content in the game. It took inspiration from Halo Combat Evolved, and forced players to move around the map more instead of staying in one safe space. The implementation of the physics engine caused issues, but the level was still successful!

I was also the lead techincal artist, and had the opportunity to create a graphical pipeline that effectively emulated the Playstation One. Complete with a lack of support subpixel vertecies, vertex lighting, affine texture mapping, fog, and a lower render resolution. Unfortunately, the assets for the game were created before these features were implemented, and the engine moved to a purely deferred rendering pipeline, resulting in many of the PS1 effects not being used in the final game.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/TOdEnRGOEmE?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

I did however get to put together this demo using the assets from Silent Hill 1 to recreate the game in my engine!