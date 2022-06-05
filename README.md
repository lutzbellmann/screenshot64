# screenshot64
Tool to make screenshots on the Commodore 64

This tool for the C64 is doing what it tells. It can make a copy of the Screen and save that to disk.
To start the tool write:
Load"screenshot",#D,1 , where #D is your drive number.
then "Run" on a C64 or C128 in C64 mode.

You are being asked for a filename. 
You can now fill the screen with the keyboard and use any PETSCII characters.
Use F7 to make a screenshot that is being saved to the drive, that the program has been loaded from. The tool will then exit.
Use F5 to make a screenshot; you can continue changing the screen and use F5 continouusly for a maximum of 9 screenshots.
If you press R/S & Restore the program will end, since all interrupts will be reset.

The filename you enter will be extended with an index (1,2,3,...) to identify the continouus screenshots.

Thats it. nothing much to it.
The VIC screen memory from $0400-$07e8 is saved into a PRG file.
The saved files include a location header. Every load in basic will result in displaying that screen.
You can use the files in your own programs.

Have fun!!!!
