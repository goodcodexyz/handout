---
layout: task
title: "TASK FOUR : MAKE YOUR HERO MOVE AROUND"
permalink: "move-hero"
activities:
  - image: "images/t4-01.png"
    steps:
      [
        "Remove Forever and Wait blocks.",
        "Add a Move block to make it move while it is animating.",
        "Add a Right Arrow Key Press event block to make your character move when you press the right arrow key.",
        "Press the right arrow key and see what happens."
      ]
  - image: "images/t4-02.png"
    steps:
      [
        "Make another script for the other direction.",
        "Add the Left Key Press event block.",
        "Add Move and Next Costume blocks.",
        "Press the left key and see what happens."

      ]
  - image: "images/t4-03.png"
    steps:
      [
        "If you notice, your character doesn't face left.",
        "To fix this, add Point in Direction block.",
        "Change the value to -90.",
        "To make it rotate properly, add Set Rotation Style block with 'left-right' as value.",
        "Try out the left key again and see what happens."
      ]
  - image: "images/t4-04.png"
    steps:
      [
        "Press the right arrow key and notice the difference in your character's reaction.",
        "Add a Point in Direction to the Right Key Press script",
        "This will make your character face right when pressing the right key.",
        "Try moving your character around with the left and right keys.",
      ]
  - image: "images/t4-05.png"
    steps:
      [
        "Try out this motion code blocks and see how your hero moves.",
        "Attach a different Key Press code block for each Motion block"
      ]
---
<div class="content-info">
  <img class="info-image" src="{{site.baseurl}}/images/coordinates.png" />
  <div class="info-title"> The Coordinate System </div>
  <div class="info-text">
    Notice the X and Y values.<br>
    These state the position of your sprite in the stage.<br>
    If X and Y are 0, the sprite is at the center.<br>
  </div>
</div>
