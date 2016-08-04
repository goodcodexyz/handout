---
title: 'TASK FOUR : PLAY AGAIN'
permalink: play-again
layout: task
content-position: below
activities:
- image: images/t4-01.gif
  steps:
  - Make sure you are in the Game Over screen by getting defeated on purpose.
  - Right click on <b>start</b> sprite and duplicate.
  - Click on the new sprite named <b>start2</b>
  - Click on the little 'i' inside the blue circle on top of the sprite.
  - Rename the sprite to 'Play'.
  - Tick the show checkbox.
- image: images/t4-02.gif
  steps:
  - Reposition Play on the game stage.
  - Click and drag it to the center.
  - Click the costumes tab and select the Play costume.
- image: images/t4-03.svg
  steps:
  - Remove <bl>show</bl> from <bl>When green flag clicked</bl>.
  - Replace by attaching <bl>hide</bl>.
  - Change <bl>broadcast [cave-1 v]</bl> to <bl>broadcast [play v]</bl>
  - Remove all the other scripts that were copied.
- image: images/t4-04.svg
  steps:
  - Lastly, add <bl>when I receive [defeat v]</bl> to Play sprite.
  - Attach <bl>show</bl> to <bl>when I receive [defeat v]</bl>.
- image: images/t4-05.gif
  steps:
  - Finally! We can now play our Story Crafters game and defeat the dragon!
  - Play through the different stages. Make sure you're level is high enough to beat
    those monsters!
  - Way to go!
---

<div class="content-info -end">
  <div class="info-title -no-image">Congratulations!</div>
  <div class="info-text -no-image">
    You have finished Story Crafters!<br>
    Go publish your work to the
    <a class="content-link" href="https://scratch.mit.edu/" target="_blank">Scratch online community</a><br>
    and share it with your friends!
  </div>
</div>
