---
title: 'TASK THREE : ADD A SCORE'
permalink: chase/:collection/add-score
layout: task
activity: chase
activities:
- image: none
  steps:
  - Let's add a bit more fun to the chase!
  - Add a variable called <bl>(score)</bl>.
  - Make it available for all sprites.
- image: none
  steps:
  - Now, every time the cat touches the mouse, the <bl>(score)</bl> should increase by 1.
  - Use <bl>change [score v] by (1)</bl> and add it after <bl>broadcast [chase v]</bl>.
- image: none
  steps:
  - Of course, don't forget to reset in when the green flag is clicked.
  - Use <bl>set [score v] to (0)</bl> to reset and attach it to <bl>when green flag clicked</bl>.
  - Reseting the variables are very important especially in game apps.
---
