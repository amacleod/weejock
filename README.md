weejock
=======

Wee Jock is a 4x5 wireless keypad with smaller than normal key spacing.
The name "Wee Jock" is a reference to Terry Pratchett's [The Wee Free Men][weefreemen], and is meant to convey that this keypad is more closely spaced than normal MX spacing.

![wee jock schematic](weejock.svg "Wee Jock Schematic")

TODO:
 - put traces closer together so there is no need for ground plane vias in islands
 - try the controller on the right to see if that makes routing easier
 - try row2col instead of col2row
 - neater silkscreen:
   - no need for big squares on the key positions
   - move the K1, K2, and so on labels nearer the center of the key position
   - cleaner, simpler diode indicators
   - less stuff around the XIAO?
 - make a custom footprint for the XIAO with the neat oval pads
 - find a nice way to print a 2D color render of the PCB for inclusion in this README

[weefreemen]: https://en.wikipedia.org/wiki/The_Wee_Free_Men "The Wee Free Men"
