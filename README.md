# GERmulator
Altair 8800 Emulator written in GameMaker: Studio 1.4

Version 16

Adds SIO and Serial Terminal. Left clicking the SIO icon toggles the Serial Terminal Display.
SIO maps to ports 80h & 81h.

Serial Terminal supports:

  CR = Carriage Return. Moves cursor to beginning of line.
  
  LF = Line Feed. Moves cursor down one line.
  
  VT = Vertical Tab. Clear Screen.
  
Serial Monitor Supports: Help, Dump, Edit, Go (Execute) Commands.

Adds HEX file support for ROMS. Left clicking the ROM icon shows a file open dialog for a .HEX file to be read into the ROM. I didn't add write protect code to the ROM address space so it is possible to modify the ROM after power on. Power must be off to modify ROM.

I also found a couple of errors in the microcode.

Version 15

Adds CPU Display. Left clicking the CPU icon toggles the CPU Display on and off. The display can be scrolled up or down with the mouse wheel.
