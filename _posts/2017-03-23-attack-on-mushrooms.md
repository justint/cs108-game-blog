---
layout: post
title: "Attack on Mushrooms"
subtitle: "On the process of prototyping a game in GameMaker"
date: 2017-03-23 22:00:00
published: true
---

![GameMaker](/images/gamemaker.png){: .center-image }

In the past week, I've co-developed a game prototype, *Attack on Mushrooms*, using the YoYo Games' GameMaker Studio software. As the programmer and producer, my role has been writing the code that enables the functionality of the game, as well as communicate our game's development progress and goals to our big cheese.

Attack on Mushrooms, playable version 0.0001 - [download (exe)](/attack-on-mushrooms.exe) (Windows only)

The game development process has been very iterative; given this is my first time using GameMaker and building an entire game from scratch, I performed a lot of trial and error to get things working the way I wanted them to. Google was a big factor in this too - being able to search and find what I needed was true power.

It all started out with me attempting to tackle the platforming mechanic - how do I make a moveable player? How do I add collisions? Gravity? Jumps? *Double* jumps? Whether the answer was in the form of a YouTube video, tutorial on a blog, or a mix of both, I got my questions answered and my code written.

The art for the prototype was done by Oscar, who crafted a main character sprite sheet and animations for the mushrooms. After the two of us had outlined what our game was going to be about, he went ahead with sprite creation while I worked on my portion. We set up a Google Drive to share media, and I set up a GitHub repository to let him download and try any updates I made to the game.

Our game really isn't fleshed out yet at this point, what we've made is essentially not a game but just a platforming simulator. Until we add an end goal and challenges, my main questions to players at this point is: **what are your thoughts on the controls?** I spent a decent amount of time ensuring the jumps/moving around felt natural, so that's where the question stems from.

In response to our comments from the first playable post we made in Canvas:

    My only wish is to have jump be bound to the space bar instead of up

    Like the design. The controls are decent but some sort of start screen with a "how to" play would be helpful. Seems like a good start.

I agree with this, and will look into changing it. Plus we need an info blurb at the beginning about controls.

    No goal at this point, but good level design and I like the sprite for your character too. Add walls so that you don't fall off the level and have to restart the game. Keep developing and it'll be a good game!

Yes, currently our game has walls around the side but aren't quite high enough to keep players from jumping out - will fix this design in our final version.

    Not much of programming or game has been implemented. I liked the player sprite you have, looks kind of funky but does not match with the very plain and basic environment. Maybe you can try making the environment funky to match the theme.

Agreed, currently only the player has any custom sprite. The rest is just black squares for floors/walls.

    The jumping felt nice.  That was all there really is so far.  I wouldn't be against incorporating the smooth feel of the character movement into the main mechanics of the game.

This comment brings up a good point about the "floatiness" of our current physics implementation, perhaps our platforms can be designed to positively augment the player physics.

    I see the beginnings of a platformer, and it's coming along. I like the inclusion of a wall jump. My suggestion would be to make the platforms more grid like, so I could tell what I could jump over and what I couldn't jump over.

Our game doesn't have a wall jump but a double jump, and I see the reason for asking for a grid. As of now the player is sort of at a loss for how far they *can* jump, so maybe our game can incorporate a training session to teach the player the game physics.
