# raw_to_asm

This code converts an 8-bit signed raw audio stream into an assembly (.S) file, tagged as read only data. Outputs a data format compatible with the nintendo gameboy advance (data can be fed into the GBA's direct sound driver).

I borrowed most of this code from the grit image tool (by Cearn), and re-purposed the functions to work with audio streams instead of images.
