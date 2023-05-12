Project Link: https://nichoda.github.io/CSC-2463-Assignments/JSAssignments/FinalProject/index.html

## Project Outline

Ghost Runner

- Graphics
  - A main character with animation using spritesheet
  - A ghost like enemy that changes direction based off which way it is moving
  - 4 game states with different text and backgrounds
  - The Playing game state will be a 2d side scrolling game, with platforms and a parallax scrolling background
- Audio
  - Each game state has custom made background music using Tone.js
    - Uses unique parameters to make it sound 8-bit like 
  - Each character action has a sound effect (From free website all under 3 seconds)
    - Running, jumping, and getting hit
- Physcial  
  - A joystick that allows the character to move back and forth as well as jump if pressed.
  - A led light that lights up if the player starts to run low on time
- Gameplay 
  - Player attempts to run through 2d course with obstacles such as death pits, ghost enemies, limited lives, and a timer.
  
---

## Description of the Project

This is a 2D platformer game similar to Mario. The goal is to reach the end of each level by jumping and using platforms while avoiding deadly pits and ghosts. Players can move using either the W, A, and D keys, a joystick and button, or a combination of both. Falling into a death trap results in immediate failure, but players have three chances when facing ghosts. There is also a time limit, and when it drops below 20 seconds, an Arduino LED activates to warn the player of low time. Your score is calculated based on how far you progress through the level, with bonus points awarded for completing the entire level. The more hearts and time remaining at the end of the level, the more bonus points you receive.

---

## Images of the Project

### Title State
![Title Image](./title.PNG)
### Gameplay State
![Gameplay Image](./Gameplay.PNG)
### Game Over State
![Game Over Image](./GameOver.PNG)
### You Win State
![You Win Image](./YouWin.PNG)

---

## Video Example of it Working

### Screen Gameplay:
https://www.youtube.com/watch?v=yLoTVKl_aMQ
### Gameplay showing working joystick:
https://example.com/video_example.png](https://www.youtube.com/watch?v=00Ni4RLKXig&ab_channel=NicholasDomingue

---

## Images That To Help Understand Work

### Plan
![Schematics Image](./setuo.PNG)

### Picture of Actual Wiring
![Schematics Image](./led.png)
---

## Thoughts About Future Development

I really enjoyed making this project. In the future if I ever work on it, I want to add music that sounds better. I would also like to add an option to somehow kill the ghost enemies for more points. I could also make multiple levels as different game states, with new enemies and unique music/sound affects. 

For an extreme challenge, adding some sort of backend and allowing for multiple people to play would be really cool.

---
