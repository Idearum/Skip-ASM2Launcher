These are the actions that are rebindable through ASM2Launcher.exe and stored in input.dat. See further down for a table of all known keybindings.

The format of input.dat is the following:
logicInput, isPositive, keybinding, holdAlt, holdCtrl, holdShift

Notes:
* The modifier keys refer to the left ones on the keyboard, meaning Left Alt/Ctrl/Shift
* In the below "Li,iP" refers to "LogicInput,isPositive"
* Think gamepad axis, so X+/X- etc in regards to the "isPostive" parameter.


How to rebind the keys:
1. Locate the action you want to rebind in the below tables, by searching either on a) the Li,iP (eg. "0,False" for "move left") or b) the current keybinding (eg. "Keyboard.10" for actions bound to "a").
2. Use the keybindings table further down below to locate the wanted keycode for the new key.
3. Change holdAlt,holdCtrl,holdShift at the end of the row (normally "False,False,False") in input.dat to true or false depending on wanted keybind.


Examples:
0,False,Keyboard.10,False,False,False - Move left using A
0,True,Keyboard.13,False,False,False - Move right using D
0,False,Keyboard.16,False,True,False - Move left using Ctrl+G
0,True,Keyboard.22,False,False,True - Move right using Shift+M

-----------------------------------------------------------------------------------------------------------

Rebindable Actions

| Navigation
|-------------------------------------|
| Li,iP     | Action                  | 
|-------------------------------------|
| 0,False   | Move Left               | 
| 0,True    | Move Right              |
| 1,True    | Move Backwards          |
| 1,False   | Move Forward            |
| 4,True    | Jump                    |
| 5,True    | WebSwing (right hand)   |
| 6,True    | WebSwing (left hand)    |
| 9,True    | Toggle wall crawl       |
| 10,True   | Interact                |
| 22,True   | Reset camera            |
| 95,True   | Peter Parker run        |
| 96,True   | Spider-Sense            |
| 99,True   | Crawl                   |
|-------------------------------------|

| Combat
|-------------------------------------|
| Li,iP     | Action                  | 
|-------------------------------------|
| 7,True    | WebShot                 |
| 15,False  | WebRush select left     |
| 15,True   | WebRush select right    |
| 16,False  | WebRush select down     |
| 16,True   | WebRush select up       |
| 18,True   | WebRush                 |
| 19,True   | Takedown                |
| 38,True   | Attack                  |
| 39,True   | Dodge attack            |
| 41,True   | Web Pull                |
| 48,True   | Heal                    |
|-------------------------------------|

| HUD
|-------------------------------------|
| Li,iP     | Action                  | 
|-------------------------------------|
| 24,True   | Photo mode              |
| 27,True   | Take photo              |
| 30,True   | Photo zoom out          |
| 30,False  | Photo zoom in           |
| 32,True   | Photo zoom reset        |
| 51,True   | Start                   |
| 52,True   | Skip movie              |
| 54,True   | Skip cutscene           |
| 61,False  | Menu scroll Left        |
| 61,True   | Menu scroll Right       |
| 62,True   | Menu scroll Down        |
| 62,False  | Menu scroll Up          |
| 63,True   | Menu select             |
| 64,True   | Back in menu            |
| 68,True   | Cellphone previous page |
| 69,True   | Cellphone next page     |
| 72,True   | Menu option 1           |
| 73,True   | Menu option 2           |
| 76,False  | Move the map left       |
| 76,True   | Move the map right      |
| 77,True   | Move the map down       |
| 77,False  | Move the map up         |
| 78,True   | Center on player        |
| 90,True   | Dialog Left choice      |
| 91,True   | Dialog Right choice     |
| 92,True   | Dialog Up choice        |
| 93,True   | Dialog Down choice      |
| 67,True   | Open cellphone          |
|-------------------------------------|


-----------------------------------------------------------------------------------------------------------

Keybindings

