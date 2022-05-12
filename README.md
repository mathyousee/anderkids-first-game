# anderkids-first-game

makng a game with the kids for a hands-on-learning project

## Tooling

pico-8 fantasy console - that's it. It uses a Lua variant as the main programming language, includes a built in sprite and map editor, as well as a sound designer.

Much of the source .p8 file is editable in a text editor, however the sprites, map, and sound are encoded in the same file.

As an added bonus, I can export builds to HTML5 apps, which I'll try to pop into the /build folder.

## Project History

### v2

Kids were excited to get back at it. First thing we did was add another character (one for Dad). Babas. I did a good enough job, but I also kept it brief so the kids didn't get distracted.

Then we decided to add in a way to switch between players. We decided on adding markers to the map where the player can cross over it to swap to a new one. That worked fine for me, since adding in the logic for that was pretty straightforward (even if it was inefficient with sprite slots). 

For fun, we added a character swap sound effect, too!

Last task in the first session was they added another character. They're getting good with the sprite editor. This one is just a floating eye. E was thrilled.

Second session focused on some map updates, adding more items and expanding to more screens. Didn't expand too far, but added interest to the area.

With all of the additional items, we talked about keeping track of how many they've collected. I added a simple counter for flowers and apples slapped it at the top of the screen. I'm sure there's a more elegant way to code it but it's working nicely.

### v1

Started with the "Wander" demo that comes with pico-8 fantasy console. Let them get a sense for basic movement, then we talked about what they wanted to do. 

They wanted to pick flowers, so I walked through finding the sprite numbers for flower and the apple. Then we found the pickup code for the collect apple logic and repurposed it to collect flowers instead.

They decided it'd be more fun to collect both. We copied the code to collect apples and amended a copy to squish flowers. For some extra flare, we added a sprite for the squished flower (with stray petal) as well as a unique sound.

After "thorough testing" to ensure things were working, we did some map work, adding more apples and flowers.

Next the kids wanted to create their own characters. We cracked open the sprite editor and the kids grabbed some reference action figures (named Fire and Kuva). Both were pretty solid interpretations if you ask me.

We closed out with testing out with each of their player sprites. They have ideas for the next update...but that'll be another day.
