# MG3
## Devlog
1. The default values for floats and ints are both 0; bools is an unchecked box, false; and string is an empty text box.

2. Unity will call this function for me so I only need to write Update() and the code inside it. Yes, it is supposed to be calles in this assignment by Unity, I don't need to call it myself.

3. KickWeapon calls and starts when the player kicks. The Timer's Update() counts down every frame, and KickWeapon's Update() checks IsFinished(). When the time runs out, it turns off the kick so the player won't keep kicking forever.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)