# Welcome to Emoji Rain

## [Chapter 1: Adding Our First Emoji](https://glitch.com/edit/#!/remix/emoji-rain-1)

Add your first Emoji using a `<span>` HTML Tag.

## [Chapter 2: Making the Emojis Bigger](https://glitch.com/edit/#!/remix/emoji-rain-2)

Use the CSS Style `font-size` to make all `<span>` tags bigger (350% is great) and give them a relative position so they can move down the page.

## [Chapter 3: Move the first Emoji](https://glitch.com/edit/#!/remix/emoji-rain-3)

Query the `DOM` with Javascript to select the first Emoji and change the `style` property to move it down. Practice this in your browser's console.

## [Chapter 4: Build a moveEmoji function](https://glitch.com/edit/#!/remix/emoji-rain-4)

Build a `moveEmoji` function in Javascript that accepts an argument of an Emoji `DOM object and moves it down a few pixels.

## [Chapter 5: Move all the Emojis](https://glitch.com/edit/#!/remix/emoji-rain-5)

Add as many emojis as you want to the page and in your Javascript, select them all and loop through the collection of emojis, passing each to the `moveEmoji` function.

## [Chapter 6: Randomize the drop of the Emoji](https://glitch.com/edit/#!/remix/emoji-rain-6)

With `Math.floor(Math.random())` and if you need, `parseInt`, move the emoji down a random amount of pixels from its current position.

## [Chapter 7: Delay the drop of the Emoji](https://glitch.com/edit/#!/remix/emoji-rain-7)

Use `setTimeout` to delay the drop of the Emoji.

## [Chapter 8: Keep dropping the Emoji](https://glitch.com/edit/#!/remix/emoji-rain-8)

Call `moveEmoji` recursively from within `moveEmoji` to create a loop that will continuously move the emojis down the page.

## [Chapter 9: Restart the drop from the top of the screen](https://glitch.com/edit/#!/remix/emoji-rain-9)

Check the position of the emoji and move it back to the top if it is going to drop below the page fold.