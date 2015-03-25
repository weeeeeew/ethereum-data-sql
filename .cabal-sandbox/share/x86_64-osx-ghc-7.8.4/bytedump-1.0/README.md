Haskell Bytedump library
========================

This is a set of helper to dump bytes (list of word8, string, bytestring, lazy bytestring)
into nice to read tables like the unix utility hexdump.

Example
-------

this is an example using the default configuration.

```
 | 7f 45 4c 46 02 01 01 00 : 00 00 00 00 00 00 00 00  | .ELF............
 | 02 00 3e 00 01 00 00 00 : 68 5e 40 00 00 00 00 00  | ..>.....h^@.....
 | 40 00 00 00 00 00 00 00 : 00 99 0a 00 00 00 00 00  | @...............
 | 00 00 00 00 40 00 38 00 : 08 00 40 00 20 00 1d 00  | ....@.8...@. ...
 | 06 00 00 00 05 00 00 00 : 40 00 00 00 00 00 00 00  | ........@.......
 | 40 00 40 00 00 00 00 00 : 40 00 40 00 00 00 00 00  | @.@.....@.@.....
 | c0 01 00 00 00 00 00 00 : c0 01 00 00 00 00 00 00  | ................
 | 08 00 00 00 00 00 00 00 : 03 00 00 00 04 00 00 00  | ................
 | 00 02 00 00 00 00 00 00 : 00 02 40 00 00 00 00 00  | ..........@.....
 | 00 02 40 00 00 00 00 00 : 1c 00 00 00 00 00 00 00  | ..@.............
 | 1c 00 00 00 00 00 00 00 : 01 00 00 00 00 00 00 00  | ................
 | 01 00 00 00 05 00 00 00 : 00 00 00 00 00 00 00 00  | ................
 | 00 00 40 00 00 00 00 00 : 00 00 40 00 00 00 00 00  | ..@.......@.....
 | a4 e7 09 00 00 00 00 00 : a4 e7 09 00 00 00 00 00  | ................
 | 00 00 20 00 00 00 00 00 : 01 00 00 00 06 00 00 00  | .. .............
 | 00 f0 09 00 00 00 00 00 : 00 f0 69 00 00 00 00 00  | ..........i.....
 | 00 f0 69 00 00 00 00 00 : 98 a7 00 00 00 00 00 00  | ..i.............
 | 18 5f 01 00 00 00 00 00 : 00 00 20 00 00 00 00 00  | ._........ .....
 | 02 00 00 00 06 00 00 00 : 30 f0 09 00 00 00 00 00  | ........0.......
 | 30 f0 69 00 00 00 00 00 : 30 f0 69 00 00 00 00 00  | 0.i.....0.i.....
```
