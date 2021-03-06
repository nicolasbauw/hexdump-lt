# hexdump-lt

[![Current Crates.io Version](https://img.shields.io/crates/v/hexdump-lt.svg)](https://crates.io/crates/hexdump-lt)
[![Downloads badge](https://img.shields.io/crates/d/hexdump-lt.svg)](https://crates.io/crates/hexdump-lt)


A minimalist, dependency free version of the hexdump utility.

To install:
```
cargo install hexdump-lt
````

Usage:
```text
hexdump-lt.exe "C:\Users\nbauw\.zoneinfo\America\Phoenix"
00000000 54 5A 69 66 32 00 00 00 00 00 00 00 00 00 00 00 |TZif2...........|
00000010 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 |................|
00000020 00 00 00 0B 00 00 00 04 00 00 00 10 80 00 00 00 |................|
00000030 9E A6 3A 90 9F BB 07 80 A0 86 1C 90 A1 9A E9 80 |..:.............|
00000040 CB 89 0C 90 CF 17 DF 1C CF 8F E5 AC D0 81 1A 1C |................|
00000050 FA F8 75 10 FB E8 58 00 02 01 02 01 02 03 02 03 |..u...X.........|
00000060 02 01 02 FF FF 96 EE 00 00 FF FF AB A0 01 04 FF |................|
00000070 FF 9D 90 00 08 FF FF AB A0 01 0C 4C 4D 54 00 4D |...........LMT.M|
00000080 44 54 00 4D 53 54 00 4D 57 54 00 54 5A 69 66 32 |DT.MST.MWT.TZif2|
00000090 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 |................|
000000A0 00 00 00 00 00 00 00 00 00 00 00 00 00 00 0B 00 |................|
000000B0 00 00 04 00 00 00 10 FF FF FF FF 5E 04 0C B0 FF |...........^....|
000000C0 FF FF FF 9E A6 3A 90 FF FF FF FF 9F BB 07 80 FF |.....:..........|
000000D0 FF FF FF A0 86 1C 90 FF FF FF FF A1 9A E9 80 FF |................|
000000E0 FF FF FF CB 89 0C 90 FF FF FF FF CF 17 DF 1C FF |................|
000000F0 FF FF FF CF 8F E5 AC FF FF FF FF D0 81 1A 1C FF |................|
00000100 FF FF FF FA F8 75 10 FF FF FF FF FB E8 58 00 02 |.....u.......X..|
00000110 01 02 01 02 03 02 03 02 01 02 FF FF 96 EE 00 00 |................|
00000120 FF FF AB A0 01 04 FF FF 9D 90 00 08 FF FF AB A0 |................|
00000130 01 0C 4C 4D 54 00 4D 44 54 00 4D 53 54 00 4D 57 |..LMT.MDT.MST.MW|
00000140 54 00 0A 4D 53 54 37 0A                         |T..MST7.........|
````

License: GPL-3.0