|-------------|----------------------------|
| KB+M_Input  | Key                        |
|-------------|----------------------------|
| (none)      | None                       |
| Keyboard.0  | 0                          |
| Keyboard.1  | 1                          |
| Keyboard.2  | 2                          |
| Keyboard.3  | 3                          |
| Keyboard.4  | 4                          |
| Keyboard.5  | 5                          |
| Keyboard.6  | 6                          |
| Keyboard.7  | 7                          |
| Keyboard.8  | 8                          |
| Keyboard.9  | 9                          |
| Keyboard.10 | a                          |
| Keyboard.11 | b                          |
| Keyboard.12 | c                          |
| Keyboard.13 | d                          |
| Keyboard.14 | e                          |
| Keyboard.15 | f                          |
| Keyboard.16 | g                          |
| Keyboard.17 | h                          |
| Keyboard.18 | i                          |
| Keyboard.19 | j                          |
| Keyboard.20 | k                          |
| Keyboard.21 | l                          |
| Keyboard.22 | m                          |
| Keyboard.23 | n                          |
| Keyboard.24 | o                          |
| Keyboard.25 | p                          |
| Keyboard.26 | q                          |
| Keyboard.27 | r                          |
| Keyboard.28 | s                          |
| Keyboard.29 | t                          |
| Keyboard.30 | u                          |
| Keyboard.31 | v                          |
| Keyboard.32 | w                          |
| Keyboard.33 | x                          |
| Keyboard.34 | y                          |
| Keyboard.35 | z                          |
| Keyboard.36 | F1                         |
| Keyboard.37 | F2                         |
| Keyboard.38 | F3                         |
| Keyboard.39 | F4                         |
| Keyboard.40 | F5                         |
| Keyboard.41 | F6                         |
| Keyboard.42 | F7                         |
| Keyboard.43 | F8                         |
| Keyboard.44 | F9                         |
| Keyboard.45 | F10                        |
| Keyboard.46 | F11                        |
| Keyboard.47 | F12                        |
| Keyboard.48 | Left                       |
| Keyboard.49 | Right                      |
| Keyboard.50 | Up                         |
| Keyboard.51 | Down                       |
| Keyboard.52 | Space                      |
| Keyboard.53 | Enter                      |
| Keyboard.54 | Escape                     |
| Keyboard.55 | Tab                        |
| Keyboard.56 | Left Shift                 |
| Keyboard.57 | Backspace                  |
| Keyboard.58 | Plus/Add (+)               |
| Keyboard.59 | Minus/Substract (-)        |
| Keyboard.60 |                            |
| Keyboard.61 |                            |
| Keyboard.62 |                            |
| Keyboard.63 |                            |
| Keyboard.64 |                            |
| Keyboard.65 |                            |
| Keyboard.66 |                            |
| Keyboard.67 |                            |
| Keyboard.68 |                            |
| Keyboard.69 |                            |
| Keyboard.70 |                            |
| Keyboard.71 |                            |
| Keyboard.72 |                            |
| Keyboard.73 |                            |
| Keyboard.74 |                            |
| Keyboard.75 |                            |
| Keyboard.76 |                            |
| Keyboard.77 | Insert                     |
| Keyboard.78 | Delete                     |
| Keyboard.79 | Page Up                    |
| Keyboard.80 | Page Down                  |
| Keyboard.81 | Home                       |
| Keyboard.82 | End                        |
| Keyboard.83 | Numpad /                   |
| Keyboard.84 | Numpad *                   |
| Keyboard.85 | Numpad -                   |
| Keyboard.86 | Numpad +                   |
| Keyboard.87 | Numpad .                   |
| Keyboard.88 | Numpad Enter               |
| Keyboard.89 | Numpad 0                   |
| Keyboard.90 | Numpad 1                   |
| Keyboard.91 | Numpad 2                   |
| Keyboard.92 | Numpad 3                   |
| Keyboard.93 | Numpad 4                   |
| Keyboard.94 | Numpad 5                   |
| Keyboard.95 | Numpad 6                   |
| Keyboard.96 | Numpad 7                   |
| Keyboard.97 | Numpad 8                   |
| Keyboard.98 | Numpad 9                   |
| Mouse.0     | Mouse Left                 |
| Mouse.1     | Mouse Middle (Mouse Wheel) |
| Mouse.2     | Mouse Right                |
| Mouse.3     | Mouse X Axis               |
| Mouse.4     | Mouse Y Axis               |
| Mouse.5     | Mouse Z Axis               |
| Mouse.6     | Mouse Button 4             |
| Mouse.7     | Mouse Button 5             |
| Mouse.8     | Mouse Button 6             |
| Mouse.9     | Mouse Button 7             |
| Mouse.10    | Mouse Button 8             |
|-------------|----------------------------|


-----------------------------------------------------------------------------------------------------------
