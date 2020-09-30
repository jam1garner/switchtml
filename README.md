# SwitcHTML

A set of CSS stylings and HTML setups to replicate various parts of the system switch UI. Designed primarily with the usecase of being used on the Switch's Webkit-based browser.

### What does this repo contain

* `dialog-yes-no` - A yes/no dialog, with functional buttons. Buttons redirect to localhost as that is how the Switch browser handles callbacks/return responses.
* `dialog-ok-cancel` - An OK/Cancel dialog, similar to the yes/no dialog.

### Missing font

The switch system font is, obviously, copyrighted and thus cannot be included. It can, however, be extracted from title id `0100000000000811` on the switch.

The expected fonts are:

* `nintendo_udsg-r_std_003.ttf` - the standard system UI font. A modified version of UD Shin Go NT.
