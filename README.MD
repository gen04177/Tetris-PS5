# Tetris Infinity (PS5)

This is a Tetris game developed in C using SDL2, designed to be played on a jailbroken PS5 (1.xx-5.xx).

## Prerequisites
- elfldr.elf
- shsrv.elf
- ftpsrv.elf

## How to Use
1. Send the elfldr.elf payload to port 9020.
2. Send the shsrv.elf payload to port 9021.
3. Send the ftpsrv.elf payload to port 9021.
4. Copy the tetris.elf payload to your PS5.
5. Execute `telnet [PS5-IP] 2323`.
6. Run the command, e.g., `hbldr /data/tetris.elf`

## Controls:
Arrows: move the pieces

Circle: rotate

Cross: hard drop

L1: pause music.

## Credits
- J. Tornblom - SDK
