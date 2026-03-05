# BLE Advert Data Structure
I am going to give each value a byte of data. Data structure listed here:
| Byte | Attribute | Notes |
|------|-----------|-------|
| 0-6 | Mandatory BLE junk | Need this stuff to function |
| 7-8 | Magic Number (0x5350) | This will be the pair of ID bytes that will be always the same. | 
| 9-10 | Protocol Version | This indicates what version of Tavarish a unit is running. |
| 11-14 | Unique UID | This will be the user ID that will be given when a user registers with the future (undetermined) service this will tie into. |
|  | Face Shape | 0 = Circle, 1 = Square, etc... |
|  | Head Color | 256 colors will be enough. Period |
|  | Facial Features | This will allow for combinations of eyes and mouths, maybe noses if I get that detailed |
|  | Eye Color | Same as before, 256 colors |
|  | Background Color | If you can understand patterns you'll understand what the answer for this one is... |
|  | Hat/Hair | Fancy hats, no loot crates required. |
|  | Companion | Because sometimes you just need a little buddy. |
