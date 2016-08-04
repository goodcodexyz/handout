---
title: 'TASK TWO: FIGHT THE MONSTER'
permalink: fight-monster
layout: task
activities:
- image: images/t2-01.gif
  steps:
  - It's time to fight brave hero!
  - Press Start on your game screen.
  - Try pressing Fight and see what happens.
- image: images/t2-02.gif
  steps:
  - Yes, nothing happens!
  - To fight the monster click on the Fight sprite in your Sprites panel.
  - Add an Event block, <bl>When this sprite clicked</bl>.
  - This makes the Fight button react to your commands.
- image: images/t2-03.svg
  steps:
  - Now we compare your level with the current stage of the game.
  - First, attach <bl>if () then</bl> to make a condition.
  - Use the Operator block <bl><[]=[]></bl> to compare two variables.
  - Now drag <bl>(level)</bl> and <bl>(stage)</bl> to the first and second slots respectively.
  - Your script should look like this.
- image: images/t2-04.svg
  steps:
  - Now, when the condition is true, we can fight the monster.
  - If we can fight the monster, this means the condition is true.
  - Add <bl>broadcast [attack v]</bl>.
  - If there's no 'attack' in the options, just select 'new message...'.
  - Level up by adding <bl>change [level v] by (1)</bl> under the Data blocks.
  - Finally add <bl>hide</bl> from Looks scripts to hide the button after clicking.
  - Here's the script so far.
- image: images/t2-05.gif
  steps:
  - We're about to defeat the evil monster!
  - Select the sprite named <b>next</b>
  - Add <bl>when I receive [attack v]
  - Attach <bl>show</bl> to the event block.
  - Now click <b>fight</b> to defeat the monster!
- image: images/t2-06.png
  steps:
  - Great job! You just defeated the first monster!
  - If you notice at the top left of your game screen, your level increased to 2!
  - To move on to the next stage, click Next on the game screen.
---

