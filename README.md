

## Leet Editor, a.k.a. LeetEd

A sprite editor for terminal application.
ASCII Art, UTF8 Art & ANSI Art are supported.

* License: MIT
* Current status: alpha



## Install

Use Node Package Manager:

    npm install leeted -g



Then just run it, and have fun:

	leeted my-sprite



## Keys

Any regular key pressed is written down.

This is the list of special keys:

* CTRL-C: Quit
* CTRL-S: Save file
* Arrow: Move the cursor
* CTRL-Arrow: resize the sprite by moving the lower-right corner
* SHIFT-Arrow: resize the sprite by moving the upper-left corner
* ALT-Arrow: change the writing direction
* ALT-SPACE / ALT-SHIFT-SPACE: in place editing, do not move the cursor after writing a char
* F1: Next hint
* F5: Previous foreground color
* F6: Next foreground color
* F7: Previous background color
* F8: Next background color
* F9: Previous editor\'s background\'s background color
* F10: Next editor\'s background\'s background color
* ALT-Q: Previous editor\'s background\'s foreground color
* ALT-W: Next editor\'s background\'s foreground color
* ALT-E: Change the editor\'s background\'s character to the next typed character
* CTRL-SPACE: only put the currents editing attributes, without changing the character
* ALT-SPACE: 
* ALT-SHIFT-F: Fill with the current foreground color
* ALT-SHIFT-G: Fill with the current background color
* ALT-SHIFT-Y: Fill with the current style
* ALT-T: Toggle all transparencies
* ALT-F: Toggle foreground transparency
* ALT-G: Toggle background transparency
* ALT-Y: Toggle style transparency
* ALT-C: Toggle character transparency
* ALT-B: Toggle bold
* ALT-D: Toggle dim
* ALT-I: Toggle italic
* ALT-U: Toggle underline
* ALT-K: Toggle blink
* ALT-N: Toggle inverse
* ALT-H: Toggle hidden
* ALT-S: Toggle strike

