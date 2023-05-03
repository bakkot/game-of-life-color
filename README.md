# Game of Life in Color

The game of life, but where cells have an additional "color" property which propagates to newly-born cells.

It's viewable [here](https://bakkot.github.io/game-of-life-color).

This was written entirely by GPT-4 in a single shot. The transcript of the conversation is included at [transcript.md](./transcript.md). I made no changes to the transcript except adding the `user`/`bot` markers. I wrote the scaffold HTML by hand and inserted a call to `randomizeGrid` in the second block of code it generated; everything else is written by the bot.

The first commit is the basic functionality. I added interactivity in subsequent commits by continuing the session asking it to add features. At one point there's a bug, which I tell it about and then it corrects.