---
task: 'TWO'
title: 'CHASE THE MOUSE'
permalink: chase/:collection/mouse-chase
layout: task
activity: chase
activities:
- image: images/chase/t2-01.png
  steps:
  - Let's make the mouse run!
  - Every time the cat touches the rat, the rat will move to a random position.
- image: none
  steps:
  - Here's a hint! Attach a <bl>forever</bl> loop to <bl>when green flag clicked</bl>.
  - Add <bl>if < > then</bl> in it to check if the cat is touching the mouse anytime.
- image: none
  steps:
  - Use <bl>touching [Mouse v] ?</bl> as your operator.
  - When it touches the mouse, use <bl>broadcast [chase v]</bl> message
- image: none
  steps:
  - Now, to tell the mouse to run away, use <bl>When I receive [chase v]</bl>
  - Use <bl>pick random () to ()</bl> with <bl>go to x:() y:()</bl> to make it run away to a random position.
  - Make sure the mouse can run the farthest it can get within the stage.
  - To do this, what is the minimum and the maximum x and y coordinates the mouse can reach?
- image: images/chase/t2-03.gif
  steps:
  - Once you're done, click the green flag and chase the mouse.
  - The mouse should be able to run away!
---
