---
title: 'TASK FOUR : HERE COMES THE DOG'
permalink: chase/:collection/dog
layout: task
activity: chase
content-position: below
activities:
- image: images/chase/t4-01.gif
  steps:
  - Let's add a bit more challenge!
  - Every time the cat touches the mouse, the dog moves to a random spot as well.
- image: none
  steps:
  - This time, the cat won't be able to pass through the dog.
  - Use <bl>touching [Dog v] ?</bl> in an <bl>if < > then</bl> block.
  - If the cat touches the dog, make it move backwards by using <bl>move (-10) steps</bl>.
- image: none
  steps:
  - Finally, to make the game even more fun, add more dogs!
  - When the cat touches the mouse, check if the score reaches 10.
  - You can use the operator <bl>< (score) = [10] ></bl> in an <bl>if < > then</bl> block.
  - Insert <bl>create clone of [Dog v]</bl> to add another dog.
- image: images/chase/t4-05.gif
  steps:
  - Now when the dog starts as a clone, make it move to a random position.
  - Use <bl>When I start as a clone</bl> to the dog and make it move afterwards.
- image: none
  steps:
  - Congratulations! You've finished your Cat Chase game!
  - Go share your work to your friends!
  - If you want more challenge, click the link below.
---
{% include challenge.html challenge="chase" %}
{% include congrats.html %}
