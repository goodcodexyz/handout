---
title: 'TASK THREE: GAME OVER'
permalink: game-over
layout: task
activities:
- image: images/t3-01.png
  steps:
  - Let's add a bit of a challenge!
  - Now you face a fork in the cave.
  - Let's be more adventurous for a bit.
  - Enter Stage 3!
- image: images/t3-02.png
  steps:
  - Woah a lion! If you try to fight it nothing will happen though.
  - This is because we didn't provide anything if the condition for fight is false
  - Let's edit your script to show a game over screen when the stage is too high for
    your level.
- image: images/t3-03.svg
  steps:
  - Click the <b>fight</b> sprite in the Sprites panel.
  - Change <bl>if <> then</bl> to <b>IF-THEN-ELSE</b> block.
  - Transfer the scripts to that new script block.
  - Inside the ELSE slot, add <bl>broadcast [defeat v]<bl>.
  - Add <bl>switch backdrop to [gameover v]</bl> under broadcast.
- image: images/t3-04.svg
  steps:
  - Add a new event block <bl>when I receive [defeat v]</bl> to <b>fight</b> sprite.
  - Attach <bl>hide</bl> to the event block to hide it.
- image: images/t3-05.gif
  steps:
  - Drag the script to each of the monsters to duplicate it to them.
  - Click on each of the monster and arrange the position of the sript
  - Make sure your scripts don't overlap each other. It's good to keep your code nice
    and tidy.
- image: images/t3-06.gif
  steps:
  - Drag the script on top of <b>return</b> and <b>title</b> sprites to duplicate
    the script.
  - Click <b>return</b> sprite in the Sprites panel and fix the arrangement of the
    script.
  - Click <b>Title</b> arrange the positioning as well.
  - Add <bl>clear</bl> to remove the title at the top center of the screen.
- image: images/t3-07.png
  steps:
  - For now, let's try to fight the lion and see what happens.
  - Oh no! Game over!
  - Relax, move on to the next task to see how to start the game again.
---

