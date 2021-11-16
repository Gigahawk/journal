---
created: 2021-11-16T05:31:12-08:00
modified: 2021-11-16T05:39:42-08:00
---

# LitePog UX

1. User powers up device
1. LitePog displays idle animation
    - Buttons light up when pressed
    - LED strip ideally displays a rainbow cycling effect (power permitting)
    - Continue once both buttons are held down for 1 s
1. Game count down starts
    - show red pixels in the middle, grow outwards at regular interval.
    - once countdown ends, all red pixels turn green
1. First player to produce rising edge (let go of button) starts the game.
    - Blue Ball appears, and travels away from player who started the game
1. Player must produce a falling edge when the ball reaches their side (button led lights up) to keep the rally going
1. If a player fails to return the ball, display game end animation
    - winner side blinks green for a few seconds, loser side blinks red
1. Return to idle animation
