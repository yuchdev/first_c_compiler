# PDP-11/UNIX C Compiler by Dennis Richie (1972)

The earliest versions of the very first C compiler, known to be written by Dennis Richie himself.

Directory **last1120c** is a saved state of the compiler just before the migration from the PDP-11/20, which did not have multiply or divide instructions, but instead provided a separate, optional unit that did these operations (and also shifts) by storing the operands into memory locations.

The second directory, **prestruct-c** is a copy of the compiler just before adding structures functionality. 

It's not possible to compile it nowadays using any modern C compilers like GCC, however, in theory there's a probability of success compiling it using PDP-11/UNIX emulator. 

Source: [Very early C compilers and language](https://www.bell-labs.com/usr/dmr/www/primevalC.html)

[PDP-11/UNIX Emulator](http://pdp11.aiju.de/)
