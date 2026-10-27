# My First Game

### Introduction @unplugged

Learn how to make a sprite move around the screen!

### Step 1

Add a sprite to the screen.

```blocks
let mySprite = sprites.create(img`
    . . . .
    . 2 2 .
    . 2 2 .
    . . . .
`, SpriteKind.Player)
```

### Step 2

Make the sprite move with the arrow keys.

```blocks
controller.moveSprite(mySprite)
```

### Step 3 @fullscreen

Great job! Try changing the speed.
