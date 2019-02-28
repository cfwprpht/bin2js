==============================
 Binary 2 JavaScript
==============================

* Fixed Bug in Format 3 output. Should be 'var payload = ['. Credits @Leeful

* Fixed EndianSwap for option -4. Credits to Z80 0x90h.

* Fixed a bug on the bin convertion routine.

A simple tool to convert a binary file which will be mostly a payload, to a 
unsigned integer 32 Array, embeded into a JavaScript function call.
The application is ready to use for the PS4 OpenSource Hacking Community.

Added a second format for the .js to write. Simple use any flag to trigger it.
Added Vortex Payload Format.
Added back convertion supportfor all 3 formats.

Flags:
-1 = Foramt1 u32[]
-2 = Format2 p.write4addr.add(...
-3 = Format3 var payload = [....
-4 = js2bin