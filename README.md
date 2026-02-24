# Tavarish
### товарищ - The Russian word for comrade or fellow traveller. 

## What is this project about?
This is a project to show people (mostly myself) that I can ship something without it becoming lost in a sea of my own ideas. In the end it will be something much more, but those ideas are for another time.

## Ok that doesn't say much, what is it going to be when it is done?
The idea is a convention badge sized device that will house a passive BLE chip that is constantly broadcasting a small packet with a unique id, and listening for other Tavarish units. It will be its own standalone device with a web interface for extra detail. Think StreetPass, but as a standalone thing.

## That sounds interesting, but are you going to finish it or is it going to rot on the vine like your other projects?
Well isn't that a bit rude of you to say? But yes I am really bad about completing projects on time or at all, hence the answer to your first question. That will have to be a question answered with time, but I have something on my side that I haven't had before... MEDICATION!

# Avatar Data Structure
I am going to give each value a byte of data. Data structure listed here:
| Byte | Attribute | Notes |
|------|-----------|-------|
| 0 | Face Shape | 0 = Circle, 1 = Square, etc... |
| 1 | Head Color | 256 colors will be enough. Period |
| 2 | Facial Features | This will allow for combinations of eyes and mouths, maybe noses if I get that detailed |
| 3 | Eye Color | Same as before, 256 colors |
| 4 | Background Color | If you can understand patterns you'll understand what the answer for this one is... |
| 5 | Hat/Hair | Fancy hats, no loot crates required. |
| 6 | Companion | Because sometimes you just need a little buddy. |
