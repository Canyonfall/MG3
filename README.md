# MG3
## Devlog
#### 1. What are the default values for floats, ints, bools, and strings? To find out, try adding one variable of each type as a member variable to the Timer class, and see what default value for each variable shows up in the Inspector.
Float: 0.0
Int: 0
Bool: false
String: ""

#### 2. How does the Update method get called- is your code supposed to call it in this assignment, or does it get called some other way?
The Update() method is automatically called by Unity every frame while the script is enabled and its GameObject is active. We do not need to call it ourselves.

#### 3. Explain how either the KickWeapon or TimerText class use the timer. Mention the Update() method.
The TimerText class uses the timer to keep track of how much time is left in the game. The Timer class's Update() method decreases the time every frame using Time.deltaTime. The TimerText class's Update() method checks if the timer has finished using IsFinished(). If the time runs out, it calls GameOver(). It also updates the text on the screen to show the remaining time.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
