# Chip-8-Phython
A Chip-8 Emulator Made In Pure python
# Info
The CHIP-8 system uses a hex keypad for entry, and a 64x32 monochrome screen for output. There is also facility for producing a beep as sound output, although this hasn't been implemented.

In this emulator the hex keypad which originally had the layout
123C
456D
789E
A0BF
is simulated by using the keys
1234
QWER
ASDF
ZXCV
(this is fairly standard in CHIP-8 emulators).

There are several other shortcut keys:

The + and - keys speed up and slow down the emulation. By default the CPU speed is 10 cycles per 60Hz tick (for a whole 600 instructions per second!)
The P key pauses/unpauses the emulation.
Escape resets the currently loaded program
Backspace performs a 'soft' reset (clear registers but not memory)
# Games
Blitz is a 'bomber' game. Use 'W' to drop bombs. Clear the screen before you hit the buildings.
Opcode Test is not particularly exciting, but tests that all the CHIP-8 machine code instructions are being emulated correctly.
Pong is pong! Player 1 uses 1Q to move up and down. Player 2 uses 4R to do the same.
Tetris is Tetris! WE moves left/right. Q rotates. A drops.
UFO is a shooting gallery game. Use QWE to fire left/ahead/right. You score if you hit one of the moving objects.
Worm is a snake game. 2QSE move up/left/down/right. Sometimes a 'fruit' will fail to appear - I haven't been able to figure out if that's a bug in my emulation or the game.
