# pong
A web-based single player version of Pong.

### decisions to be made
- use arrow keys or mouse cursor? arrow keys means fixed speed of paddle whereas cursor opens up much faster potential play. Maybe implement both and give option?


### key gameplay features
- ball collision with walls and paddles
- point detection when ball reaches either end
- keep track of score
- a "reset" function for resetting ball after point is scored
- a "masterReset" function for starting game over again without refreshing browser
- "end game" condition when either score reaches ScoreMax
- variable scoreMax
- variable ballSpeed (increase over time and plateau at some Vmax)
- keep track of an internal "clock" of sorts for use by speed calculations
- variable "computer" difficulty. I can already think of 2 algorithms that would result in an "easy" and "hard" mode. Maybe also an "impossible" mode where the computer plays perfectly. Or maybe a slider for continuously variable computer paddle speed.


### first steps
- design HTML page
- include all necessary visible elements (buttons, sliders, etc)
- design game elements (paddles, ball, score displays)
