Minigame 2 Devlog

1. Describe a bug you encountered and how you fixed it.

I had a problem with the chest on the second floor. My spell could not hit the chest after I changed its layer. I checked the settings in Unity and changed the chest’s GameObject Layer to Layer 2. Then I tested the game again. The spell worked and the chest could take damage.

2. Explain this line of code: _spriteRenderer.color = new Color(r, 0.2f, 0.2f);

This line changes the color of the chest. The value r controls the red color. The two 0.2f values control green and blue. The dot (.) is used to access a property of an object. In this example, .color accesses the color of _spriteRenderer. The word new creates a new Color value.