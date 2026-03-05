# BLE Advert Data Structure
I am going to give each value a byte of data. Data structure listed here:
| Byte | Attribute | Notes |
|------|-----------|-------|
| 0-6 | Mandatory BLE junk | Need this stuff to function |
| 7-8 | Magic Number (0x5350) | This will be the pair of ID bytes that will be always the same. | 
| 9-10 | Protocol Version | This indicates what version of Tavarish a unit is running. |
| 11 | Domain ID | This ID is essentially for future tracking of other projects using this backend so they can intermingle without causing a ruckus. |
| 12-15 | Unique UID | This will be the user ID that will be given when a user registers with the future (undetermined) service this will tie into. |
| 16 | Face Shape | 0 = Circle, 1 = Square, etc... |
| 17 | Head Color | 256 colors will be enough. Period |
| 18 | Facial Features | This will allow for combinations of eyes and mouths, maybe noses if I get that detailed |
| 19 | Eye Color | Same as before, 256 colors |
| 20 | Background Color | If you can understand patterns you'll understand what the answer for this one is... |
| 21 | Hat/Hair | Fancy hats, no loot crates required. |
| 22 | Companion | Because sometimes you just need a little buddy. |

Given this structure, I will have enough space to be compatible with older BLE versions.